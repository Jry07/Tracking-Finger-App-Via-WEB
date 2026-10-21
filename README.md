# Tracking-Finger-App-Via-WEB
# ✋ Hitung Jari: 3 atau 5

Muhammad Fajri Jumadil (F1G125041)
Kelas A & C

Aplikasi web untuk mengidentifikasi jumlah jari (**3 atau 5**) langsung dari kamera. Dibuat dengan model klasifikasi gambar dari [Teachable Machine](https://teachablemachine.withgoogle.com/) dan dijalankan di browser memakai TensorFlow.js. Semua proses berjalan di perangkat pengguna, tidak ada gambar yang dikirim ke server.


## Fitur

- Identifikasi jari secara langsung lewat kamera (real-time)
- Tampilan tebakan model dalam persentase untuk tiap kelas
- Mode tantangan: tunjukkan 3 atau 5 jari dan tahan selama 1 detik untuk menambah skor
- Model sudah tertanam di dalam `index.html`, jadi tidak butuh file model tambahan
- Pesan kesalahan kamera yang jelas (izin ditolak, kamera tidak ditemukan, dll.)

## Teknologi

| Komponen | Versi |
| --- | --- |
| TensorFlow.js | 1.7.4 |
| @teachablemachine/image | 0.8.4 |
| Ukuran gambar model | 224 × 224 |

## Kelas model

| Label model | Ditampilkan sebagai |
| --- | --- |
| `TIGA` | 3 jari |
| `LIMA` | 5 jari |

## Cara menggunakan

1. Buka halaman aplikasi.
2. Klik **Nyalakan kamera** dan izinkan akses kamera.
3. Arahkan telapak tangan ke kamera dengan latar yang tidak terlalu ramai.
4. Lihat hasil tebakan dan persentasenya di panel kanan.
5. Ikuti tantangan di layar: tunjukkan jumlah jari yang diminta dan tahan selama 1 detik.

## Menjalankan di komputer sendiri
