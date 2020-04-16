### That sounds great, but why would Provisioned be needed?

Provisioned concurrency counts towards a function's reserved concurrency and Regional limits.

If the amount of provisioned concurrency on a function's versions and aliases adds up to the function's reserved concurrency, all invocations run on provisioned concurrency.

This configuration also has the effect of throttling the unpublished version of the function ($LATEST), which prevents it from executing.
