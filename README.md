# 🅿️ ParkFinder – Sistem Parkir Pintar Berbasis IoT

**ParkFinder** adalah proyek skripsi kolaboratif yang bertujuan untuk menyelesaikan masalah parkir di area publik seperti rumah sakit dan kantor pemerintahan. Dengan menggabungkan teknologi **Internet of Things (IoT)**, **Realtime Cloud Database**, dan **aplikasi mobile Flutter**, ParkFinder memungkinkan pengguna untuk memantau slot parkir secara real-time, melakukan pemesanan slot, dan menavigasi ke lokasi parkir yang tersedia.

## 👥 Tim Pengembang

- **Imam Ariadi** – *Frontend Developer (Flutter)*
- **Ivan Alif Hadrian** – *Backend Developer*
- **Anastasia Citra Negara** – *IoT Engineer*

## 📱 Deskripsi Aplikasi

ParkFinder adalah sistem parkir cerdas berbasis IoT yang terdiri dari:

- **Sensor ultrasonik HC-SR04** untuk mendeteksi keberadaan kendaraan di slot parkir.
- **ESP32** sebagai mikrokontroler yang mengirimkan data ke cloud secara real-time.
- **Firebase Realtime Database** sebagai penyimpanan data.
- **Aplikasi Flutter** sebagai antarmuka pengguna.

### Fitur Utama:

- ✅ Informasi slot parkir kosong/terisi secara real-time.
- 📍 Navigasi menuju lokasi parkir.
- ⏳ Timer durasi parkir dan notifikasi waktu habis.
- 📖 Riwayat dan detail parkir sebelumnya.
- 🧾 Estimasi biaya parkir.

## 🎯 Tujuan & Manfaat

- Mengurangi waktu pencarian parkir.
- Mengurangi konsumsi bahan bakar dan emisi karbon.
- Meningkatkan efisiensi operasional rumah sakit dan kantor pemerintahan.
- Mendukung SDGs 9, 11, dan 13 serta Industri 4.0.

## 🧰 Teknologi yang Digunakan

| Komponen    | Teknologi / Tools                           |
|-------------|----------------------------------------------|
| Frontend    | Flutter (Dart)                               |
| Backend     | Firebase Realtime Database, Node.js (API)    |
| IoT         | ESP32, Sensor Ultrasonik HC-SR04             |
| Cloud       | Firebase                                      |
| IDE         | Android Studio, VS Code, Arduino IDE         |

## 🖼️ Mockup UI/UX

Lihat desain antarmuka aplikasi kami pada tautan berikut:  
👉 [UI/UX Mockup ParkFinder](https://www.figma.com/file/CONTOH_LINK_DESAIN_PARKFINDER)  
*(Ganti dengan tautan aslimu di Figma atau platform desain lainnya)*



## ⚙️ Alur Sistem

1. Sensor mendeteksi kendaraan masuk/keluar.
2. Mikrokontroler ESP32 mengirim status ke Firebase.
3. Aplikasi Flutter menampilkan data secara real-time.
4. Pengguna dapat memesan, menavigasi, dan memantau durasi parkir.

## ✅ Pengujian Sistem

| Uji                    | Hasil yang Diharapkan                          |
|------------------------|-------------------------------------------------|
| Deteksi Sensor         | Akurasi >90% untuk deteksi kendaraan           |
| Latensi Sistem         | Update data < 10 detik                         |
| Realtime UI            | Indikator slot terisi (merah), kosong (hijau) |
| Navigasi               | Arahkan ke slot parkir dengan cepat & akurat  |

## 🗓️ Status

📊 **Tahap pengembangan** – seluruh komponen sedang dibangun sesuai timeline tugas akhir.

## 📬 Kontak

| Nama                   | Peran               | Kontak                 |
|------------------------|---------------------|------------------------|
| Imam Ariadi            | Frontend Developer  | [imamariadi775@gmail.com]   |
| Ivan Alif Hadrian      | Backend Developer   | [email/media sosial]   |
| Anastasia Citra Negara | IoT Engineer        | [email/media sosial]   |

---

> 🚘 *"Parkir bukan sekadar tempat — tetapi pengalaman yang efisien, cerdas, dan terintegrasi."*
```

---

