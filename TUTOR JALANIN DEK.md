# ?? Panduan Lengkap Menjalankan Website AURA-VISION
### (Panduan Mudah untuk Pemula & Non-IT)

Selamat datang! Dokumen ini dibuat khusus untuk membantu siapa saja—termasuk Anda yang tidak memiliki latar belakang IT—agar dapat menjalankan dan mencoba seluruh fitur interaktif website **AURA-VISION** di komputer sendiri.

---

## ?? Ringkasan 3 Langkah Mudah

1. **Unduh & Install Node.js** (Hanya dilakukan 1 kali di awal).
2. **Buka Folder Projek & Ketik `npm install`** (Mengunduh bahan aplikasi).
3. **Ketik `npm run dev`** (Menjalankan website di browser).

---

## ??? LANGKAH 1: Mengunduh & Memasang Software Node.js

Aplikasi web modern membutuhkan sebuah program gratis bernama **Node.js** agar dapat berjalan di komputer Anda.

1. Buka browser Anda (Google Chrome / Microsoft Edge) dan buka situs web resmi berikut:
   ?? **[https://nodejs.org/](https://nodejs.org/)**
2. Klik tombol hijau bertuliskan **"LTS"** (Long Term Support / Versi Paling Stabil).
3. Setelah file selesai diunduh, buka file installer tersebut (misalnya `node-v20.x.x-x64.msi`).
4. Klik tombol **Next** -> centang persetujuan -> klik **Next** terus sampai selesai -> lalu klik **Finish**.
5. **Cara Mengecek Apakah Sudah Terpasang:**
   - Buka aplikasi **Command Prompt** (Cari "cmd" di pencarian Windows).
   - Ketik perintah: `node -v` lalu tekan Enter.
   - Jika muncul angka versi (misalnya `v20.11.0`), artinya Node.js berhasil terpasang! ??

---

## ?? LANGKAH 2: Membuka Folder Projek AURA-VISION

1. Buka folder projek **`AURA-VISION_Website`** melalui File Explorer Windows Anda.
2. **Cara Tercepat Membuka Terminal di Folder Tersebut:**
   - Klik pada bilah alamat folder di bagian atas File Explorer (tempat tulisan lokasi folder).
   - Ketik `cmd` lalu tekan **Enter**.
   - Jendela Command Prompt hitam/putih akan otomatis terbuka tepat di dalam folder projek tersebut.

---

## ?? LANGKAH 3: Mengunduh Bahan & Library Aplikasi (`npm install`)

Sebelum aplikasi dijalankan pertama kali, komputer perlu menyiapkan library pustaka pendukung.

1. Pada jendela Command Prompt yang sudah terbuka, ketik perintah berikut:
   ```bash
   npm install
   ```
2. Tekan **Enter** dan tunggu beberapa detik (pastikan komputer terhubung ke internet).
3. Setelah selesai, akan muncul pesan seperti `added ... packages`. Langkah ini cukup dilakukan sekali saja saat pertama kali menyiapkan projek.

---

## ?? LANGKAH 4: Menjalankan Website di Browser (`npm run dev`)

1. Ketik perintah berikut di Command Prompt:
   ```bash
   npm run dev
   ```
2. Tekan **Enter**.
3. Dalam hitungan detik, akan muncul tulisan seperti ini:
   ```text
     VITE v6.4.4  ready in 450 ms

     ?  Local:   http://localhost:5173/
   ```
4. Buka browser Google Chrome atau Microsoft Edge Anda.
5. Ketik alamat berikut di bagian atas browser:
   ?? **`http://localhost:5173`**
6. Tekan **Enter**, dan selamat! Website **AURA-VISION** kini sudah tampil dan aktif di layar komputer Anda! ??

---

## ?? LANGKAH 5: Panduan Uji Coba & Menggunakan Fitur Aplikasi

Anda dapat menjelajahi seluruh alur penggunaan aplikasi seperti pengelola dapur sungguhan:

### 1. Menjelajahi Landing Page Publik
- Buka alamat `http://localhost:5173`.
- Scroll ke bawah untuk melihat penjelasan produk, 3 Langkah Kerja, Perangkat Hardware, serta **Profil 5 Anggota Tim** (Darryl, Jinggan, Satryo, Angel, Faiq).
- Coba klik menu navigasi di bagian atas (*Cara Kerja, Fitur, Dampak, Tim, Kontak*). Navigasi akan bergeser mulus dan berhenti pas tepat di bawah header.

### 2. Masuk ke Mode Aplikasi Demo (Dashboard)
- Klik tombol hijau **"Coba Demo"** di bagian atas kanan header, atau klik **"Masuk"**.
- Pada halaman Login, klik tombol **"Gunakan Akun Demo"**.
- Anda akan otomatis masuk ke **Dashboard Operasional (`/app`)**.

### 3. Mencoba Pemindaian Kamera & Simulasi AI
- Pada menu sebelah kiri, pilih **"Kamera & Deteksi"**.
- Anda dapat memilih 2 cara pengujian:
  - **Cara A (Menggunakan Webcam HP/Laptop):** Klik tombol **"Aktifkan Kamera Browser"**, izinkan akses kamera pada pesan browser. Klik **"Ambil Gambar & Simulasikan"**.
  - **Cara B (Tanpa Kamera):** Klik tombol **"Gunakan Contoh Tanpa Kamera"**.
- Geser slider penimbangan gramasi limbah (misalnya `850 g`).
- Klik tombol **"Simpan Catatan Demo ke Dashboard"**.
- Catatan baru tersebut akan otomatis memperbarui nilai total berat, estimasi kerugian Rupiah, dan jejak karbon CO2e di seluruh aplikasi!

### 4. Melihat Riwayat & Analitik Grafik
- Buka menu **"Riwayat Limbah"** untuk mencari, menyaring kategori, atau melihat detail catatan yang baru saja disimpan.
- Buka menu **"Analitik & Grafik"** untuk melihat grafik pembuangan harian dan distribusi pie chart.

### 5. Mengubah Pengaturan HPP & Faktor Emisi
- Buka menu **"Pengaturan HPP"**.
- Anda dapat mengubah harga HPP per kilogram untuk tiap bahan (misalnya Protein dari Rp 65.000 menjadi Rp 70.000).
- Klik **"Simpan Konfigurasi Baru"**.

---

## ?? LANGKAH 6: Cara Menghentikan Aplikasi

Jika Anda sudah selesai mencoba dan ingin mematikan aplikasi server lokal:

1. Kembali ke jendela Command Prompt.
2. Tekan tombol **`Ctrl` + `C`** bersamaan di keyboard.
3. Jika muncul pertanyaan `Terminate batch job (Y/N)?`, ketik `Y` lalu tekan **Enter**.
4. Jendela Command Prompt dapat ditutup.

---

## ? Tanya Jawab & Solusi Masalah Sering Terjadi (FAQ)

#### Q: Perintah `node -v` dikatakan "is not recognized as an internal command"?
> **Solusi:** Node.js belum terpasang sempurna atau jalur sistem belum diperbarui. Ulangi instalasi Node.js pada Langkah 1 dan pastikan mencentang opsi *"Add to PATH"*, kemudian tutup dan buka kembali jendela Command Prompt.

#### Q: Kamera tidak muncul saat menekan "Aktifkan Kamera Browser"?
> **Solusi:** Pastikan Anda mengizinkan (*Allow*) saat browser meminta izin webcam. Jika tidak memiliki webcam, klik tombol alternatif **"Gunakan Contoh Tanpa Kamera"**.

#### Q: Data yang saya simpan apakah hilang saat komputer dimatikan?
> **Solusi:** Seluruh data demo tersimpan secara otomatis di penyimpanan browser (*localStorage*) komputer Anda. Jika ingin mengembalikan ke data awal, buka menu **Pengaturan HPP** -> klik **"Reset Data Demo ke Bawaan"**.

---

*Dokumen panduan ini disusun resmi untuk kemudahan pengujian dan evaluasi projek AURA-VISION.*
