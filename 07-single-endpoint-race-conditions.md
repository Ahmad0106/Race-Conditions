# Single-endpoint Race Conditions

Occurs when one endpoint handles multiple inputs simultaneously.

## Example
Password reset:
- Request A: victim
- Request B: attacker

Both modify same session → collision.

## Result
Mixed state:
- victim data
- attacker-controlled token
