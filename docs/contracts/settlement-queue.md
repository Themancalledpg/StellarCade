# settlement-queue

## Public Methods

### `init`
Initialise the contract.

```rust
pub fn init(
```

### `enqueue_settlement`
Enqueue a new settlement.

```rust
pub fn enqueue_settlement(
```

### `process_next`
Process the next batch of settlements.

```rust
pub fn process_next(env: Env, batch_size: u32) -> Result<u32, Error>
```

### `mark_failed`
Mark a settlement as failed.

```rust
pub fn mark_failed(env: Env, settlement_id: Symbol, error_code: u32) -> Result<(), Error>
```

### `settlement_state`
Query the state of a settlement.

```rust
pub fn settlement_state(env: Env, settlement_id: Symbol) -> Option<SettlementData>
```

