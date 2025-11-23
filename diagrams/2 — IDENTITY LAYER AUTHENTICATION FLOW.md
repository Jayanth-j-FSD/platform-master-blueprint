User
 │
 │ 1. Register/Login Request
 ▼
┌──────────────────────┐
│   API GATEWAY         │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ AUTH SERVICE          │
│ - Password/FIDO/OAuth │
└──────────┬───────────┘
           │ Generates JWT + Refresh Token
           ▼
┌──────────────────────┐
│ SESSION SERVICE       │
│ - Stores session info │
│ - Device association  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ DEVICE TRUST ENGINE   │
│ - Fingerprint         │
│ - IP reputation       │
│ - Risk scoring        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ VERIFICATION SERVICE  │
│ - Email/Phone/OCR     │
│ - Aadhaar/Passport    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ TRUST GRAPH ENGINE    │
│ Adds weighted edges   │
└──────────────────────┘
