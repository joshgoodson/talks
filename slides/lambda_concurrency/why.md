### Why should we care?

Concurrency is subject to a Regional limit that is shared by all functions in a Region.

To ensure that a function can always reach a certain level of concurrency, you can configure the function with reserved concurrency.

When a function has reserved concurrency, no other function can use that concurrency.

Reserved concurrency also limits the maximum concurrency for the function, and applies to the function as a whole, including versions and aliases.
