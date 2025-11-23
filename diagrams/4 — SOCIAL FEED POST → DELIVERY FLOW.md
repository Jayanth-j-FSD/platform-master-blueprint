User Creates Post
 │
 ▼
┌──────────────────────────┐
│ POST SERVICE (Write)     │
└───────────┬──────────────┘
            │ Sends Event
            ▼
┌──────────────────────────┐
│ EVENT BUS (Kafka/NATS)   │
└───────────┬──────────────┘
            │
            ▼
┌──────────────────────────┐
│ FEED FAN-OUT WORKER      │
│ - Push to followers feed │
│ - Rank using trust graph │
└───────────┬──────────────┘
            │
            ▼
┌──────────────────────────┐
│ FEED STORAGE (Redis/ES)  │
└───────────┬──────────────┘
            │
            ▼
┌──────────────────────────┐
│ USER FEED API            │
└──────────────────────────┘
