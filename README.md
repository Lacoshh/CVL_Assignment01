# Peningkatan Kualitas Citra Minim Cahaya (Low-Light Image Enhancement) menggunakan Zero-DCE

Repository ini berisi implementasi proyek untuk meningkatkan kualitas gambar yang diambil dalam kondisi minim cahaya (low-light). Program ini menggunakan model Zero-DCE (Zero-Reference Deep Curve Estimation) untuk mencerahkan gambar secara efektif tanpa memerlukan gambar referensi yang terang, sehingga sangat fleksibel untuk berbagai kasus penggunaan.

# Teknologi yang Digunakan
Python 3.8+

PyTorch: Sebagai framework utama deep learning untuk membangun dan menjalankan model.

OpenCV: Digunakan untuk pemrosesan gambar dasar.

NumPy: Untuk manipulasi data numerik dan array.

Pillow (PIL): Untuk membuka dan menyimpan berbagai format gambar.

# Requirement

1. Python 3.7
2. Pytorch 1.0.0
3. opencv
4. torchvision 0.2.1
5. cuda 10.0

# Dataset
input: Zero-DCE_code/data/test_data/DICM

result: Zero-CDE/Zero-DCE_code/data/result/DICM

# Sumber Asli
Proyek ini didasarkan pada implementasi dan model dari repository asli Zero-DCE.

Repository GitHub: https://github.com/Li-Chongyi/Zero-DCE

Paper Referensi: Learning to Enhance Low-Light Image via Zero-Reference Deep Curve Estimation
