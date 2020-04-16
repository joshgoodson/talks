### Provisioned Concurrency

When Lambda allocates an instance of your function, the runtime loads your function's code and runs initialization code that you define outside of the handler.

If your code and dependencies are large, or you create SDK clients during initialization, this process can take some time.

As your function scales up, this causes the portion of requests that are served by new instances to have higher latency than the rest.
