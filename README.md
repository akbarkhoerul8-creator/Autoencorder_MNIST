# Penerapan Metode Autoencoder untuk Rekonstruksi Citra MNIST

## Deskripsi

Proyek ini merupakan implementasi metode **Autoencoder** menggunakan dataset **MNIST** untuk melakukan proses rekonstruksi citra tulisan tangan. Autoencoder merupakan salah satu metode *Deep Learning* yang digunakan untuk mempelajari representasi data secara tidak terawasi (*unsupervised learning*) dengan cara mengompresi data ke dalam ruang laten (*latent space*) kemudian merekonstruksinya kembali.

Notebook yang disediakan berisi tahapan penelitian mulai dari persiapan data, pembangunan model Autoencoder, proses pelatihan (*training*), hingga evaluasi hasil rekonstruksi citra.

## Tujuan

* Mempelajari konsep dasar Autoencoder.
* Mengimplementasikan Autoencoder pada dataset MNIST.
* Melakukan proses rekonstruksi citra tulisan tangan.
* Mengevaluasi kualitas hasil rekonstruksi berdasarkan nilai *loss* dan visualisasi citra.

## Struktur Proyek

```text
UAS_Autoencoder/
│
├── autoencoder_mnist.ipynb    # Notebook implementasi Autoencoder
├── README.md                  # Dokumentasi proyek
├── data/                      # Folder dataset (tidak disertakan di repository)
└── autoencoder_mnist.pth      # Model hasil pelatihan (opsional)
```

## Dataset

Dataset yang digunakan adalah **MNIST**.

Silakan unduh dataset melalui tautan berikut:

https://drive.google.com/file/d/1I-eu3mfX9B7MvmlgcSa4wihLWdGMOZJw/view?usp=sharing

Setelah diunduh, letakkan file CSV ke dalam folder `data/` sebelum menjalankan notebook.

## Cara Menjalankan

1. Clone repository ini.
2. Unduh dataset melalui tautan di atas.
3. Simpan dataset pada folder `data/`.
4. Install seluruh library yang dibutuhkan.
5. Jalankan file `autoencoder_mnist.ipynb` menggunakan Jupyter Notebook atau Visual Studio Code.

## Teknologi yang Digunakan

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* PyTorch

## Penulis

**Nama:** Khaerul Akbar

**NIM:** 24260034

**Program Studi:** Informatika

**Semester:** 4

## Lisensi

Repository ini dibuat untuk keperluan pembelajaran, penelitian, dan tugas akademik.
