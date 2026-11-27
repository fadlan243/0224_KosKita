# KosKita – Aplikasi Manajemen Kos dan Penghuni

Project Akhir **Pengembangan Aplikasi Mobile 2026** – Universitas Muhammadiyah Yogyakarta

| | |
|---|---|
| Nama | Fadlan Nasrizal Parma |
| NIM | 20240140224 |
| Repository | `0224_KosKita` |
| Tema | Bisnis |

## Deskripsi

KosKita adalah aplikasi mobile berbasis Jetpack Compose untuk membantu pemilik kos mengelola kamar, data penghuni, pencatatan pembayaran sewa bulanan, keluhan penghuni, dan pengumuman dalam satu aplikasi. Penghuni bisa melihat tagihan, mengunggah bukti transfer, dan mengirim keluhan, sedangkan pemilik kos bisa memverifikasi pembayaran dan memantau status kamar. Pembayaran dilakukan manual di luar aplikasi, jadi aplikasi hanya mencatat dan memverifikasi.

## Teknologi

- **Android:** Kotlin, Jetpack Compose, Navigation Compose, MVVM, Retrofit
- **Backend:** ASP.NET Core Web API (REST API, JWT)
- **Database:** MySQL

## Status Fitur

Keterangan: ✅ Selesai · 🚧 Sedang dikerjakan · ⏳ Belum

<!-- Ubah status dan tanggal sesuai yang benar-benar sudah dikerjakan -->

| Fitur | Status | Update terakhir |
|---|---|---|
| Login dan Register | ⏳ Belum | - |
| JWT dan Refresh Token | ⏳ Belum | - |
| Role-based UI (Pemilik dan Penghuni) | ⏳ Belum | - |
| Navigasi (Navigation Compose) | ⏳ Belum | - |
| CRUDS Kamar | ⏳ Belum | - |
| CRUDS Penghuni | ⏳ Belum | - |
| CRUDS Pembayaran | ⏳ Belum | - |
| CRUDS Keluhan | ⏳ Belum | - |
| CRUDS Pengumuman | ⏳ Belum | - |
| Dashboard | ⏳ Belum | - |
| File Storage (foto kamar dan bukti transfer) | ⏳ Belum | - |

## Progress Mingguan

### Pertemuan 9 (12-18 November 2026)

**Yang dikerjakan:**
- Memilih tema (Bisnis) dan judul project KosKita
- Menyusun deskripsi singkat project
- Merancang fitur awal, role pengguna, dan struktur database (daftar tabel dan relasi)

**Rencana berikutnya:** Menyusun SRS sesuai template

---

### Pertemuan 10 (19-25 November 2026)

**Yang dikerjakan:**
- Menyusun SRS KosKita sesuai template (kebutuhan fungsional dan non-fungsional, antarmuka, model data)
- Membuat repository 

**Rencana berikutnya:** Mulai tahap implementasi (database, backend, project Android)

<!-- Pastikan isi di atas sesuai kenyataan. Belum ada implementasi kode pada Pertemuan 9 dan 10. -->

---

### Pertemuan 11 (26 November - 2 Desember 2026)

- Membuat struktur folder, lalu push SRS ke `docs/`
- Setup database SQL Server dan project backend
- Membuat endpoint register dan login
- Setup project Android (Jetpack Compose dan Navigation Compose)

<!-- Setelah dikerjakan, ubah "rencana" jadi hasil yang sebenarnya, lalu update tabel Status Fitur -->

## Struktur Folder

```
0224_KosKita/
├── docs/            (SRS dan dokumen pendukung)
├── backend/         (ASP.NET Core Web API)
├── android/         (project Jetpack Compose)
└── README.md
```

<!-- Sesuaikan dengan struktur repo yang sebenarnya -->

## Cara Menjalankan

**Backend**
1. Buat database SQL Server dan jalankan script tabel (isi lokasi script)
2. Atur connection string di `appsettings.json`
3. Jalankan backend dengan `dotnet run`

**Android**
1. Buka folder `android` di Android Studio
2. Atur alamat API (BASE_URL) sesuai alamat backend
3. Jalankan di emulator atau HP

## Dokumen

- SRS: `docs/` (isi nama file)
