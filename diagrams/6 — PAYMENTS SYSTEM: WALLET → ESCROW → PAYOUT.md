User Wallet
 │
 │ Transfer
 ▼
┌─────────────────────────────┐
│ PAYMENTS LEDGER              │
│ - Immutable transaction log  │
└──────────────┬──────────────┘
               │ Escrow lock
               ▼
┌─────────────────────────────┐
│ ESCROW SERVICE               │
│ - Locks funds                │
│ - Tracks disputes            │
└──────────────┬──────────────┘
               │ Release
               ▼
┌─────────────────────────────┐
│ PAYOUT SERVICE               │
│ - Bank/UPI/Stripe transfer   │
└─────────────────────────────┘
