---
title: AHSP
tags:
  - 🌿tumbuh
  - pengadaan
  - teknik-sipil
aliases:
  - Analisa Harga Satuan Pekerjaan
---

**Analisa Harga Satuan Pekerjaan** — pecahan satu item pekerjaan jadi komponen tenaga, bahan, dan alat.

Rujukan utama: Permen PUPR No. 8 Tahun 2023 tentang pedoman penyusunan perkiraan biaya pekerjaan konstruksi.

## Rumus dasarnya

```
Harga satuan = Σ (koefisien × harga dasar)   untuk tenaga + bahan + alat
             + overhead & profit (%)
```

- **Koefisien** diambil dari tabel AHSP (misalnya: berapa OH pekerja per m³ beton).
- **Harga dasar** dari standar harga daerah atau survei pasar.
- **Overhead & profit** mengikuti ketentuan yang berlaku di dokumen pemilihan.

## Cara kerja gw di Excel

- Satu sheet harga dasar, satu sheet AHSP, satu sheet [[BOQ vs RAB vs HPS|DKH]].
- Semua angka di AHSP **merujuk** ke sheet harga dasar — nggak ada angka diketik ulang.
- Kalau total harus masuk target di bawah HPS, yang disesuaikan harga dasar/profit, **bukan** koefisien.

Terkait: [[Beton Mutu dan Campuran]]
