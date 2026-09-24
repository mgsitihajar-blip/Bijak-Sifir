# 🎉 Bijak Sifir!

Aplikasi web interaktif untuk kanak-kanak (umur 7–12 tahun) belajar dan
menghafal sifir (jadual perkalian 2 hingga 12). Dibina sepenuhnya dengan
HTML, CSS dan JavaScript vanila — tiada backend atau dependency diperlukan.

## ✨ Ciri-ciri

- **Skrin Permulaan** — masukkan nama, pilih satu atau lebih sifir (2–12),
  dan tetapkan masa hafalan (1, 2 atau 3 minit).
- **Fasa Hafalan** — papar jadual sifir penuh dengan countdown timer, dan
  butang "Sudah Sedia" untuk terus ke soalan.
- **Fasa Soalan** — 20 soalan setiap sesi, campuran 4 jenis:
  - Pilihan berganda
  - Padankan (matching)
  - Isi tempat kosong
- **Sistem Markah & Bintang** — 1 markah setiap soalan betul (maksimum
  20/20), dengan sistem 5 bintang:
  | Soalan Betul | Bintang |
  |---|---|
  | 1–5   | ⭐ |
  | 6–10  | ⭐⭐ |
  | 11–15 | ⭐⭐⭐ |
  | 16–19 | ⭐⭐⭐⭐ |
  | 20    | ⭐⭐⭐⭐⭐ |
- **Animasi & Ganjaran** — konfeti untuk skor sempurna (20/20), maklum
  balas serta-merta bagi setiap jawapan.
- **Rekod Pemain** — sejarah permainan disimpan dalam `localStorage`
  pelayar, boleh disemak bila-bila masa di halaman "Rekod Pemain".
- **Responsive** — sesuai digunakan pada telefon, tablet dan komputer.

## 📂 Struktur Projek

```
bijak-sifir/
├── index.html      # Aplikasi lengkap (HTML + CSS + JS dalam satu fail)
├── package.json    # Skrip untuk jalankan pelayan pembangunan tempatan
├── .gitignore
└── README.md
```

## 🚀 Jalankan Secara Tempatan

Oleh kerana aplikasi ini adalah satu fail HTML "self-contained", ia boleh
dibuka terus dalam pelayar:

```bash
open index.html        # macOS
start index.html        # Windows
```

Atau jalankan pelayan tempatan (disyorkan supaya `localStorage` dan ciri
pelayar lain berfungsi dengan konsisten):

```bash
npm install -g http-server   # jika belum ada
npm start
```

Aplikasi akan terbuka di `http://localhost:8080`.

## 🌐 Deploy ke GitHub Pages

1. Push repo ini ke GitHub.
2. Pergi ke **Settings → Pages**.
3. Pilih branch `main` dan root folder `/ (root)`.
4. Simpan — laman akan tersedia di
   `https://<username>.github.io/bijak-sifir/`.

## 🛠️ Teknologi

- HTML5, CSS3, JavaScript (Vanilla, tiada framework)
- `localStorage` untuk penyimpanan rekod pemain
- Tiada backend / API diperlukan

## 📄 Lesen

MIT
