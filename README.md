## ✨ Fitur Utama
- **Otomatis Berulang**: Dijadwalkan otomatis setiap 4 jam (dapat disesuaikan).
- **Views Permanen**: Views yang dikirim bersifat permanen dan tidak hilang.
- **Tanpa Login**: Tidak perlu akun TikTok atau autentikasi apa pun.
- **User Agent Acak**: Menggunakan *user agent* acak untuk menghindari deteksi.
- **Aman & Privasi**: Tidak menyimpan data pengguna atau informasi pribadi.

## 🛠️ Persyaratan Sistem
- Python 3.12 atau versi lebih baru.
- Library Pendukung:
  - `requests`
  - `fake_useragent`
  - `pytz`
  - `rich`
  - `requests_toolbelt`
 
## 📥 Instalasi
```bash
apt update -y && apt upgrade -y
pkg install git python-pip
git clone https://github.com/RozhakXD/TikBoostX.git
cd "TikBoostX"
pip install -r requirements.txt
python Run.py
```

## 🛠️ Tips & Solusi
TikBoostX menggunakan API publik dari layanan pihak ketiga, sehingga legalitas penggunaannya bergantung pada kebijakan masing-masing platform. Pastikan untuk menggunakannya dengan bijak dan sesuai dengan aturan yang berlaku.  

Batasan 100 views per 4 jam diterapkan sebagai langkah aman untuk menghindari deteksi oleh sistem TikTok. Jika ingin mengubah batas ini, Anda dapat menyesuaikan interval waktu langsung di dalam kode.  

Jika muncul error "remainingTime", itu berarti Anda harus menunggu sebelum mengirim permintaan berikutnya. Program akan menampilkan waktu tunggu yang diperlukan, jadi pastikan koneksi internet Anda stabil untuk menghindari gangguan.
