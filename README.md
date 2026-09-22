# Legenda Nusantara

Website "Nusantara Wiki" berisi kumpulan legenda & mitologi daerah di Indonesia,
dibuat oleh **Kelompok 14 — D3 Teknik Informatika A, PENS**, semester 1.
Sejauh ini region yang sudah punya halaman lengkap: **Jawa**.

## Cara membuka
Situs ini statis (HTML/CSS/JS biasa, tanpa server/database), jadi tinggal:

1. Ekstrak ZIP.
2. Buka `index.html` langsung di browser, **atau** jalankan local server dari
   folder ini (disarankan, biar semua path/link jalan normal), contoh:
   ```bash
   npx serve .
   # atau
   python3 -m http.server 8000
   ```
3. Buka `http://localhost:8000` (kalau pakai server).

## Struktur folder
```
legenda-nusantara/
├── index.html                     # Beranda
├── kontak.html                    # Halaman Tim Kami
├── login.html                     # Sign in
├── register.html                  # Register
├── assets/
│   ├── css/                        # bootstrap.css, login.css, jawa.css, artikel.css
│   ├── js/                          # bootstrap.js
│   └── img/                         # semua gambar, dikelompokkan per bagian
│       ├── shared/                   # header, ikon sosial (dipakai banyak halaman)
│       ├── home/                      # gambar beranda + daerah/ (kartu tiap pulau)
│       ├── kontak/                   # foto anggota tim
│       └── jawa/                      # semua gambar khusus region Jawa
└── jawa/
    ├── index.html                    # Halaman "pintu" region Jawa (kartu-kartu legenda)
    ├── artikel.html                   # Artikel legenda (saat ini: Kebo Emas & Bapa Tuo)
    ├── prambanan.html                 # Fragmen detail Candi Prambanan (dimuat via iframe)
    ├── borobudur.html                  # Fragmen detail Candi Borobudur (dimuat via iframe)
    └── tangkuban-perahu.html            # Fragmen detail Tangkuban Perahu (dimuat via iframe)
```

## Status konten
- ✅ Region **Jawa**: halaman pintu, kartu-kartu legenda, dan 1 artikel lengkap (Kebomas) sudah jadi.
- 🚧 Region **Sumatera, Kalimantan, Sulawesi, Papua**: baru ada kartu di beranda,
  halamannya belum dibuat (sementara diarahkan ke halaman Jawa).
- 🚧 Kartu legenda selain Kebomas (Barongan, Nyi Roro Kidul, Joko Tole, Punakawan,
  Kyai Tunggul Wulung) belum punya artikel sendiri.
- 🚧 Form login, register, dan kolom komentar baru tampilan (belum terhubung ke backend/database).

## Tim
Kelompok 14 — Mas Falich Ahmad, Muhammad Fahrizal Ramadhan, Ibnu Royhan Firdausy.
