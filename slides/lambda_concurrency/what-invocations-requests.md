### Invocations and Requests

When your function is invoked, Lambda allocates an instance of it to process the event.

When the function code finishes running, it can handle another request.

If the function is invoked again while a request is still being processed, another instance is allocated, which increases the function's concurrency.
