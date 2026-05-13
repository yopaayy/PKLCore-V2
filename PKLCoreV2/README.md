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
  - `Overview Insight`: Pusat kendali utama dengan statistik realtime (Siswa Aktif, DU/DI, Absensi, Issues), Grafik Trend, Live GPS Radar, AI Insights, dan Antrean Validasi.
  - `Live Monitoring`: Pantauan khusus peta layar penuh untuk aktivitas siswa di lapangan.
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
- **Overview Insight Hub:**
  - **Header Controls:** Filter Tahun Ajaran, Tombol Export, Search Bar API routes, dan tombol **Quick Action**.
  - **Realtime Stat Cards:** Siswa PKL Aktif (counter + percentage), DU/DI Terhubung (+ new badge), Absensi Realtime (progress bar), dan Issue/Offline (alert badge).
  - **Trend Aktivitas & Jurnal:** Grafik multi-layer (Submission vs Validasi) dengan smooth curves dan gradient fill.
  - **Live GPS Tracking:** Widget peta dengan efek radar, pulsing dots (green/red), dan tombol Full Map.
  - **AI Engine Insight:** Panel rekomendasi penempatan (Auto/Manual), deteksi dropout/inaktivitas, dan tombol **Tanya AI Assistant**.
  - **Workflow Queue (Antrean Validasi):** Tabel dinamis untuk tracking status pendaftaran, pembuatan surat (PDF), dan jurnal harian.

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
- [ ] Implementasi Tailwind Config (Dark Theme, Neon Colors, Glassmorphism utilities).
- [ ] Pembuatan Sidebar Navigasi Modular & Header (Search, API Status, Quick Action).
- [ ] Setup Phosphor Icons Library & Typography (Inter/Outfit).

### 🏗️ Phase 3: Database & Core API
- [ ] Migrasi Database: `students`, `industries`, `internships`, `journals`, `notifications`.
- [ ] Pembuatan Resource API & Controller untuk Data Utama.
- [ ] Setup Laravel Sanctum/Passport untuk Auth.

### 📈 Phase 4: Overview Insight & Visuals
- [ ] **Stat Cards**: Implementasi 4 card utama dengan progress bar & badges.
- [ ] **Activity Chart**: Integrasi Chart.js (Gradient curves, selection weekly/monthly).
- [ ] **Live Radar Map**: Pembuatan widget GPS dengan CSS animations (pulsing & radar).

### 🤖 Phase 5: AI Engine & Workflow Queue
- [ ] **AI Insight Panel**: UI untuk rekomendasi & prediksi masalah.
- [ ] **Workflow Queue**: Tabel antrean dengan status badges & action buttons.
- [ ] **PDF Generator**: Integrasi DomPDF/Browsershot untuk surat tugas & sertifikat.

### 🚀 Phase 6: Finalization & Integration
- [ ] Sinkronisasi data realtime (API Status Indicator logic).
- [ ] Final UI Polish (Transitions, Hover effects, Glassmorphism refinements).
- [ ] Dokumentasi API lengkap & Final Testing.

---

**© 2026 PKLCore V2 | Dev by YP | Stable Release**
