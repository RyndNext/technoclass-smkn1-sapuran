# User Flow Documentation

# TechnoClass Learning & Assessment System

Version: 1.0

---

# Overview

Dokumen ini menjelaskan alur interaksi pengguna (User Flow) dalam sistem TechnoClass.

Aktor utama:

- Admin
- Guru
- Siswa

---

# Student User Flow

## Login Flow

```text
START
  │
  ▼
Login
  │
  ▼
Validasi Akun
  │
  ├── Gagal
  │      │
  │      ▼
  │   Pesan Error
  │      │
  │      ▼
  │    Login
  │
  └── Berhasil
           │
           ▼
      Dashboard Siswa
```

---

## Learning Flow

```text
Dashboard
   │
   ▼
Pilih Pertemuan
   │
   ▼
Lihat Tujuan Pembelajaran
   │
   ▼
Tonton Video Pembelajaran
   │
   ▼
Baca Materi
   │
   ▼
Mengerjakan LKPD
   │
   ▼
Submit LKPD
   │
   ▼
Menunggu Penilaian
   │
   ▼
Lihat Feedback
   │
   ▼
Selesai
```

---

## Assignment Submission Flow

```text
Pilih LKPD
   │
   ▼
Isi Form Jawaban
   │
   ▼
Upload File (Opsional)
   │
   ▼
Klik Submit
   │
   ▼
Validasi Data
   │
   ├── Error
   │      │
   │      ▼
   │  Perbaiki Jawaban
   │
   └── Valid
          │
          ▼
      Simpan Data
          │
          ▼
      Status Submitted
```

---

## Grade Review Flow

```text
Dashboard
   │
   ▼
Menu Nilai
   │
   ▼
Pilih Pertemuan
   │
   ▼
Lihat Nilai
   │
   ▼
Lihat Feedback Guru
```

---

# Teacher User Flow

## Login Flow

```text
START
  │
  ▼
Login Guru
  │
  ▼
Validasi Akun
  │
  ▼
Dashboard Guru
```

---

## Material Management Flow

```text
Dashboard Guru
      │
      ▼
Kelola Materi
      │
      ▼
Tambah Materi
      │
      ▼
Upload Dokumen
      │
      ▼
Upload Video
      │
      ▼
Publish Materi
```

---

## Assessment Flow

```text
Dashboard Guru
       │
       ▼
Pilih Kelas
       │
       ▼
Pilih Pertemuan
       │
       ▼
Lihat Pengumpulan LKPD
       │
       ▼
Beri Nilai
       │
       ▼
Tambahkan Feedback
       │
       ▼
Simpan Penilaian
       │
       ▼
Update Rekap Nilai
```

---

## Report Generation Flow

```text
Dashboard Guru
       │
       ▼
Menu Rapor
       │
       ▼
Pilih Kelas
       │
       ▼
Generate Nilai Akhir
       │
       ▼
Validasi Data
       │
       ▼
Generate PDF
       │
       ▼
Download Rapor
```

---

# Admin User Flow

## User Management

```text
Dashboard Admin
       │
       ▼
Kelola Pengguna
       │
       ▼
Tambah Guru
       │
       ▼
Tambah Siswa
       │
       ▼
Kelola Kelas
       │
       ▼
Simpan
```

---

# Meeting Learning Flow

## Pertemuan 1

```text
Tujuan Pembelajaran
       │
       ▼
Video Service Advisor
       │
       ▼
Materi PKB
       │
       ▼
Simulasi PKB
       │
       ▼
Simulasi RAB
       │
       ▼
LKPD
       │
       ▼
Submit
```

---

## Pertemuan 2

```text
Tujuan Pembelajaran
       │
       ▼
Video SWOT dan BEP
       │
       ▼
Materi
       │
       ▼
SWOT Builder
       │
       ▼
BEP Calculator
       │
       ▼
LKPD
       │
       ▼
Submit
```

---

## Pertemuan 3

```text
Tujuan Pembelajaran
       │
       ▼
Video Business Model Canvas
       │
       ▼
Canvas Builder
       │
       ▼
Upload Proposal
       │
       ▼
Pitching
       │
       ▼
Penilaian
```

---

# Success Criteria

## Student

- Login berhasil
- Materi selesai dipelajari
- LKPD berhasil dikumpulkan
- Nilai dapat dilihat

## Teacher

- Materi berhasil dipublikasikan
- Penilaian berhasil dilakukan
- Rapor berhasil dibuat

## Admin

- Data pengguna terkelola dengan baik
- Kelas dan tahun ajaran aktif

---

# Future Enhancements

- AI Feedback
- Gamifikasi Pembelajaran
- Sertifikat Otomatis
- Integrasi Email Notifikasi
- Integrasi WhatsApp Notifikasi
- Dashboard Analitik Lanjutan
