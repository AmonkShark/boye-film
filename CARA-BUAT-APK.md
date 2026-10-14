# Boye Film — cara membuat APK

APK dibuat otomatis dan gratis oleh GitHub. Tidak perlu memasang Android Studio.

1. Buat akun di github.com (kalau belum punya).
2. Klik **New repository**, beri nama `boye-film`, lalu **Create repository**.
3. Klik **uploading an existing file**. Ekstrak `BoyeFilm.zip`, lalu seret **semua isi folder** (termasuk folder `.github`) ke halaman itu. Klik **Commit changes**.
   - Kalau folder `.github` tidak ikut terunggah: klik **Add file → Create new file**, ketik nama `.github/workflows/build-apk.yml`, lalu tempel isi file tersebut.
4. Buka tab **Actions**. Proses "Build APK Boye Film" akan berjalan sekitar 3–5 menit sampai muncul centang hijau.
5. Klik proses itu, gulir ke bawah ke **Artifacts**, unduh **BoyeFilm-apk**, lalu ekstrak.
6. Pindahkan file `.apk` ke HP, buka, dan izinkan **Instal dari sumber tidak dikenal**.

## Mengubah tampilan
Semua tampilan ada di `app/src/main/assets/index.html`. Setelah diubah, unggah ulang ke GitHub dan APK baru akan dibuat otomatis.
