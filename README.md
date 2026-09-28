# Warung Madura Android

Project Android offline untuk aplikasi kasir Warung Madura.

## Build dari HP melalui GitHub Actions
1. Buat repository GitHub baru.
2. Upload seluruh isi folder `WarungMaduraAndroid` ke repository (bukan folder pembungkus ZIP).
3. Buka tab **Actions** dan pilih workflow **Build Warung Madura APK**.
4. Tekan **Run workflow** jika tersedia, atau push ke branch `main` untuk menjalankan otomatis.
5. Setelah selesai, buka hasil workflow dan bagian **Artifacts**, lalu unduh `Warung-Madura-APK`.
6. Di dalam ZIP artifact terdapat `app-debug.apk`.

Project menggunakan Android Gradle Plugin 8.6.1 dan Gradle 8.7.
