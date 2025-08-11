# Face Recognition Project

Proyek ini merupakan implementasi sistem **pengenalan wajah** menggunakan Python, OpenCV, dan library Machine Learning.  
Aplikasi ini dapat mendeteksi wajah secara real-time menggunakan kamera, serta melakukan identifikasi berdasarkan model yang sudah dilatih.

#📌 Fitur
- Deteksi wajah secara real-time melalui webcam.
- Klasifikasi atribut wajah (jenis kelamin, umur, ras, dll. — opsional).
- Mendukung model yang disimpan dalam format `.pkl`.
- Bisa digunakan untuk dataset khusus maupun umum (misalnya LFW atau CelebA).

#🛠 Teknologi yang Digunakan
- **Python 3.x**
- [OpenCV](https://opencv.org/) — untuk pengolahan citra & deteksi wajah.
- [face_recognition](https://github.com/ageitgey/face_recognition) — untuk ekstraksi dan pencocokan fitur wajah.
- NumPy & Pandas — untuk manipulasi data.
- Pickle (`.pkl`) — untuk menyimpan model.

#📂 Struktur Proyek
```
Face Recognition/
│
├── face_recognition.ipynb # Notebook utama
├── face_model.pkl # Model machine learning
├── dataset/ # Dataset wajah (opsional)
├── requirements.txt # Daftar dependencies
└── README.md # Dokumentasi proyek
```

# 🚀 Cara Menjalankan
1. Clone repository
   ```bash
   git clone https://github.com/Achmadtegar23/Face-Recognition.git
   cd face-recognition
2. Jalankan Jupiter Notebook
   ```bash
   jupyter notebook face_recognition.ipynb
3. Jalankan Masing Masing Sel (Jika bermasalah silahkan berdiskusi dengan AI)

# 📄 Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

_Jangan ragu untuk memberikan bintang ⭐ pada repositori ini jika Anda merasa terbantu!_




