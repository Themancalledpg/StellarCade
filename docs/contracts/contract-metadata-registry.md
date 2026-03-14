# contract-metadata-registry

## Public Methods

### `init`
Initialize the metadata registry with an admin.

```rust
pub fn init(env: Env, admin: Address) -> Result<(), Error>
```

### `register_metadata`
Register initial metadata for a contract.

```rust
pub fn register_metadata(
```

### `update_metadata`
Update metadata for an existing contract (incrementing version).

```rust
pub fn update_metadata(
```

### `metadata_of`
Query current metadata for a contract.

```rust
pub fn metadata_of(env: Env, contract_id: Address) -> Option<MetadataRecord>
```

### `history`
Query the complete history of metadata for a contract.

```rust
pub fn history(env: Env, contract_id: Address) -> Vec<MetadataRecord>
```

