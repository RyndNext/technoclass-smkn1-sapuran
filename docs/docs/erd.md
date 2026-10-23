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
CLASSES
     │
     ▼
MEETINGS
     │
     ▼
MATERIALS
     │
     ▼
ASSIGNMENTS
     │
     ▼
SUBMISSIONS
1 Class
   └── banyak Student

1 Meeting
   ├── banyak Materi
   ├── banyak LKPD
   └── banyak Penilaian

   
