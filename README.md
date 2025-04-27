# Face_Detection_and_Recognition

Proyek ini melakukan deteksi wajah dari gambar menggunakan metode `Haar Cascade` dari OpenCV.  
Gambar input akan diproses dalam bentuk grayscale, lalu dilakukan pencarian wajah berdasarkan model cascade classifier.

## Fitur
- Deteksi wajah pada gambar.
- Resize gambar ke ukuran konsisten (250x250).
- Parameter deteksi dapat dikustomisasi (scale factor, min neighbors, minimum size).

## Cara Penggunaan

1. **Persiapan Library**
   - Pastikan Python dan library berikut sudah terinstal:
     - `opencv-python`
     - `numpy`
     - `matplotlib` (opsional untuk visualisasi)

2. **Jalankan Notebook**
   - Buka `Face_Detection_Recognition.ipynb`
   - Jalankan sel satu per satu.

3. **Deteksi Wajah**
   - Panggil fungsi `detect_faces(image_gray)` untuk mendeteksi wajah dari gambar grayscale.
