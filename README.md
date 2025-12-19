# UAS-Deep-Learning

Disusun Oleh :
1. Daffa Fadhil Apriza    (G1A022067)
2. Rino Alfaridzi Hutomo  (G1A022085)

Dosen Pengampu : 
1. Ernawati, S.T., M.Cs
2. Ir. Arie Vatresia, S.T., M.TI., Ph.D., IPP.

Soal UAS :
Tema:“Pengembangan Sistem Deteksi Anomali pada Data Sensor IoT menggunakan Arsitektur Hybrid CNN‑LSTM”

Tujuan:
Mahasiswa mampu merancang, mengimplementasikan, dan mengevaluasi model deep learning yang memadukan jaringan konvolusi (CNN) dan recurrent (LSTM) untuk menyelesaikan masalah nyata, serta mendokumentasikan proses secara ilmiah.

Deskripsi Tugas:
1. Identifikasi Masalah & Dataset
    - Pilih satu jenis data sensor IoT (mis. suhu, kelembaban, atau accelerometer).
    - Kumpulkan atau gunakan dataset publik yang berisi label anomali.

2. Pra‑pemrosesan & Eksplorasi Data
    - Lakukan pembersihan, normalisasi, dan segmentasi data menjadi window temporal.
    - Visualisasikan distribusi kelas dan pola anomali.

3. Perancangan Arsitektur Model
    - Bangun model hybrid: CNN mengekstrak fitur spasial dari tiap window, diikuti LSTM untuk memodelkan ketergantungan waktu.
    - Eksperimen dengan variasi (jumlah layer, kernel size, unit LSTM, dropout).

4. Implementasi
    - Kode dalam Python menggunakan TensorFlow/Keras atau PyTorch.
    - Gunakan callback (early stopping, model checkpoint) dan teknik regulasi.

5. Pelatihan & Evaluasi
    - Bagi data menjadi train/validation/test (mis. 70/15/15).
    - Hitung metrik: accuracy, precision, recall, F1‑score, ROC‑AUC.
    - Bandingkan dengan baseline (mis. SVM, autoencoder).

6. Optimasi & Deployment
    - Lakukan hyperparameter tuning (grid/random search atau Bayesian).
    - Eksport model ke format ONNX atau TensorFlow Lite untuk edge device.

7. Laporan & Presentasi
    - Tulis laporan ≤ 15 halaman (abstrak, latar belakang, metodologi, hasil, kesimpulan, referensi).
    - Siapkan slide 10 menit dan demo singkat (jalankan model pada contoh data).

Kriteria Penilaian:
- Kreatifitas – inovasi arsitektur dan pendekatan solusi.
- Kualitas Implementasi – kebersihan kode, penggunaan teknik DL yang tepat.
- Analisis & Evaluasi – interpretasi hasil, perbandingan dengan baseline.
- Dokumentasi – laporan ilmiah terstruktur, referensi tepat.

Dateline: 19 Desember 2025 jam 23:59

Kerjakan secara individu atau berpasangan (maks 3 orang). Pastikan semua kode dan data tersedia di repositori Git yang dapat diakses dosen.
Kompti mengirimkan link github untuk setiap project yang dikerjakan
--
_____________________________________________

Arie Vatresia
​Lecture in Informatics Engineering, Faculty of Engineering
Gedung Fakultas Teknik, Jl. W.R Supratman Kandang Limun Bengkulu 38371
Sumatera - INDONESIA
Tel : +62 736 21170 and 21884
Email: arie.vatresia@unib.ac.id
Webpage: http://vatresia.staff.unib.ac.id/
