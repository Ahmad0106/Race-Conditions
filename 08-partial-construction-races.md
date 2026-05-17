#  Partial Construction Race Conditions

Objects created in multiple steps.

## Problem
Temporary incomplete state exists.

## Example
- Create user
- Assign API key

Between steps → user exists but API key is NULL.

## Exploit
Send crafted input that matches NULL/uninitialized values.
