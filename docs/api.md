# PKLCore V2 API Documentation 📘

**Version:** `v1.0.0 Stable`  
**Base URL:** `http://localhost/api`

---

## 🔐 Authentication
Sistem menggunakan **Laravel Sanctum** untuk autentikasi API. Semua endpoint yang dilindungi memerlukan header:
`Authorization: Bearer <token>`

---

## 📌 Core Modules (Proposed)

### 👨‍🎓 Data Siswa
- `GET /api/v1/students` - List semua siswa (with pagination & filters).
- `POST /api/v1/students` - Tambah siswa baru.
- `GET /api/v1/students/{id}` - Detail siswa.
- `PUT /api/v1/students/{id}` - Update data siswa.
- `DELETE /api/v1/students/{id}` - Hapus data siswa.

### 🏢 Data DU/DI (Industri)
- `GET /api/v1/industries` - List semua mitra industri.
- `POST /api/v1/industries` - Tambah mitra baru.
- `GET /api/v1/industries/{id}` - Detail industri.

### 🗺️ Live Monitoring & GPS
- `POST /api/v1/tracking/update` - Update koordinat GPS siswa (for Mobile App).
- `GET /api/v1/tracking/realtime` - Get posisi semua siswa aktif.

---

## 🤖 AI Analytics Endpoints
- `GET /api/v1/analytics/dropout-prediction` - Prediksi potensi masalah siswa.
- `GET /api/v1/analytics/placement-recommendations` - Rekomendasi penempatan DU/DI.

---

## 📄 Response Format
Semua response API mengikuti format standar JSON:
```json
{
    "status": "success",
    "message": "Data retrieved successfully",
    "data": { ... }
}
```

---

**© 2026 PKLCore V2 | API Documentation Draft**
