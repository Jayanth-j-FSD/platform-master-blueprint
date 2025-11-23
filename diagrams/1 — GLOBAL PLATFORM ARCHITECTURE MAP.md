                          ┌──────────────────────────┐
                          │        CLIENT APPS        │
                          │  Web • Mobile • Admin     │
                          └─────────────┬────────────┘
                                        │
                               (API Gateway Layer)
                                        │
             ┌──────────────────────────┴───────────────────────────┐
             │                                                      │
   ┌─────────▼──────────┐                            ┌──────────────▼───────────┐
   │   IDENTITY LAYER    │                            │     SOCIAL LAYER         │
   │  Auth • Users •     │                            │ Posts • Feed • Messages  │
   │  Devices • Verify   │                            │ Groups • Notifications   │
   └─────────┬───────────┘                            └──────────────┬───────────┘
             │                                                      │
             │                                                      │
   ┌─────────▼──────────┐                            ┌──────────────▼───────────┐
   │   TRUST GRAPH       │                            │     MARKETPLACE LAYER   │
   │ Graph DB • Scoring  │                            │ Listings • Orders       │
   │ Reputation • Edges  │                            │ Discovery • Reviews     │
   └─────────┬───────────┘                            └──────────────┬───────────┘
             │                                                      │
             │                                                      │
   ┌─────────▼──────────┐                            ┌──────────────▼───────────┐
   │  COLLABORATION      │                            │      PAYMENTS LAYER      │
   │  Workspaces • Files │                            │ Wallet • Escrow • Payout │
   │ Projects • Tasks    │                            │ Fraud • Settlement       │
   └─────────┬───────────┘                            └──────────────┬───────────┘
             │                                                      │
             └──────────────────────┬───────────────────────────────┘
                                    │
                             ┌──────▼──────┐
                             │   DATA/AI    │
                             │ Analytics    │
                             │ ML Engine    │
                             └──────────────┘
