# RoastVision AI ☕
Sistem Cerdas Berbasis Citra Vision untuk Klasifikasi Tingkat Roasting Biji Kopi

## Deskripsi
Project PBL ini menggabungkan Sistem Cerdas, Sistem Tertanam, dan Citra Vision untuk
mendeteksi tingkat roasting kopi (Light, Medium, Dark) secara real-time menggunakan AI.

## Struktur Folder
- dataset/: berisi gambar kopi roasted (mentah & hasil resize)
- models/: hasil training model CNN
- scripts/: kode Python untuk training, evaluasi, dan inferensi
- embedded/: kode untuk Raspberry Pi / ESP32-CAM
- docs/: laporan, diagram, hasil pengujian

## Cara Jalankan
1. Jalankan `scripts/train_model.py` untuk melatih model
2. Jalankan `scripts/realtime_predict.py` untuk uji realtime
3. Upload model ke Raspberry Pi / ESP32 untuk implementasi embedded

## Library
TensorFlow, Keras, OpenCV, NumPy, Pillow, Flask (opsional)
