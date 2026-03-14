# contract-monitoring

## Public Methods

### `init`
```rust
pub fn init(env: Env, admin: Address) -> Result<(), Error>
```

### `ingest_event`
```rust
pub fn ingest_event(env: Env, admin: Address, event_id: u64, kind: EventKind) -> Result<Metrics, Error>
```

### `set_paused`
```rust
pub fn set_paused(env: Env, admin: Address, paused: bool) -> Result<(), Error>
```

### `get_metrics`
```rust
pub fn get_metrics(env: Env) -> Metrics
```

### `get_health`
```rust
pub fn get_health(env: Env) -> HealthSnapshot
```

