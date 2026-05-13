# PKLCore V2 — RPL Core PKL Digital System 🚀

**Version:** `v1.0.0 Stable`  
**Powered by:** `Laravel 12 API`  
**Developer:** `YP 2026`

---

## 🌌 UI/UX Vision: The Future of Internship Management
PKLCore V2 dirancang dengan estetika **Premium & Futuristik (SaaS/Vercel Vibes)**. Fokus utama adalah memberikan pengalaman pengguna yang mulus melalui:
- **Arsitektur UI Modern:** Menggunakan Tailwind CSS dengan implementasi *Deep Dark Mode*.
- **Glassmorphism & Neon Accents:** Efek transparansi kaca dengan aksen cahaya neon untuk elemen interaktif.
- **Micro-interactions:** Navigasi yang responsif dan animasi halus untuk setiap transisi status.

---

## 🛠️ Tech Stack & Architecture
- **Backend:** Laravel 12 (API-First Architecture)
- **Database:** MySQL
- **Frontend Styling:** Tailwind CSS
- **Icons:** Phosphor Icons (Clean & Modular)
- **Visualisasi Data:** Chart.js with Smooth Curves & Gradient Fills
- **Maps:** Live GPS Simulation with Radar Effect UI

---

## 📂 Struktur Menu & Fitur Utama

### 1. Sidebar Navigasi (Modular)
- **DASHBOARD**
  - `Overview Insight`: Ringkasan performa dan statistik utama.
  - `Live Monitoring`: Pantauan realtime aktivitas siswa di lapangan.
- **DATA UTAMA**
  - `Data Siswa RPL`: Manajemen profil siswa (No, Kelas, NIS, Nama, JK, Tgl Larir, WhatsApp).
  - `Data DU/DI`: Database mitra industri (Nama, Pimpinan, NIP, Pembimbing, Alamat Detail, Rating).
  - `Bidang Usaha`: Klasifikasi paket keahlian (RPL, TKJ, TP, dsb).
- **MANAJEMEN PKL**
  - `Pengajuan Peserta`: Alur pendaftaran dan validasi tempat PKL.
  - `Jurnal Harian`: Monitoring aktivitas harian siswa.
  - `Dokumen & Surat`: Automasi pembuatan PDF (Surat Tugas, MoA, Sertifikat).
  - `Penilaian & Sertifikat`: Rekapitulasi nilai industri dan cetak sertifikat.
  - `Ceklis Kelengkapan`: Validasi dokumen keberangkatan dan kepulangan.
- **AI & SYSTEM**
  - `AI Analytics`: Analitik prediksi perilaku dan rekomendasi penempatan.
  - `Settings & API`: Konfigurasi sistem dan integrasi third-party.

### 2. Dashboard Widgets & Intelligence
- **Realtime Dashboard:** Mockup data aktif, indikator API Online, dan lencana status (Active, Pending, Offline).
- **Live Map Tracking:** Simulasi radar GPS dengan titik koordinat. **Smart Alert System** akan berkedip merah jika siswa terdeteksi keluar radius DU/DI.
- **AI Engine Insight:** Panel rekomendasi penempatan otomatis berdasarkan skill dan prediksi potensi masalah (Dropout/Inactivity detection).
- **Workflow Queue:** Tabel antrean manajemen pengajuan dengan status dinamis.

---

## 📊 Data Schema Highlights

### Data Siswa
| Field | Deskripsi |
| :--- | :--- |
| `No` | Primary Key / Index |
| `Kelas` | Tingkat & Jurusan |
| `NIS` | Nomor Induk Siswa |
| `Nama` | Nama Lengkap Peserta Didik |
| `JK` | Jenis Kelamin (L/P) |
| `Tgl Lahir` | Tanggal Lahir |
| `No WhatsApp` | Kontak Aktif Siswa |

### Data DU/DI
| Field | Deskripsi |
| :--- | :--- |
| `Paket Keahlian` | Kompetensi (RPL/TKJ/TP) |
| `Nama DU/DI` | Nama Perusahaan Mitra |
| `Alamat Lengkap` | Text Panjang + (Provinsi, Kab, Kec, Kel) |
| `Peringkat` | Star Rating (1-5 Stars) |
| `Daya Tampung` | Kapasitas Kuota Siswa |

---

## 🗺️ Roadmap Pengembangan (Phased Execution)

> [!IMPORTANT]
> Pengembangan dilakukan secara bertahap untuk menjaga konsistensi dan kualitas kode.

### 🏁 Phase 1: Foundation & Git Initialization
- [ ] Setup Repository `PKLCore-V2` di GitHub `yopaayy`.
- [ ] Inisialisasi Project Laravel 12 API.
- [ ] Setup Dokumentasi API (Swagger/Scalar).

### 🎨 Phase 2: UI/UX Shell & Design System
- [ ] Implementasi Tailwind Config (Dark Theme & Neon Colors).
- [ ] Pembuatan Layout Sidebar & Navbar (Glassmorphism).
- [ ] Setup Phosphor Icons Library.

### 🏗️ Phase 3: Database & Core API
- [ ] Migrasi Database (Siswa, DU/DI, Users).
- [ ] Pembuatan Resource API untuk Data Utama.
- [ ] Implementasi Authentication & Role Management.

### 📈 Phase 4: Interactive Dashboard UI
- [ ] Integrasi Chart.js untuk Trend Aktivitas.
- [ ] Mockup Widget Live Map dengan Radar Animation.
- [ ] Implementasi Realtime Indicators (Status API & Badges).

### 🤖 Phase 5: AI Integration & Workflow
- [ ] Setup AI Engine Insight Panel logic.
- [ ] Implementasi Document Generator (PDF Surats).
- [ ] Workflow Queue & Approval System.

### 🚀 Phase 6: Finalization & Future Sync
- [ ] Penyesuaian API untuk koneksi Frontend Siswa (Mobile App Prep).
- [ ] Final Bug Fixing & Security Hardening.

---

**© 2026 PKLCore V2 | Dev by YP | Stable Release**
