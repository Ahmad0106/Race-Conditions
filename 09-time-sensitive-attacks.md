#  Time-sensitive Attacks

No race condition needed.

## Idea
Exploit timestamp-based randomness.

## Example
Password reset token:
- token = hash(timestamp)

## Attack
Send requests at same time → identical timestamp → same token
