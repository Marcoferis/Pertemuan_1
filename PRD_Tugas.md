# **Modul Mandiri — Pertemuan 1**

**Mata Kuliah:** Natural Language Processing (NLP)

**Topik:** Pengantar NLP & Aplikasi

**Mode:** Belajar mandiri (tanpa pendampingan dosen)

**Estimasi waktu:** ±120 menit

1) # **Tujuan Pembelajaran Spesifik**

Setelah menyelesaikan modul ini, mahasiswa mampu: 1\. Menjelaskan apa itu NLP, ruang lingkup, dan contoh aplikasinya di industri.

2. Mengidentifikasi komponen umum alur kerja NLP (data → pra‑proses → representasi → model →

evaluasi).

3. Menyiapkan lingkungan kerja Python untuk praktikum NLP ( Jupyter \+ pustaka dasar).

4. Membuat *notebook* sederhana yang memverifikasi instalasi dan melakukan uji coba mini.

**Indikator Ketercapaian**

* **Konsep:** Mahasiswa dapat menyebutkan ≥5 aplikasi NLP dan menjelaskan alur kerja NLP dalam 1 diagram/daftar berurutan.

  * **Keterampilan teknis:** Lingkungan Python aktif dengan Jupyter; pustaka	,	,

,

,

terpasang; *notebook* validasi berjalan tanpa error.

* **Produk:** Ringkasan 1 halaman \+ *screenshots* instalasi \+ *notebook* "00\_setup.ipynb".

2) # **Prasyarat & Perlengkapan**

* **Pengetahuan:** Dasar pemrograman Python (variabel, fungsi, pip).

* **Perangkat:** Laptop/PC (RAM minimal 8 GB disarankan).

* ## **Perangkat lunak:**

* **Opsi A (disarankan):** Python ≥3.10 dan Jupyter Notebook (via	)

* **Opsi B:** Miniconda/Anaconda (untuk manajemen lingkungan)

* **Koneksi internet:** Untuk mengunduh paket dan model awal.

3) # **Peta Materi Pertemuan 1 (Alur 120 Menit)**

1. **Pembuka & Motivasi (10’):** Mengapa NLP relevan untuk proyek dan karier.

2. **Konsep Dasar NLP (25’):** Definisi, ruang lingkup, contoh aplikasi lintas industri.

3. **Alur Kerja & Ekosistem (15’):** Data → pra‑proses → representasi → model → evaluasi; peran NLTK, spaCy, scikit‑learn, HF.  
4. **Setup Lingkungan (40’):** Instalasi Python/Jupyter & pustaka; unduh data/model dasar.

5. **Uji Coba Mini (20’):** Notebook validasi \+ demo singkat tokenisasi (teaser untuk pertemuan 2).

6. **Rangkuman & Penugasan (10’):** Output yang harus dikumpulkan \+ rubrik penilaian.

4) # **Materi Inti**

   1. **Apa itu NLP?**

NLP adalah bidang ilmu yang memampukan komputer memahami, mengolah, dan menghasilkan bahasa manusia. Contoh tugas: klasifikasi teks (sentimen/berita), ekstraksi entitas, penjawab pertanyaan, peringkasan otomatis, terjemahan, *chatbot*, dan lain‑lain.

2. **Aplikasi Industri (contoh cepat)**

   * **Layanan pelanggan:** *Chatbot* & *virtual assistant*.

     * **E‑commerce:** Klasifikasi ulasan, rekomendasi berbasis teks.

     * **Kesehatan:** Ekstraksi informasi dari catatan medis.

     * **Keuangan:** Analisis dokumen, deteksi penipuan berbasis teks.

     * **Media:** Moderasi konten, peringkasan berita.

   3. **Alur Kerja Umum NLP**

1) ## **Data & tujuan**

2) **Pra‑proses** (tokenisasi, stopwords, normalisasi, dll.)

3) **Representasi** (BoW/TF‑IDF/embeddings)

4) **Pemodelan** (Naive Bayes, SVM, RNN/LSTM, Transformer)

5) **Evaluasi** (akurasi, F1, ROUGE, dsb.)

6) **Deployment/Integrasi** (opsional; prasyarat proyek akhir)

5) # **Langkah Praktikum Mandiri (Step‑by‑Step)**

   Pilih **Opsi A (pip)** atau **Opsi B (conda)**. Jalankan di **Terminal/Command Prompt**.

   1. **Opsi A — Python \+ pip**

2. **Opsi B — (Mini)conda**

   3. **Uji Coba Mini di Jupyter**

Buat file *notebook* bernama

dan jalankan sel berikut:

**Target:** *Notebook* berjalan tanpa error, menampilkan versi paket, dan keluaran tokenisasi.

4. **(Opsional) Simpan Daftar Paket**

6) # **Penugasan Mandiri (Wajib Dikumpulkan)**

**Tugas A — Ringkasan 1 Halaman**

Tuliskan ringkasan (maks. 1 halaman, PDF) berjudul: **“Lanskap & Aplikasi NLP yang Relevan bagi Saya”**. Isi minimal: \- 3–5 aplikasi NLP yang menarik untuk Anda (jelaskan *use case* dan manfaatnya).

- Satu diagram/daftar pendek **alur kerja NLP** versi Anda sendiri.

- Satu ide mini proyek yang mungkin dikerjakan di akhir semester.

**Tugas B — Notebook Validasi**

Unggah *notebook*

- Versi Python dan paket kunci.

- Hasil tokenisasi (NLTK dan spaCy ID).

yang menampilkan:

- (Opsional) Cuplikan *plot* sederhana menggunakan	untuk memastikan integrasi berjalan.

**Tugas C — Bukti Instalasi**

3–5 *screenshot* yang menunjukkan:

1) Aktivasi *virtual environment* atau	,

2) Keberhasilan **pip install** ,

3) Hasil  **python \-m spacy download …** ,

4) Tampilan Jupyter,

5) Keluaran sel tokenisasi di *notebook*.

## **Format penyerahan (1 arsip	):**

**Penamaan di LMS:**

**Batas pengumpulan:** Mengikuti jadwal perkuliahan.

7) # **Rubrik Penilaian**

Komponen	Bobot	Sangat Baik (A)	Baik (B)	Cukup (C)	Perlu Perbaikan  
(D)

|  |  | Semua paket | Terpasang; |  |  |
| :---- | ----- | :---- | :---- | :---- | :---- |
|  |  | terpasang; | ada | Ada error kecil; | Instalasi gagal/ |
| **Lingkungan &** | 40% | notebook | peringatan | masih dapat | tidak dapat |
| **Notebook** |  | berjalan tanpa | minor tetapi | menunjukkan | menjalankan |
|  |  | error; demo | fungsi utama | output sebagian | notebook |
|  |  | tokenisasi jelas | berjalan |  |  |
|  |  | Aplikasi ≥5, |  |  |  |
| **Ringkasan 1** |  | akurat, relevan; | Aplikasi 3–4; | Aplikasi \<3; alur | Ringkasan |
| **Halaman** | 40% | alur kerja jelas; | alur kerja | kerja kurang | dangkal/kurang |
|  |  | ide mini proyek | cukup jelas | runtut | sesuai |
|  |  | realistis |  |  |  |
|  |  | 5 gambar |  |  |  |
| **Bukti Instalasi** |  20% | lengkap, berurutan, | 3–4 gambar, cukup | 1–2 gambar, | Tidak ada/ tidak |
| **(Screenshots)** |  |  |  | kurang bukti | relevan |
|  |  | mudah | informatif |  |  |
|  |  | diverifikasi |  |  |  |

**Kriteria Lulus pertemuan:** Nilai total ≥ 60/100 **dan** notebook dapat dieksekusi.

8) # **Refleksi & Diskusi (Isian Mahasiswa)**

* Apa insight terpenting yang Anda pelajari hari ini tentang NLP?

* Bagian mana yang masih membingungkan (tuliskan 2–3 pertanyaan)?

* Aplikasi NLP apa yang paling relevan untuk bidang minat Anda? Mengapa?

## **Kegiatan forum (opsional/diwajibkan sesuai dosen):**

- Posting 1 contoh aplikasi NLP nyata yang Anda temukan (sertakan tautan/sumber),

- Balas minimal 1 posting teman dengan masukan konstruktif.

9) # **Troubleshooting Cepat**

* **:** Pastikan *environment* aktif ( **.venv** / **conda activate** ).

* **Unduh model spaCy gagal:** Cek koneksi; coba ulang; jalankan **python \-m spacy validate** .

* **Jupyter tidak muncul:** Jalankan **jupyter notebook** di folder proyek dan periksa *firewall*/port.

* **Bahasa Indonesia tidak ter‐tokenisasi baik:** Pastikan **id\_core\_news\_sm** terpasang; atau gunakan NLTK \+ kamus kustom pada pertemuan 2\.

10) # **Etika & Privasi Data**

* Gunakan data yang legal dan menghormati privasi; *anonymize* bila perlu.

* Jangan mengunggah data sensitif ke repositori publik.

* Cantumkan sumber ketika memakai dataset/model pihak ketiga.

11) # **Glosarium Ringkas**

* **Tokenisasi:** Memecah teks menjadi unit (kalimat/kata).

* **Stopwords:** Kata umum yang sering dihapus saat pra‑proses (mis. “yang”, “dan”).

* **Representasi teks:** Cara mengubah teks menjadi vektor numerik (BoW, TF‑IDF, embedding).

* **Pipeline:** Rangkaian langkah otomatis dari input hingga keluaran model.

* **Notebook Jupyter:** Berkas interaktif untuk kode, teks, dan visualisasi.

12) # **Checklist Akhir (Centang sebelum unggah)**

* \[ \] Python & Jupyter terpasang dan berjalan.

* \[ \] Paket inti NLP terinstal ( **nltk** ,

,

,

,	).

* \[ \] Model **id\_core\_news\_sm** spaCy terunduh.

* \[ \] **00\_setup.ipynb** menampilkan versi paket \+ hasil tokenisasi.

* \[ \] **ringkasan\_p1.pdf** selesai (≤1 halaman, jelas, relevan).

* \[ \] Folder **screenshots/** berisi bukti instalasi.

* \[ \] Semua berkas dikompresi menjadi	.

13) # **Referensi Awal (untuk bacaan mandiri)**

* Jurafsky, D., & Martin, J. H. *Speech and Language Processing* (edisi terbaru tersedia daring).

* Bird, S., Klein, E., & Loper, E. *Natural Language Processing with Python* (NLTK Book).

* Dokumentasi spaCy & scikit‑learn.

* Artikel/studi kasus aplikasi NLP di industri.

**Lampiran A — Template Struktur Folder Proyek**

**Lampiran B — Contoh README.md Singkat**

