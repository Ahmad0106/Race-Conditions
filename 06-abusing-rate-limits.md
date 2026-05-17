#  Abusing Rate Limits

## Idea
Force server to slow itself down.

## Technique
- Send many dummy requests
- Trigger rate limiting
- Server introduces artificial delay

## Result
Better alignment for race condition attacks.
