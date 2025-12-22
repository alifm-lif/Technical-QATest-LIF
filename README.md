# Technical Test: QA Manual Engineer (Mobile/Web)

## 📌 Pendahuluan
Tes ini dirancang untuk mengevaluasi kemampuan analisis, logika pengujian, dan kualitas dokumentasi Anda. Objek pengujian dalam tes ini adalah fitur **"Tweet/Post Composer"** pada aplikasi Twitter (X).

---

## 🛠 Deskripsi Tugas
Anda diminta untuk melakukan analisis kualitas pada fitur pembuatan konten (Tweet Composer). Tugas ini dibagi menjadi tiga bagian:

### 1. Test Case Creation
Buatlah minimal **10 skenario pengujian (Test Case)** yang mencakup:
* **Positive Test:** Skenario standar di mana fitur berjalan sebagaimana mestinya.
* **Negative Test:** Skenario di mana sistem diberikan input yang tidak valid/salah.
* **UI/UX Test:** Validasi terhadap tampilan, konsistensi ikon, dan kemudahan navigasi.

### 2. Edge Case Analysis
Identifikasi minimal **3 Edge Case** (skenario kondisi ekstrem atau batas). 
*Contoh: Kondisi jaringan tidak stabil, limit karakter unik, atau gangguan sistem secara simultan.*

### 3. Bug Reporting
Buatlah **2 Laporan Bug** berdasarkan temuan Anda (atau simulasi jika tidak menemukan bug nyata). Laporan harus ditulis sedemikian rupa agar Developer dapat melakukan perbaikan tanpa bertanya kembali.

---

## 📝 Format Jawaban (Template)

### A. Test Case Table
| ID | Deskripsi Skenario | Langkah-Langkah | Hasil yang Diharapkan | Tipe (Pos/Neg/UI) |
|:---|:---|:---|:---|:---|
| TC-001 | Kirim tweet teks < 280 karakter | 1. Buka composer<br>2. Input teks "Test"<br>3. Klik 'Post' | Tweet muncul di timeline | Positive |

### B. Bug Report Template
* **ID Bug:** [Contoh: BUG-001]
* **Judul:** [Judul singkat yang menggambarkan masalah]
* **Severity:** [Blocker / Major / Minor / Trivial]
* **Langkah Reproduksi:**
    1. ...
    2. ...
* **Hasil Aktual:** [Apa yang terjadi sekarang?]
* **Hasil Diharapkan:** [Apa yang seharusnya terjadi?]
* **Environment:** [Contoh: iOS 17.2 / Chrome v120]

---

## 🎯 Kriteria Penilaian
1.  **Analisis Logika:** Seberapa jauh Anda memikirkan kemungkinan error yang tidak umum.
2.  **Kualitas Dokumentasi:** Penggunaan bahasa yang teknis, efektif, dan tidak ambigu.
3.  **Ketelitian:** Kemampuan mendeteksi anomali pada elemen visual atau alur fungsi.

---

## 📬 Cara Pengiriman
1. Selesaikan tugas ini dalam format **PDF**, **Markdown (.md)**, atau link **Google Sheets**.
2. Kirimkan file tersebut melalui email ke `[Email Perusahaan]` dengan subjek:
   `QA_Manual_Test_NamaLengkap_Tanggal`