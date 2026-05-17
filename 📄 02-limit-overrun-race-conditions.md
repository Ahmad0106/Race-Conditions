#  Limit Overrun Race Conditions

## Concept
Occurs when repeated requests bypass business limits.

## Examples
- Redeeming gift cards multiple times
- Using coupon codes repeatedly
- Bypassing rate limits
- Withdrawing more money than allowed

## Root Cause
Time-of-check vs time-of-use (TOCTOU)

## Exploit
Send multiple requests simultaneously to hit race window before limit is applied.
