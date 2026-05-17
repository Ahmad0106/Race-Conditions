#  Multi-endpoint Race Conditions

Occurs when multiple endpoints interact with same data.

## Example
- Add item to cart
- Checkout
- Modify cart before confirmation

## Exploit
Send requests to:
- /cart
- /checkout

At the same time → modify state during validation window.
