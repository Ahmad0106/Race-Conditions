# Prevention of Race Conditions

## Best Practices

### 1. Atomic operations
Use database transactions.

### 2. Avoid sub-states
Don't split logic into multiple steps.

### 3. Consistent storage
Don't mix session + DB + cache logic.

### 4. Integrity constraints
Use UNIQUE / PRIMARY KEY constraints.

### 5. Proper session handling
Ensure atomic session updates.

### 6. Avoid server-side state
Use stateless systems (carefully like JWT).
