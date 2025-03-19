# Hand Gesture Recognition with Mediapipe

Proyek ini adalah aplikasi Python untuk mendeteksi dan melacak gerakan tangan secara real-time menggunakan [Mediapipe](https://google.github.io/mediapipe/) dan OpenCV.

---

## Fitur
- Deteksi tangan secara real-time menggunakan webcam.
- Visualisasi landmark tangan dengan koneksi antar titik.
- Konfigurasi warna untuk landmark dan koneksi.

---

## Prasyarat
Pastikan Anda memiliki **Python 3.7 atau versi lebih baru** yang sudah terinstal di sistem Anda.

---

## Instalasi

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/farasalgh/hand-tracking-mediapipe.git
   cd hand-tracking-mediapipe
   ```

2. **Buat dan aktifkan virtual environment (opsional, direkomendasikan):**
   ```bash
   python -m venv venv
   
   # Windows
   venv\Scripts\activate
   
   # macOS/Linux
   source venv/bin/activate
   ```

3. **Instal dependensi:**
   ```bash
   pip install -r requirements.txt
   ```

**Catatan:** Jika file `requirements.txt` belum tersedia, tambahkan dependensi berikut ke dalamnya:
   ```
   opencv-python
   mediapipe
   numpy
   ```

---

## Cara Menjalankan
Jalankan skrip Python berikut untuk mulai mendeteksi tangan:
```bash
python hand.py
```
Aplikasi akan membuka jendela webcam dan mulai mendeteksi tangan. **Tekan tombol `q` untuk keluar dari aplikasi.**

---

## Struktur Proyek
```
hand-gesture-recognition-mediapipe/
│
├── hand.py             # Skrip utama untuk deteksi dan pelacakan tangan
├── requirements.txt    # File untuk mendefinisikan dependensi proyek
├── README.md           # Dokumentasi proyek
└── assets/             # Folder untuk menyimpan gambar atau contoh hasil (opsional)
```

---

## Teknologi yang Digunakan
- **OpenCV**: Untuk menangkap video dan memproses gambar.
- **Mediapipe**: Untuk deteksi dan pelacakan tangan.
- **NumPy**: Untuk manipulasi array.

---

## Kontribusi
Kontribusi sangat diterima! Jika Anda ingin berkontribusi, ikuti langkah berikut:

1. Fork repositori ini.
2. Buat branch baru untuk fitur atau perbaikan Anda:
   ```bash
   git checkout -b fitur-baru
   ```
3. Commit perubahan Anda:
   ```bash
   git commit -m "Menambahkan fitur baru"
   ```
4. Push ke branch Anda:
   ```bash
   git push origin fitur-baru
   ```
5. Buat **Pull Request** di GitHub.

Jika Anda menemukan bug atau memiliki saran, silakan buka **Issue** di repositori ini. 😊

---

Jika Anda memerlukan bantuan lebih lanjut, silakan hubungi saya!

