# Pinkary - Edukasi Otomatisasi & Analisis Trafik Profil

[![Python 3.x](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

![Pinkary](https://github.com/user-attachments/assets/58dda515-7cb6-4578-9a9c-b9c11b7b72dd)

**Pinkary** adalah program sederhana untuk mengirim views otomatis ke profil Pinkary, dibuat dengan Python. Dengan antarmuka yang mudah digunakan dan dukungan multi-threading, Pinkary membantu Anda meningkatkan views profil dengan cepat.

## Fitur

- ⚡ **Multi-Threading**: Kirim banyak permintaan views sekaligus dengan dukungan threading.
- 📊 **Statistik Real-Time**: Pantau jumlah views yang berhasil dikirim, gagal, dan kesalahan selama proses berlangsung.
- 🎨 **Rich Output**: Menggunakan modul `rich` untuk menampilkan output yang menarik di terminal.
- 💻 **User-Friendly**: Antarmuka yang jelas dan mudah digunakan.
- ⏱ **Performa Tinggi**: Optimasi dengan pengaturan jumlah permintaan dan thread untuk waktu eksekusi yang lebih cepat.

## Persyaratan

Pastikan Anda telah menginstal semua dependensi sebelum menjalankan program:

```bash
pip install -r requirements.txt
```

## Kebutuhan Modul:

- `fake-useragent`
- `rich`
- `mechanize`

## [Cara Menggunakan](https://youtu.be/SjTtGyQjhMY)

1. Clone repositori ini:
   
   ```bash
   git clone https://github.com/RozhakLabs/Pinkary.git
   ```
2. Install semua dependensi:
   
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan program:
   
   ```bash
   python Run.py
   ```
4. Masukkan tautan profil Pinkary yang ingin Anda tambahkan views, lalu masukkan jumlah views yang diinginkan.
5. Program akan menampilkan hasilnya dengan statistik:
   - **Success**: Views yang berhasil dikirim.
   - **Failed**: Views yang gagal.
   - **Errors**: Kesalahan yang terjadi selama proses.

## Contoh Keluaran

```bash
[?] Tautan : https://pinkary.com/@rozhak_official
[?] Count : 100

[*] Total Success: 85
[*] Total Failed: 10
[*] Total Errors: 5
```

## Troubleshooting

Jika views tidak berhasil masuk, atau Anda mengalami masalah lain, coba solusi berikut:

- ⚙️ **Pastikan Koneksi Stabil**: Koneksi internet yang lemah dapat menyebabkan kegagalan pengiriman views. Pastikan koneksi Anda stabil sebelum menjalankan program.
- 🔄 **Aktifkan Mode Pesawat**: Jika views tidak berhasil, IP Anda mungkin telah dibatasi. Aktifkan mode pesawat selama beberapa detik untuk mereset koneksi, lalu coba lagi.
- 🌐 **Gunakan VPN**: Jika mode pesawat tidak efektif, cobalah menggunakan VPN untuk menghindari blokir IP oleh Pinkary.
- 🔄 **Restart Program**: Jika Anda menemukan terlalu banyak error, coba hentikan program dan jalankan ulang.

Jika masalah berlanjut, periksa apakah Anda telah menginstal versi terbaru dari semua dependensi.

## Tangkapan Layar

![FunPic_20240907](https://github.com/user-attachments/assets/68a77dce-3c34-4f1c-b55d-541b57cf840f)

## Pengaturan Tambahan

Anda bisa menyesuaikan pengaturan jumlah thread untuk mempercepat proses pengiriman views. Secara default, program menggunakan 5 threads, namun Anda bisa menambah atau mengurangi sesuai kemampuan perangkat:

```python
num_threads = 10  # Menambah jumlah thread untuk proses yang lebih cepat
```

## Dukungan

Jika Anda menikmati menggunakan **Pinkary** dan ingin mendukung pengembang lebih lanjut, pertimbangkan untuk memberikan donasi melalui platform berikut:

- [Trakteer](https://trakteer.id/rozhak_official/tip)
- [PayPal](https://paypal.me/rozhak9)

## Kontribusi

Kontribusi selalu diterima! Jika Anda memiliki ide untuk peningkatan atau menemukan masalah, jangan ragu untuk membuka pull request atau membuat laporan di bagian [issues](https://github.com/RozhakLabs/Pinkary/issues).

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT. Lihat [LICENSE](LICENSE) untuk detail lebih lanjut.