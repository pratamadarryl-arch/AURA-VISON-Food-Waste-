# ?? AURA-VISION — Food Waste Intelligence System

AURA-VISION adalah sistem pelacak sisa makanan berbasis **IoT** dan **Computer Vision** yang dirancang untuk membantu dapur komersial, restoran, kantin, serta rumah tangga mengukur berat limbah makanan, estimasi kerugian HPP (Rupiah), serta estimasi jejak emisi CO2e secara otomatis.

---

## ?? Dokumen Panduan & Persyaratan

Untuk kemudahan pengujian dan evaluasi projek oleh pengguna umum maupun tim teknis, silakan baca dokumen berikut:

- ?? **[PANDUAN_CARA_JALANKAN.md](./PANDUAN_CARA_JALANKAN.md)** — Panduan langkah demi langkah menjalankan projek untuk pemula / Non-IT (Disertai instruksi install Node.js, pengoperasian kamera, dan pengujian fitur demo).
- ?? **[REQUIREMENTS.md](./REQUIREMENTS.md)** — Spesifikasi persyaratan sistem, perangkat keras, dan perangkat lunak pendukung.
- ?? **[01_PRD.md](./01_PRD.md) - [08_ANTI_SLOP.md](./08_ANTI_SLOP.md)** — Spesifikasi teknis & desain blueprint produk AURA-VISION.

---

## ? Ringkasan Cara Menjalankan Projek

1. **Install Node.js** (Versi 18 LTS atau lebih baru) dari [https://nodejs.org/](https://nodejs.org/).
2. **Install Dependencies**:
   ```bash
   npm install
   ```
3. **Jalankan Dev Server**:
   ```bash
   npm run dev
   ```
4. Buka browser di: **`http://localhost:5173`**

---

## ?? Profil Tim Pengembang AURA-VISION

1. **Darryl** — `Web & Dashboard Development`
2. **Jinggan** — `Market Expansion & Financials`
3. **Satryo** — `Market Expansion & Financials`
4. **Angel** — `User Experience & Support`
5. **Faiq** — `User Experience & Support`

---

## ??? Teknologi yang Digunakan

- **Frontend**: React 19, TypeScript, Vite
- **Styling**: Tailwind CSS v4, Lucide React Icons
- **Visualisasi & Grafik**: Recharts
- **Kamera**: WebRTC MediaDevices Browser API
- **State & Storage**: React Context + Versioned LocalStorage Persistence
