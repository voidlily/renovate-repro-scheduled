# 48314

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

(note: schedule in the original repo was "every weekday", for reproduction
purposes the schedule here is set to ~1 year from time of writing)

At time of writing, the js-md5 package needs an update, but has not hit the
scheduled time yet, so it's under "Awaiting Schedule".

Attempting to check the box to get the update now fails.

```text
DEBUG: Package not scheduled (branch="renovate/js-md5-0.x")
DEBUG: Skipping branch creation as not within schedule (branch="renovate/js-md5-0.x")
```

## Expected behavior

The js-md5 package should be allowed to update outside of the scheduled time if
requested manually. This may be a regression.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/48314
