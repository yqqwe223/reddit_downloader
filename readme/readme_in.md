# Reddit Video Parser Tool 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Bahasa_Indonesia-yellow.svg)

## 📋 Gambaran Proyek

**Reddit Video Parser Tool** adalah utilitas berbasis web yang dirancang untuk membantu pendidik, peneliti, dan pelajar individu dalam menganalisis secara teknis konten video yang dapat diakses publik di platform Reddit, untuk keperluan pengarsipan dan studi berdasarkan prinsip "penggunaan wajar" (Fair Use). Alat ini berfokus pada penyediaan dukungan teknis yang bersih dan efisien untuk skenario non-komersial, seperti pengumpulan kasus pengajaran, penelitian media sosial, analisis budaya digital, dan manajemen pengetahuan pribadi.

🔗 **Demo Langsung**: [https://twittervideodownloaderx.com/reddit_downloader_in](https://twittervideodownloaderx.com/reddit_downloader_in)

> ⚠️ **Penting**: Proyek ini dikembangkan semata-mata untuk tujuan pembelajaran teknis dan penelitian. Pengguna diharapkan mematuhi hukum hak cipta yang berlaku dan ketentuan layanan platform, menghormati hak kreator asli, serta tidak menggunakan alat ini untuk aktivitas apa pun yang melanggar hak kekayaan intelektual atau kebijakan platform.

---

## ✨ Fitur Utama

- 🔗 **Pengenalan Tautan Cerdas**: Menganalisis otomatis tautan posting Reddit, tautan video langsung, dan berbagai format lainnya
- 📥 **Adaptasi Kualitas**: Menampilkan opsi resolusi yang tersedia berdasarkan metadata sumber (tergantung ketersediaan platform)
- 📱 **Kompatibilitas Multi-Perangkat**: Desain responsif yang dioptimalkan untuk browser desktop dan mobile
- 🔐 **Desain Berorientasi Privasi**: Tidak ada log aktivitas pengguna yang disimpan; tidak ada konten yang diproses disimpan di server
- ⚡ **Ringan & Cepat**: Logika pemrosesan berpusat pada klien meminimalkan ketergantungan server untuk respons cepat
- 🔄 **Pemeliharaan Aktif**: Pembaruan rutin untuk beradaptasi dengan perubahan frontend platform dan memastikan fungsionalitas berkelanjutan
- 💬 **Ekstraksi Metadata**: Ekstraksi opsional informasi publik seperti judul posting, penulis, subreddit (hanya untuk tujuan anotasi penelitian)

---

## 🚀 Panduan Memulai Cepat

### Langkah 1: Dapatkan Tautan Video
1. Buka situs web atau aplikasi Reddit
2. Temukan **posting video yang tersedia secara publik** yang ingin Anda analisis
3. Klik "Bagikan" → "Salin tautan", atau salin langsung URL posting dari bilah alamat browser

### Langkah 2: Kirim untuk Diproses
1. Navigasi ke: `https://twittervideodownloaderx.com/reddit_downloader_in`
2. Tempelkan tautan yang telah disalin ke bidang input yang disediakan
3. Klik tombol "Mulai Analisis"

### Langkah 3: Tinjau Hasil
1. Tunggu sistem menyelesaikan analisis teknis (biasanya beberapa detik)
2. Tinjau pratinjau metadata video dan informasi yang tersedia
3. Lanjutkan dengan tindakan berikutnya sesuai petunjuk (hanya untuk tujuan pembelajaran pribadi)

---

## 💡 Format Tautan yang Didukung

```
✅ Pola URL yang direkomendasikan:
- https://www.reddit.com/r/subreddit/comments/xxxxx/video_title/
- https://old.reddit.com/r/subreddit/comments/xxxxx/
- https://v.redd.it/xxxxxxxxxxx/

❌ Skenario yang saat ini tidak didukung:
- Posting yang diatur sebagai "hanya pengguna diundang" atau telah dihapus
- Konten terbatas yang memerlukan autentikasi atau login untuk mengakses
- Video yang dilindungi oleh Manajemen Hak Digital (DRM) tingkat lanjut
- Konten yang melanggar pedoman komunitas Reddit
```

---

## ⚙️ Arsitektur Teknis

| Komponen | Implementasi | Deskripsi |
|----------|--------------|-----------|
| **Frontend** | HTML5 + CSS3 + Vanilla JS | Tanpa framework untuk pemuatan cepat, kompatibilitas tinggi |
| **Penangan Permintaan** | Node.js / Python Backend | Asinkron non-blocking, dukungan konkurensi tinggi, operasi stabil |
| **Parser Konten** | Ekspresi Reguler + Analisis DOM + API Reddit | Hanya mengekstrak metadata publik; tanpa bypass enkripsi, menghormati otorisasi |
| **Lapisan Keamanan** | HTTPS + Sanitasi Input + Pembatasan Laju | Mencegah penyalahgunaan, memastikan stabilitas layanan, melindungi privasi pengguna |
| **Penyebaran** | Docker + Akselerasi CDN | Node terdistribusi global untuk akses latensi rendah, skalabilitas elastis |

---

## ⚠️ Pernyataan Kepatuhan dan Penggunaan Bertanggung Jawab

Alat ini beroperasi secara ketat berdasarkan prinsip **netralitas teknis** dan **penggunaan wajar**. Harap perhatikan panduan berikut:

### ✅ Kasus Penggunaan yang Diizinkan
- 📚 Institusi pendidikan menganalisis kasus penyebaran media sosial untuk studi akademis
- 🔬 Proyek penelitian yang melibatkan pengambilan sampel, anotasi, dan analisis budaya konten video digital
- 🗂️ Peneliti individu yang mengatur materi referensi untuk inspirasi (dengan atribusi yang sesuai)
- 🌐 Akses pembelajaran offline di wilayah dengan konektivitas internet terbatas
- 📊 Pengamatan dan pendokumentasian fenomena budaya digital untuk tujuan non-komersial

### ❌ Aktivitas yang Dilarang
- 🚫 Menggunakan konten yang diproses untuk distribusi komersial, redistribusi sekunder, atau monetisasi trafik
- 🚫 Menghapus informasi penulis asli atau watermark dan memposting ulang konten sebagai karya orisinal
- 🚫 Scraping massal, pengumpulan data otomatis, atau mengganggu operasi Reddit
- 🚫 Mencoba melewati kontrol akses untuk melihat konten yang tidak publik atau terbatas
- 🚫 Menggunakan untuk menyebarkan konten ilegal, melanggar hak, atau bertentangan dengan pedoman komunitas

### 📜 Kerangka Referensi Hukum
- Undang-Undang Hak Cipta Indonesia No. 28 Tahun 2014 (pasal tentang penggunaan wajar dan pengecualian)
- Undang-Undang Informasi dan Transaksi Elektronik (ITE) terkait aspek privasi dan perlindungan data
- Kebijakan Konten dan Ketentuan Layanan platform Reddit
- Prinsip yudisial internasional yang diakui tentang "penggunaan wajar" (Fair Use)

> 📌 **Penyangkalan**: Pengembang tidak bertanggung jawab atas penyalahgunaan alat ini. Dengan menggunakan perangkat lunak ini, Anda menyatakan telah membaca, memahami, dan setuju untuk mematuhi ketentuan yang diuraikan di atas.

---

## 🤝 Berkontribusi

Kami menyambut kontribusi dari komunitas untuk membantu meningkatkan proyek ini:

```bash
# 1. Fork repositori ini
# 2. Buat branch fitur baru
git checkout -b feature/perbaikan

# 3. Commit perubahan Anda
git commit -m "feat: meningkatkan logika pengenalan tautan Reddit"

# 4. Push dan buka Pull Request
git push origin feature/perbaikan
```

**Panduan Kontribusi**:
- Ikuti konvensi gaya kode ESLint / Prettier
- Sertakan pengujian unit untuk fungsionalitas baru bila memungkinkan
- Gunakan pesan commit yang jelas dan deskriptif dalam Bahasa Indonesia atau Inggris
- Dokumentasikan fitur baru baik dalam komentar kode maupun pembaruan README
- Pastikan kiriman lolos pemeriksaan kode dasar sebelum dikirim

---

## 🐛 Melaporkan Masalah

Menemukan bug atau memiliki saran perbaikan?

1. Periksa terlebih dahulu tab [Issues](../../issues) untuk menghindari duplikasi
2. Saat membuat issue baru, harap sertakan:
   - Nama dan versi browser
   - Instruksi reproduksi langkah demi langkah
   - Perilaku yang diharapkan vs. perilaku aktual
   - Tangkapan layar atau log error (jika ada)
   - Contoh tautan posting Reddit (dengan informasi sensitif dianonimkan)
3. Tim kami meninjau kiriman secara berkala dan akan merespons secepat mungkin

---

## 📄 Lisensi

Proyek ini didistribusikan di bawah **Lisensi MIT**. Anda bebas menggunakan, memodifikasi, dan mendistribusikan perangkat lunak ini, dengan syarat pemberitahuan hak cipta asli dan ketentuan lisensi tetap dipertahankan.

```
MIT License

Copyright (c) 2024 Reddit Video Parser Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Ucapan Terima Kasih

- Terima kasih kepada komunitas open-source atas penyediaan komponen teknis yang andal dan inspirasi
- Apresiasi kepada pengguna dan peneliti akademis yang berkontribusi dengan umpan balik berharga
- Pengakuan kepada kreator konten di Reddit yang karyanya memperkaya nilai konten budaya digital

---

> 📬 **Dukungan & Kontak**: Untuk pertanyaan kolaborasi teknis atau pertanyaan terkait kepatuhan, silakan kirim tiket melalui GitHub Issues. Kami berupaya merespons semua permintaan yang sah dengan cepat.

*Proyek ini tidak berafiliasi, disetujui, atau disponsori oleh Reddit Inc. atau afiliasinya. Semua merek dagang, logo, dan nama merek adalah milik masing-masing pemilik. Alat ini hanya menyediakan dukungan teknis analisis dan tidak melakukan penyimpanan, distribusi, atau klaim kepemilikan atas konten pihak ketiga.*