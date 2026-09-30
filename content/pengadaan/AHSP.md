---
title: AHSP
tags:
  - 🌿tumbuh
  - pengadaan
  - teknik-sipil
aliases:
  - Analisa Harga Satuan Pekerjaan
---

**AHSP** alias Analisa Harga Satuan Pekerjaan. Intinya: satu item kerjaan dibongkar jadi komponen tenaga, bahan, sama alat.

Pegangan gw: Permen PUPR No. 8 Tahun 2023 soal pedoman nyusun perkiraan biaya pekerjaan konstruksi.

## Rumus dasarnya

```
Harga satuan = Σ (koefisien × harga dasar)   buat tenaga + bahan + alat
             + overhead & profit (%)
```

- **Koefisien** ambil dari tabel AHSP. Contoh: berapa OH pekerja buat 1 m³ beton.
- **Harga dasar** dari standar harga daerah atau survei pasar.
- **Overhead & profit** ikutin ketentuan di dokumen pemilihan.

## Cara gw ngerjainnya di Excel

- Pisahin jadi tiga sheet: harga dasar, AHSP, sama [[BOQ vs RAB vs HPS|DKH]].
- Semua angka di sheet AHSP **ngerujuk** ke sheet harga dasar. Nggak ada angka yang gw ketik ulang, biar kalau harga berubah semuanya ikut.
- Kalau totalnya harus masuk di bawah HPS, yang gw utak-atik harga dasar atau profit. **Koefisien jangan disentuh.**

Nyambung ke: [[Beton Mutu dan Campuran]]
