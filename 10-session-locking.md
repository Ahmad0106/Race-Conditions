# Session-based Locking

Some frameworks process only one request per session.

## Example
- PHP session locking

## Effect
- Requests executed sequentially
- Race conditions become invisible

## Bypass
Use multiple sessions:
- session A
- session B
- session C
