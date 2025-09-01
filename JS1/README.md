Nama : Rafi Abiyyu Airlangga

Kelas : TI-3F

NIM : 2341720115

MK : Pembelajaran Mesin

## Bagian 1

1. Buat _file notebook_ dengan nama **TG1_NIM_NAMA.ipynb**. Contoh: **TG_0028119106_M AFIF HENDRAWAN.ipynb**.

2. Lakukan instalasi library berikut pada notebook,

   ```python
   PyPREP
   Scipy
   wandb
   pyECG
   ```

3. Jelaskan kegunakan masing-masing _library_ tersebut.

   Jawaban:

   - PyPREP

     <u>Digunakan untuk _preprocessing_ sinyal EEG (_Electroencephalogram_). _Library_ ini membantu membersihkan sinyal dari artefak (_noise_ seperti kedipan mata, gerakan otot, atau interferensi listrik) sehingga data lebih siap untuk dianalisis.</u>

   - SciPy

     <u>_Library_ ilmiah di Python yang berisi fungsi-fungsi matematika, statistik, dan pengolahan sinyal. Berguna untuk operasi numerik, optimisasi, _filtering_ sinyal, hingga pemrosesan data biomedis seperti ECG atau EEG.</u>

   - wandb (Weights & Biases)

     <u>Alat untuk eksperimen _machine learning tracking_. Membantu mencatat hasil _training model_, memvisualisasikan metrik (akurasi, _loss_), menyimpan konfigurasi _hyperparameter_, dan mempermudah kolaborasi tim riset.</u>

   - pyECG

     <u>_Library_ untuk analisis sinyal ECG (Electrocardiogram). Biasanya digunakan untuk mendeteksi _R-peaks_, menghitung _heart rate_, atau mengekstraksi fitur sinyal jantung. Walaupun agak lawas (dependensi _sklearn_), masih berguna untuk eksperimen pemrosesan ECG.</u>

## Bagian 2

1. Berikan contoh tentang tidakan melanggar etika dan hukum tentang penggunaan kecerdasan buatan. Sertakan referensi yang digunakan.

   Jawaban:

   - Deepfake tanpa izin → Membuat video palsu orang terkenal untuk tujuan penipuan, pornografi non-konsensual, atau propaganda politik.

   - Plagiarisme akademik → Menggunakan AI untuk menulis tugas, skripsi, atau jurnal tanpa atribusi, lalu mengklaim hasilnya sebagai karya pribadi.

   - AI untuk kejahatan siber → Memanfaatkan AI untuk phishing otomatis, cracking password, atau menyebarkan malware.

2. Berikan contoh tentang dampak energi dan lingkungan terhadap pemanfaatan kecerdasan buatan dan bagaimana cara mengatasinya (Anda dapat memberikan pendapat pribadi). Sertakan referensi yang digunakan.

   Jawaban:

   **Dampak**

   - _Training model_ AI besar (seperti GPT, BERT) membutuhkan energi komputasi sangat besar, menghasilkan jejak karbon yang signifikan.
   - _Data center_ AI mengonsumsi listrik dan air dalam jumlah besar untuk pendinginan, sehingga meningkatkan emisi karbon.

   **Cara mengatasi**

   - Efisiensi model: Menggunakan teknik _model compression_, _knowledge distillation_, dan _transfer learning_ agar tidak perlu melatih dari nol.
   - _Green data center_: Memakai energi terbarukan (matahari, angin) untuk operasional _data center_.
   - _AI for environment_: Menggunakan AI untuk memantau energi, cuaca, atau optimasi sistem listrik agar lebih efisien.