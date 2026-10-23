┌─────────────┐
│   USERS     │
├─────────────┤
│ id (PK)     │
│ email       │
│ password    │
│ role        │
└──────┬──────┘
       │
       │
 ┌─────▼─────┐
 │ PROFILES  │
 ├───────────┤
 │ id        │
 │ user_id   │
 │ nama      │
 │ avatar    │
 └─────┬─────┘
       │
       │
 ┌─────▼─────────┐
 │ STUDENTS      │
 ├───────────────┤
 │ id            │
 │ profile_id    │
 │ nis           │
 │ class_id      │
 └─────┬─────────┘
       │
       │
 ┌─────▼───────┐
 │ CLASSES     │
 ├─────────────┤
 │ id          │
 │ nama        │
 │ tahun       │
 └─────────────┘
