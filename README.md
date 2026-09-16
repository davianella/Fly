# 🪂 Sistem Penilaian Kelayakan Terbang Paralayang

Repository ini berisi implementasi metode Fuzzy Inference dengan Probabilistic Rule Weighting untuk menilai kelayakan terbang paralayang berdasarkan variabel cuaca.

Project ini dikembangkan sebagai bagian dari tugas akhir Program Studi Teknik Informatika di Institut Asia Malang.

---

## 📌 Tentang Project

Penelitian ini membahas penerapan kecerdasan buatan dalam melakukan penilaian kelayakan aktivitas paralayang berdasarkan kondisi cuaca.

Metode yang digunakan adalah Fuzzy Inference yang dikombinasikan dengan Probabilistic Rule Weighting. Pendekatan ini digunakan untuk mengolah variabel cuaca dan mempertimbangkan bobot probabilistik pada aturan fuzzy berdasarkan penilaian pakar.

Hasil pengolahan sistem berupa nilai penilaian kelayakan terbang yang dapat digunakan sebagai pendukung dalam memahami kesesuaian kondisi cuaca untuk aktivitas paralayang.

Perlu diperhatikan bahwa sistem ini merupakan alat bantu pengambilan keputusan dan bukan pengganti penilaian pilot, instruktur, maupun prosedur keselamatan penerbangan.

---

## 🎓 Informasi Penelitian

Judul penelitian:

Fuzzy Inference with Probabilistic Rule Weighting to Assess Paragliding Viability Based on Weather Variables

Bidang penelitian:
- Kecerdasan Buatan
- Logika Fuzzy
- Pengolahan Data
- Sistem Pendukung Keputusan
- Analisis Data Cuaca

Jenis project:
- Tugas Akhir
- Penelitian dan implementasi metode

---

## 🎯 Tujuan Penelitian

Penelitian ini bertujuan untuk:

- Mengolah variabel cuaca yang berkaitan dengan aktivitas paralayang.
- Menerapkan logika fuzzy dalam merepresentasikan kondisi cuaca.
- Mengembangkan pembobotan probabilistik pada aturan fuzzy berdasarkan penilaian pakar.
- Menghasilkan penilaian kelayakan terbang berdasarkan kondisi cuaca.
- Menganalisis pengaruh perubahan kondisi cuaca terhadap hasil penilaian sistem.
- Mengembangkan pendekatan yang dapat mendukung proses pengambilan keputusan terkait waktu yang sesuai untuk melakukan aktivitas paralayang.

---

## 🧠 Metode yang Digunakan

### 1. Pengumpulan Data Cuaca

Data cuaca digunakan sebagai masukan utama dalam sistem penilaian kelayakan terbang.

Variabel yang digunakan disesuaikan dengan kebutuhan penelitian dan keterkaitannya dengan kondisi penerbangan paralayang.

### 2. Fuzzifikasi

Tahap fuzzifikasi digunakan untuk mengubah nilai numerik dari variabel cuaca menjadi nilai keanggotaan fuzzy.

Setiap variabel dikelompokkan ke dalam kategori linguistik sesuai dengan fungsi keanggotaan yang telah ditentukan.

### 3. Pembentukan Aturan Fuzzy

Aturan fuzzy digunakan untuk menggambarkan hubungan antara kondisi cuaca dan tingkat kelayakan terbang.

Aturan disusun berdasarkan pengetahuan serta penilaian pakar yang berkaitan dengan aktivitas paralayang.

### 4. Probabilistic Rule Weighting

Setiap aturan fuzzy diberikan bobot probabilistik berdasarkan hasil penilaian pakar.

Pembobotan ini digunakan untuk merepresentasikan tingkat keyakinan terhadap aturan tertentu dalam proses pengambilan keputusan.

### 5. Inferensi Fuzzy

Tahap inferensi digunakan untuk memproses masukan cuaca berdasarkan aturan fuzzy dan bobot probabilistik yang telah ditentukan.

Hasil dari proses ini digunakan untuk memperoleh keluaran berupa penilaian kelayakan terbang.

### 6. Defuzzifikasi

Tahap defuzzifikasi digunakan untuk mengubah hasil keluaran fuzzy menjadi nilai numerik yang dapat digunakan dalam proses penilaian kelayakan terbang.

---

## 🔄 Alur Sistem

Alur umum pengolahan data dalam penelitian ini adalah sebagai berikut:

Data Cuaca
    ↓
Persiapan dan Pengolahan Data
    ↓
Fuzzifikasi
    ↓
Pembentukan Aturan Fuzzy
    ↓
Pembobotan Probabilistik
    ↓
Inferensi Fuzzy
    ↓
Defuzzifikasi
    ↓
Penilaian Kelayakan Terbang

---

## 📊 Data Penelitian

Data penelitian disimpan dalam berkas DATA.zip.

Data tersebut digunakan untuk mendukung proses pengolahan dan pengujian metode yang diterapkan dalam penelitian.

Tahapan pengolahan data meliputi:

- Persiapan data
- Pembersihan data
- Penyesuaian format data
- Pemilihan variabel penelitian
- Pengolahan data sebagai masukan sistem fuzzy
- Pengujian hasil penilaian sistem

---

## 📁 Struktur Repository

Struktur repository terdiri dari:

Fly/
│
├── DATA.zip
│   └── Data penelitian
│
├── Fuzzy Prob.ipynb
│   └── Notebook implementasi dan analisis metode
│
└── README.md
    └── Dokumentasi project

---

## 🛠️ Teknologi dan Perangkat yang Digunakan

Bahasa pemrograman:
- Python

Pustaka pengolahan dan analisis data:
- Pandas
- NumPy
- Matplotlib

Metode dan pendekatan:
- Logika Fuzzy
- Fuzzy Inference
- Probabilistic Rule Weighting
- Pengolahan Data Cuaca

---

## 🔬 Implementasi Penelitian

Notebook Fuzzy Prob.ipynb digunakan untuk menjalankan implementasi metode dan analisis penelitian.

Beberapa proses yang dilakukan dalam notebook meliputi:

- Pengolahan data penelitian.
- Penerapan fungsi keanggotaan fuzzy.
- Pembentukan dan pengolahan aturan fuzzy.
- Perhitungan bobot probabilistik.
- Penerapan proses inferensi.
- Perhitungan nilai kelayakan terbang.
- Analisis hasil pengolahan data.

---

## 📈 Hasil yang Diharapkan

Melalui penelitian ini, diharapkan dapat diperoleh suatu pendekatan yang mampu:

- Mengolah kondisi cuaca ke dalam bentuk penilaian fuzzy.
- Mempertimbangkan bobot probabilistik pada aturan yang digunakan.
- Menghasilkan nilai penilaian kelayakan terbang.
- Memberikan gambaran mengenai kesesuaian kondisi cuaca untuk aktivitas paralayang.
- Mendukung pengembangan sistem pendukung keputusan berbasis kecerdasan buatan.

---

## 📚 Bidang Keilmuan yang Diterapkan

Project ini menerapkan beberapa konsep dalam bidang Teknik Informatika, di antaranya:

- Kecerdasan Buatan
- Logika Fuzzy
- Penalaran Probabilistik
- Pengolahan Data
- Analisis Data
- Sistem Pendukung Keputusan
- Pemodelan Berbasis Aturan

---

## 🎓 Konteks Akademik

Project ini merupakan bagian dari tugas akhir mahasiswa Program Studi Teknik Informatika.

Penelitian ini menggabungkan penerapan metode kecerdasan buatan dengan permasalahan nyata dalam bidang olahraga paralayang, khususnya penilaian kelayakan terbang berdasarkan variabel cuaca.

---

## 👩‍💻 Pengembang

Nama: Davianda Ersya Putri

Program Studi: Teknik Informatika

Perguruan Tinggi: Institut Asia Malang

Jenis Project: Tugas Akhir

---

## 🔗 Tautan Repository

Repository GitHub:
https://github.com/davianella/Fly

---

## ⚠️ Catatan

Project ini dikembangkan untuk keperluan akademik dan penelitian.

Hasil penilaian yang diperoleh dari sistem tidak dimaksudkan untuk menggantikan keputusan pilot, instruktur, atau prosedur keselamatan penerbangan.

Keputusan penerbangan perlu mempertimbangkan berbagai faktor lain, termasuk kondisi cuaca aktual, kondisi lokasi, kemampuan pilot, dan aspek keselamatan penerbangan.

---

## 📄 Lisensi

Belum menggunakan lisensi khusus.
