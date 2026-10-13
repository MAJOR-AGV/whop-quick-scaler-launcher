# Support reply preparation

By Major · Unofficial

Derived from [Customer support](../../skills/whop-quick-scaler-launcher/references/customer-support.md). Reference date: 2026-09-29. These are reply patterns for a merchant to review, not messages sent by the assistant. The bot cannot inspect private payments, change access or refund money. Customer identity and payment details belong in the merchant's secure support channel.

## Failed payment

Separate initial purchase from renewal. A pending or uncertain outcome needs reconciliation before another attempt. Do not invent the decline reason or promise an approval. Updating a saved method may trigger payment recovery.

Draft for an uncertain outcome: "Please do not submit another payment while the existing attempt is being checked. Keep card details and sign-in codes out of this conversation."

## Missing access

Use the existing order confirmation and the same purchase identity. Check payment, membership, product attachment and actual content as separate stages. Administrator access does not prove buyer access.

Draft: "Open the Access button in your Whop order confirmation and sign in using the same address that received it. Enter sign-in codes only on Whop. Do not buy again. If access still fails, share only the redacted error through the merchant's private support channel."

## Refund request

Check the applicable terms and consumer rights, existing refunds or disputes, payment status and the requested outcome. Cancellation, refund and access removal are separate effects. Never promise acceptance or bank-arrival timing.

Draft: "The refund request needs review against the payment and the terms at purchase. No refund is confirmed yet. If you already have a case in Whop, continue in that case rather than opening another."

## Possible duplicate payment

Matching amounts alone do not prove duplicate settled charges. Distinguish a pending authorization, installment, renewal and separate purchase. Any correction must preserve the legitimate purchase.

Draft: "Please do not make another payment. The merchant needs to distinguish a second completed charge from a pending authorization or another billing event before proposing a correction."

## Before purchase

Draft from confirmed offer facts only: "The product includes [verified contents]. Payment is [approved amount, currency and cadence]. Access lasts [defined period] through [delivery route]. Support and refund terms are [verified terms]."

Replace or remove every bracketed field before sending. Do not turn a draft into a statement that an investigation or account change already occurred. The human approves the final recipient, message and any separate financial action.

Official sources checked 2026-09-29: [Failed subscription payments](https://docs.whop.com/payments-and-billing/payment-issues/troubleshoot-failed-payments.md), [Request a refund and find a missing purchase](https://docs.whop.com/memberships-and-access/cancellations-and-refunds/request-a-refund.md).
