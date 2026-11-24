# ⛵ Nusantara Math Adventure: Misi Sabang Sampai Merauke

**Nusantara Math Adventure** adalah aplikasi web edukasi matematika interaktif berbasis petualangan budaya Indonesia untuk siswa Sekolah Dasar (**Kelas 1 – 6 SD**) yang dirancang selaras dengan **Kurikulum Merdeka** (Fase A, Fase B, dan Fase C).

Siswa berperan sebagai **Kapten Penjelajah** yang berlayar menggunakan kapal virtual melintasi **7 kepulauan ikonik Indonesia** dari **Sumatra (Sabang)** hingga **Papua (Merauke)**. Setiap pulau menghadirkan permainan tradisional Nusantara, tantangan berhitung bertahap, ragam budaya daerah, serta **Sertifikat Kelulusan Digital** yang siap dicetak.

---

## ✨ Fitur Utama

### 1. 🗺️ Peta Interaktif Kepulauan Nusantara
- Kapal penjelajah otomatis berlayar dari satu pulau ke pulau berikutnya setiap kali siswa berhasil menyelesaikan 3 tantangan soal pada sebuah pos.
- Meliputi **7 Pos Petualangan & Permainan Tradisional**:
  1. **Pos 1 – Sumatra**: *Permainan Gasing Tradisional*
  2. **Pos 2 – Jawa**: *Permainan Dakon / Congklak*
  3. **Pos 3 – Kalimantan**: *Permainan Enggrang Bambu*
  4. **Pos 4 – Sulawesi**: *Permainan Lompat Karet (Yeye)*
  5. **Pos 5 – Bali & Nusa Tenggara**: *Tari Topeng Nusantara*
  6. **Pos 6 – Maluku**: *Permainan Bentengan*
  7. **Pos 7 – Papua (Boss Level)**: *Panahan Tradisional Kaseang & Final Boss*

### 2. 📚 Materi Kurikulum Merdeka (Kelas 1 – 6 SD)
Siswa (atau guru melalui tautan khusus) dapat memilih jenjang kelas sesuai tingkat belajarnya:
- **Kelas 1 SD (Fase A)**: Bilangan Cacah 1–20, Penjumlahan & Pengurangan $\le 20$, Bangun Datar, Pola Bilangan Loncat, serta Pengukuran Waktu & Panjang.
- **Kelas 2 SD (Fase A)**: Nilai Tempat s.d. 100, Perkalian Dasar ($\times 2, \times 3, \times 5$), Pembagian Dasar, Nilai Uang Rupiah, serta Satuan Panjang & Berat.
- **Kelas 3 SD (Fase B)**: Misi Utama Perkalian $4$ sampai $10$ serta Tantangan Campuran Final Boss.
- **Kelas 4 SD (Fase B)**: Bilangan Cacah Besar s.d. $10.000$, KPK & FPB Dasar, Pecahan & Desimal, Luas Bangun Datar, Besar Sudut ($^\circ$), dan Piktogram.
- **Kelas 5 SD (Fase C)**: Operasi Pecahan & Persen, Luas Segitiga & Jajar Genjang, Volume Kubus & Balok, Kecepatan ($J = K \times W$), Skala Peta, dan Debit Air.
- **Kelas 6 SD (Fase C)**: Operasi Bilangan Bulat Negatif, Keliling & Luas Lingkaran ($\pi$), Volume Tabung & Prisma, Rasio & Proporsi, Statistika (*Mean, Median, Modus*), dan Luas Permukaan Bangun Ruang.

### 3. 💡 Bantuan Kakak Pintar & Visualisasi Benda
- **Visualisasi Kelompok Benda**: Setiap soal dilengkapi ilustrasi pengelompokan ikon benda budaya untuk membantu pemahaman konseptual siswa.
- **Bantuan Kakak Pintar**: Panduan strategi cepat interaktif (termasuk simulasi **10 jari perkalian $9$**, penjumlahan berulang, serta rumus cepat Kurikulum Merdeka).

### 4. 🏛️ Wawasan Budaya Nusantara, Narator & Musik Latar
- **Katalog Budaya Nusantara**: Di setiap pulau, siswa dapat mengenal Rumah Adat, Tarian Khas, Alat Musik Tradisional, dan Kuliner/Kriya daerah.
- **Narator Bersuara Otomatis (*Text-to-Speech* `id-ID`)**: Membacakan kisah petualangan, soal cerita, umpan balik jawaban, dan fakta unik daerah secara ramah anak.
- **Musik Latar Pentatonis (Tone.js)**: Melodi pengiring bernuansa slendro Nusantara yang dapat dinyalakan atau dimatikan kapan saja.

### 5. 👩‍🏫 Dashboard Admin / Guru & Sinkronisasi Cloud Lintas Perangkat
Dilengkapi panel khusus guru/admin (**Username:** `admin` | **PIN:** `1234` atau `guru123`) dengan fitur:
- **Pemantauan Siswa Real-Time**: Melihat total siswa terdaftar, jumlah siswa lulus ($7/7$ pulau), rata-rata bintang, akurasi jawaban, serta log aktivitas siswa lintas perangkat/browser.
- **Generator Link Khusus Siswa**: Membuat tautan undangan khusus dengan parameter otomatis (`?kelas=3&ruang=3A&kunci=1`) agar jenjang kelas siswa langsung terkunci sesuai rombel.
- **Kelola Bank Soal (CRUD)**: Menambah soal baru, mengedit soal yang ada, menghapus soal, maupun mereset ke soal bawaan Kurikulum Merdeka secara real-time.
- **Ekspor Laporan CSV**: Mengunduh rekapitulasi nilai dan progres belajar seluruh siswa dalam format `.csv`.

### 6. 🏆 Sertifikat Kelulusan Digital
- Otomatis diterbitkan saat siswa menuntaskan seluruh $7$ pos dari Sabang sampai Merauke, lengkap dengan **Nama Lengkap Siswa**, **Jenjang Kelas**, **Total Bintang Emas**, dan tombol **Cetak / Simpan PDF**.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & Vanilla JavaScript (ES Modules)** — Arsitektur *single-file* ringan tanpa memerlukan proses *build* rumit.
- **Tailwind CSS (CDN)** — Antarmuka responsif ramah anak dan mendukung mode cetak (`@media print`) untuk sertifikat.
- **Tone.js** — Sintesis efek suara interaktif (*click, correct, wrong, victory*) dan musik latar pentatonis.
- **Web Speech API (`speechSynthesis`)** — Narator suara Bahasa Indonesia otomatis.
- **Firebase Authentication & Cloud Firestore** — Sinkronisasi data progres siswa, log aktivitas, dan bank soal kustom secara *real-time* lintas perangkat.

---

## 🚀 Cara Menjalankan & Deploy

### A. Menjalankan Secara Lokal
1. Unduh atau simpan file utama aplikasi sebagai **`index.html`** (atau `nusantara_math_adventure.html`).
2. Buka file tersebut menggunakan browser modern (Google Chrome, Microsoft Edge, Safari, atau Firefox).
3. *(Opsional)* Untuk mengaktifkan sinkronisasi cloud lintas perangkat secara permanen di server Anda sendiri, masukkan objek konfigurasi proyek **Firebase** Anda ke variabel `__firebase_config` pada bagian `<script type="module">`.

### B. Publikasi ke Web / Google Sites (Netlify Drop)
1. Masukkan file **`index.html`** ke dalam satu folder (misalnya `nusantara-math`).
2. Buka **[app.netlify.com/drop](https://app.netlify.com/drop)** dan seret (*drag & drop*) folder tersebut untuk mendapatkan tautan HTTPS publik.
3. Untuk memasangnya di **Google Sites**: buka menu **Sisipkan (Insert) ➔ Sematkan (Embed) ➔ Dengan URL**, tempel tautan Netlify Anda, pilih tampilan **Seluruh halaman**, lalu klik **Publikasikan**.

---

## 🔐 Kredensial Akses Admin (Default)

| Kolom | Nilai Default |
| :--- | :--- |
| **Username** | `admin` (atau `guru`) |
| **PIN / Kata Sandi** | `1234` (atau `guru123`) |

> **Catatan Keamanan:** Sebelum mempublikasikan aplikasi untuk lingkungan sekolah yang luas, disarankan untuk mengubah kredensial login admin di dalam fungsi `handleAdminLogin()` pada kode sumber.

---

## 📄 Lisensi & Penggunaan
Aplikasi ini dikembangkan untuk mendukung pembelajaran matematika yang menyenangkan dan berwawasan kebhinekaan di sekolah maupun di rumah. Silakan digunakan dan disesuaikan untuk kebutuhan pendidikan.