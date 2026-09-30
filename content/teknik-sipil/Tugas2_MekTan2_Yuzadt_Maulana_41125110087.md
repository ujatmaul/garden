# TUGAS 2 MEKANIKA TANAH 2

## Integrasi Data SPT, CPT, dan Boring Log pada Titik BH-01 dan CPT-01

| | |
|---|---|
| **Nama** | Yuzadt Maulana |
| **NIM** | 41125110087 |
| **Program Studi** | Teknik Sipil, Universitas Mercu Buana |
| **Dosen** | Dr. Ir. Anita Setyowati Srie Gunarti, ST, MT |
| **Semester** | Gasal 2026/2027 |

---

## 1. Perhitungan N60 (SPT)

Nilai N-SPT lapangan dikoreksi terhadap energi hammer, panjang rod, tipe sampler, dan diameter lubang bor sehingga setara dengan efisiensi energi 60%, menggunakan persamaan:

$$N_{60} = C_h \times C_r \times C_s \times C_d \times N_{SPT}$$

Contoh perhitungan pada kedalaman 4 m:

$$N_{60} = 0{,}95 \times 0{,}75 \times 1{,}00 \times 1{,}05 \times 5 = 0{,}7481 \times 5 = 3{,}74 \approx 3$$

Perhitungan yang sama dilakukan untuk seluruh kedalaman dan hasilnya disajikan pada Tabel 1. Pembulatan dilakukan ke bawah (konservatif) mengikuti contoh pada modul.

**Tabel 1. Hasil Perhitungan N60**

| Kedalaman (m) | N-SPT lapangan | Ch | Cr | Cs | Cd | Faktor total | N60 hitung | N60 dibulatkan |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 4 | 5 | 0,95 | 0,75 | 1,00 | 1,05 | 0,7481 | 3,74 | 3 |
| 6 | 7 | 0,95 | 0,85 | 1,00 | 1,05 | 0,8479 | 5,94 | 5 |
| 8 | 12 | 0,95 | 0,95 | 1,00 | 1,05 | 0,9476 | 11,37 | 11 |
| 10 | 18 | 0,95 | 0,95 | 1,00 | 1,05 | 0,9476 | 17,06 | 17 |
| 12 | 26 | 0,95 | 1,00 | 1,00 | 1,05 | 0,9975 | 25,93 | 25 |
| 14 | 34 | 0,95 | 1,00 | 1,00 | 1,05 | 0,9975 | 33,91 | 33 |
| 16 | 43 | 0,95 | 1,00 | 1,00 | 1,05 | 0,9975 | 42,89 | 42 |

*Faktor total = Ch × Cr × Cs × Cd. Nilai Cr < 1 pada kedalaman 4–10 m karena batang bor masih pendek sehingga sebagian energi hilang.*

---

## 2. Perhitungan Friction Ratio Rf (CPT)

Friction ratio dihitung dari perbandingan tahanan selimut (fs) dan tahanan konus (qc). Karena fs dalam kPa dan qc dalam MPa, qc dikonversi terlebih dahulu (1 MPa = 1.000 kPa):

$$R_f = \frac{f_s}{q_c \times 1.000} \times 100\%$$

Contoh perhitungan pada kedalaman 4 m:

$$R_f = \frac{45}{1{,}0 \times 1.000} \times 100\% = 4{,}50\%$$

Sebagai pendekatan umum, Rf < 2% mengindikasikan tanah pasir, Rf 2–4% tanah campuran (pasir berlanau/lanau berpasir), dan Rf > 4% tanah lempung atau lanau lempungan (Robertson, 1990). Hasil lengkap disajikan pada Tabel 2.

**Tabel 2. Hasil Perhitungan Friction Ratio**

| Kedalaman (m) | qc (MPa) | fs (kPa) | qc (kPa) | Rf (%) | Indikasi jenis tanah dari Rf |
|:---:|:---:|:---:|:---:|:---:|---|
| 4 | 1,0 | 45 | 1.000 | 4,50 | Lempung / lanau lempungan |
| 6 | 1,5 | 60 | 1.500 | 4,00 | Lempung / lanau (transisi) |
| 8 | 3,0 | 75 | 3.000 | 2,50 | Pasir berlanau / campuran |
| 10 | 5,0 | 90 | 5.000 | 1,80 | Pasir |
| 12 | 8,0 | 120 | 8.000 | 1,50 | Pasir |
| 14 | 12,0 | 150 | 12.000 | 1,25 | Pasir bersih |
| 16 | 16,0 | 170 | 16.000 | 1,06 | Pasir bersih |

---

## 3. Integrasi Data SPT, CPT, dan Boring Log

Data ketiga pengujian disatukan pada Tabel 3 dan diplot terhadap kedalaman pada Gambar 1. Rasio qc/N60 ditambahkan sebagai cek silang konsistensi antara SPT dan CPT.

**Tabel 3. Integrasi N60, qc, Rf, dan Boring Log**

| z (m) | Boring log | N60 | qc (MPa) | Rf (%) | qc/N60 (MPa) | Interpretasi terpadu |
|:---:|---|:---:|:---:|:---:|:---:|---|
| 4 | Lempung berlanau, lunak–sedang | 3,74 | 1,0 | 4,50 | 0,27 | Lempung lunak; ketiga data konsisten |
| 6 | Batas lempung → pasir berlanau | 5,94 | 1,5 | 4,00 | 0,25 | Lempung sedang (zona transisi) |
| 8 | Pasir berlanau, lepas–sedang | 11,37 | 3,0 | 2,50 | 0,26 | Pasir berlanau agak lepas–sedang |
| 10 | Batas pasir berlanau → pasir | 17,06 | 5,0 | 1,80 | 0,29 | Pasir sedang |
| 12 | Pasir, sedang–padat | 25,93 | 8,0 | 1,50 | 0,31 | Pasir sedang, mendekati padat |
| 14 | Batas pasir sedang → padat | 33,91 | 12,0 | 1,25 | 0,35 | Pasir padat |
| 16 | Pasir, padat | 42,89 | 16,0 | 1,06 | 0,37 | Pasir padat (paling baik) |

Berdasarkan Tabel 3 dan Gambar 1, hubungan ketiga data dapat diuraikan sebagai berikut:

1. **Kedalaman 2–6 m (lempung berlanau).** N60 rendah (3,74–5,94) dan qc kecil (1,0–1,5 MPa), sedangkan Rf tinggi (4,0–4,5%). Rf tinggi menunjukkan tanah berbutir halus (lempung), sesuai dengan deskripsi boring log. Menurut Terzaghi dan Peck, N60 ≈ 4–6 termasuk konsistensi lunak–sedang, sama dengan kondisi umum pada boring log.
2. **Kedalaman 6–10 m (pasir berlanau).** N60 naik menjadi 11,37–17,06, qc naik menjadi 3,0–5,0 MPa, dan Rf turun ke 2,5–1,8%. Penurunan Rf menandai peralihan dari tanah lempungan ke tanah berpasir. Nilai Rf 2,5% pada 8 m masih di zona campuran, sesuai dengan pasir berlanau. Kepadatannya lepas–sedang, konsisten dengan boring log.
3. **Kedalaman 10–14 m (pasir sedang–padat).** N60 25,93–33,91, qc 8–12 MPa, dan Rf 1,25–1,50% (< 2%) menunjukkan pasir dengan kepadatan meningkat dari sedang menjadi padat.
4. **Kedalaman 14–18 m (pasir padat).** N60 mencapai 42,89 dan qc 16 MPa dengan Rf terendah (1,06%). Ini menunjukkan pasir bersih yang padat, sesuai dengan boring log.

Secara keseluruhan, N60 dan qc meningkat hampir sejajar terhadap kedalaman, sedangkan Rf menurun secara konsisten. Rasio qc/N60 relatif stabil (0,25–0,37 MPa) dan sedikit naik terhadap kedalaman. Hal ini wajar karena butiran tanah makin kasar dan kandungan halusnya makin sedikit (Robertson & Campanella, 1983). Tidak terdapat anomali, misalnya N tinggi dengan qc rendah akibat kerikil, sehingga data SPT, CPT, dan boring log saling mendukung dan dapat dipakai bersama untuk interpretasi.

![Gambar 1. Profil N-SPT/N60, qc, dan Rf terhadap Kedalaman](gambar1_profil_spt_cpt.png)

**Gambar 1.** Profil N-SPT/N60, qc, dan Rf terhadap Kedalaman

---

## 4. Kesimpulan

Lapisan yang relatif kritis atau lemah adalah timbunan lanau berpasir lepas (0–2 m) dan terutama lempung berlanau pada kedalaman 2–6 m. Lapisan lempung ini memiliki N60 3,74–5,94, qc 1,0–1,5 MPa, dan Rf 4,0–4,5%, yang menunjukkan lempung lunak–sedang di bawah muka air tanah (−2,0 m). Lapisan ini memiliki kuat geser dan daya dukung rendah serta kompresibilitas tinggi, sehingga berpotensi menimbulkan penurunan konsolidasi bila dibebani langsung dengan fondasi dangkal. Pasir berlanau pada 6–10 m (N60 11–17, qc 3–5 MPa) juga belum cukup kuat sebagai tumpuan dan, karena lepas–sedang serta jenuh air, perlu dicek terhadap potensi likuifaksi bila lokasi berada di zona gempa.

Lapisan yang relatif baik sebagai pendukung fondasi adalah pasir padat pada kedalaman 14–18 m. Pada lapisan ini N60 ≥ 33,91, qc 12–16 MPa, dan Rf < 1,3%, dan ketiga data tersebut konsisten menunjukkan pasir bersih yang padat. Lapisan 10–14 m (pasir sedang–padat) dapat dimanfaatkan untuk tahanan gesek selimut tiang. Oleh karena itu, fondasi yang disarankan adalah fondasi tiang dengan ujung tertanam di lapisan pasir padat, sekitar kedalaman 14–16 m. Karena penyelidikan hanya sampai 18 m, perlu dipastikan dengan pengeboran lebih dalam bahwa tidak terdapat lapisan lunak di bawah lapisan pendukung tersebut.

---

## Daftar Pustaka

- Badan Standardisasi Nasional. (2008a). *SNI 4153:2008 Cara uji penetrasi lapangan dengan SPT*. Jakarta: BSN.
- Badan Standardisasi Nasional. (2008b). *SNI 2827:2008 Cara uji penetrasi lapangan dengan alat sondir*. Jakarta: BSN.
- Hardiyatmo, H. C. (2012). *Mekanika tanah 2*. Yogyakarta: Gadjah Mada University Press.
- Robertson, P. K., & Campanella, R. G. (1983). Interpretation of cone penetration tests. Part I: Sand. *Canadian Geotechnical Journal, 20*(4), 718–733.
- Robertson, P. K. (1990). Soil classification using the cone penetration test. *Canadian Geotechnical Journal, 27*(1), 151–158.
- Terzaghi, K., & Peck, R. B. (1967). *Soil mechanics in engineering practice* (2nd ed.). New York: John Wiley & Sons.
- Universitas Mercu Buana. (2026). *Modul Mekanika Tanah 2 Pertemuan 2: Uji SPT dan CPT*. Jakarta: Universitas Mercu Buana.
