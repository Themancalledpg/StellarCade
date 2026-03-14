# cross-contract-call-guard

## Public Methods

### `init`
Initialize the guard with an admin address.

```rust
pub fn init(env: Env, admin: Address) -> Result<(), Error>
```

### `allow_call`
Allow a specific cross-contract call. Admin only.

```rust
pub fn allow_call(
```

### `deny_call`
Deny (remove permission for) a specific cross-contract call. Admin only.

```rust
pub fn deny_call(
```

### `assert_allowed`
Assert that a call is allowed. Traps/Errs if not found or explicitly denied.

```rust
pub fn assert_allowed(
```

### `policy_state`
Check the state of a specific policy.

```rust
pub fn policy_state(
```

