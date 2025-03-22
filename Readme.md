# Konversi Warna dan Deteksi Warna Dominan

## Deskripsi Proyek
Proyek ini mengimplementasikan konversi warna antara format RGB, HSV, dan Grayscale serta melakukan analisis untuk mendeteksi warna dominan dalam suatu citra menggunakan metode clustering.

## Struktur Proyek
```
warna-dominan/
│── src/
│   ├── main.py             # File utama untuk menjalankan proyek
│   ├── color_conversion.py # Modul untuk konversi warna (RGB, HSV, Grayscale)
│   ├── color_detection.py  # Modul untuk analisis warna dominan
│   ├── utils.py            # Fungsi bantu seperti pembacaan gambar, konversi format
│── images/
│   ├── sample.jpg          # Contoh gambar untuk diuji
│── results/
│   ├── output.jpg          # Hasil konversi atau analisis
│── requirements.txt        # Daftar dependensi
│── README.md               # Dokumentasi proyek
│── .gitignore              # File untuk mengabaikan file yang tidak perlu dalam Git
```

## Instalasi
Pastikan Anda memiliki **Python 3.x** terinstal di sistem Anda. Kemudian, jalankan perintah berikut untuk menginstal dependensi yang dibutuhkan:

```sh
pip install -r requirements.txt
```

## Cara Penggunaan
1. Letakkan gambar yang akan diuji dalam folder `images/`.
2. Jalankan skrip utama:
   ```sh
   python src/main.py
   ```
3. Hasil konversi warna dan deteksi warna dominan akan disimpan dalam folder `results/`.

## Dependensi
Berikut adalah pustaka yang digunakan dalam proyek ini:
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib
- Scikit-learn

Anda juga bisa menginstalnya satu per satu:
```sh
pip install opencv-python numpy matplotlib scikit-learn
```

## Lisensi
Proyek ini bersifat open-source dan dapat digunakan sesuai dengan lisensi yang berlaku.

## Kontributor
Jika ingin berkontribusi, silakan fork repository ini dan buat pull request dengan perbaikan atau fitur tambahan!

---
🚀 **Selamat Mencoba!**

