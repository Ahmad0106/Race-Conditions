#  Connection Warming

Used to eliminate backend initialization delays.

## Technique
Send harmless request first:
- GET /

Then send attack requests.

## Goal
Ensure all requests share same warmed connection for consistent timing.
