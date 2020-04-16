### Configuring Reserved Concurrency

You can reserve up to the **Unreserved account concurrency** value that is available, minus 100 for functions that don't have reserved concurrency. The unreserved account concurrency balance today in our production account is 1,000.

To throttle a function, set the reserved concurrency to zero. This stops any events from being processed until you remove the limit.
