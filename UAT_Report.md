# UAT Report

**Scope:** Checkout, Payments, Order Confirmation  
**Participants:** Product Owner, QA Lead, 2 Business Users  
**Environment:** Staging

## Acceptance Criteria
- Able to place an order with valid payment details.
- Coupons apply correctly to totals.
- Confirmations (on-screen + email) are triggered.

## Summary
- **Pass rate:** 15/16 critical scenarios passed (93.7%).
- **Blocking issue:** Payment API timeout during peak (BUG-1011).
- **Decision:** Conditional sign-off with plan to re-test after API fix.

## Notes
Screenshots and evidence stored under `Screenshots/`.
