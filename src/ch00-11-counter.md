# Simple Counter

This is a smiple counter contract.

Here's how it works:

- The contract has a state variable called 'counter' that is initialized to 0.

- When a user calls 'increment', the contract increments the counter by 1.

- When a user calls 'decrement', the contract decrements the counter by 1.

```rust
{{#include ../listings/ch00-introduction/counter/src/counter.cairo}}
```
