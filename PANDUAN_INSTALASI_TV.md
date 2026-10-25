# 📺 Panduan Instalasi IDLIX di Android TV & Google TV (Untuk Pengguna Awam)

Panduan ini ditujukan bagi Anda yang ingin memasang (**install**) aplikasi IDLIX di Smart TV, Android TV Box, atau Google TV secara mandiri tanpa perlu laptop/coding atau backend server.

---

## 📋 Syarat & Persiapan Awal

1. **Perangkat TV**: Android TV, Google TV, atau TV Box (seperti ZTE B860H, Mi TV Stick, Mi Box, Chromecast with Google TV, RealMe TV Stick, Aqua, Coocaa, TCL, dsb.).
2. **File APK**: File aplikasi IDLIX TV (`IDLIX-TV-Standalone.apk` atau `app-debug.apk`).
3. **Koneksi Wi-Fi / Internet**: Pastikan TV terhubung ke jaringan internet rumah Anda.

---

## ⚙️ Langkah Wajib: Mengaktifkan Izin "Sumber Tidak Dikenal"

Android TV secara default membatasi instalasi aplikasi dari luar Google Play Store. Ikuti langkah ini sekali saja:

### Untuk Google TV (Versi Baru / Chromecast / Sony / TCL):
1. Masuk ke **Setelan (Settings)** di pojok kanan atas layar TV (ikon gerigi).
2. Pilih **Sistem (System)** > **Tentang (About)**.
3. Geser ke bawah ke tulisan **Build OS Android TV (Android TV OS Build)**.
4. Tekan tombol **OK / Tengah** di remote sebanyak **7 kali berturut-turut** hingga muncul tulisan *"Anda sekarang adalah developer!"*.
5. Tekan tombol *Back/Kembali*, lalu buka menu **Aplikasi (Apps)** > **Keamanan & Pembatasan (Security & Restrictions)**.
6. Pilih **Instal Aplikasi Tidak Dikenal (Install unknown apps)**.
7. Cari aplikasi File Manager yang akan digunakan (misal: *File Commander*, *Send Files to TV*, atau *AnExplorer*), lalu ubah posisinya menjadi **Aktif / Izinkan (Allow)**.

### Untuk Android TV Standar (ZTE B860H, Mi TV Stick, Mi Box):
1. Buka **Setelan (Settings)** > **Preferensi Perangkat (Device Preferences)**.
2. Pilih **Keamanan & Pembatasan (Security & Restrictions)**.
3. Aktifkan opsi **Sumber Tidak Dikenal (Unknown Sources)** untuk aplikasi File Manager Anda.

---

## 🚀 Pilihan Cara Pasang (Pilih Salah Satu)

### 🔹 Cara 1: Menggunakan HP (Paling Praktis & Tanpa Kabel / USB)
*Sangat disarankan untuk Mi TV Stick atau Chromecast yang tidak memiliki lubang colokan USB.*

1. **Install aplikasi perantara di HP & TV**:
   * Buka **Google Play Store** di TV dan di HP Android Anda.
   * Pasang aplikasi bernama **"Send Files to TV" (SFTTV)** di kedua perangkat tersebut.
   * Pasang juga aplikasi file manager di TV (misalnya **File Commander** atau **AnExplorer** dari Play Store TV).
2. **Kirim APK dari HP ke TV**:
   * Pastikan HP dan TV terhubung ke **jaringan Wi-Fi yang sama**.
   * Buka aplikasi *Send Files to TV* di TV dan pilih **RECEIVE** (Terima).
   * Buka aplikasi *Send Files to TV* di HP, pilih **SEND** (Kirim), lalu pilih file APK IDLIX yang ada di HP Anda.
   * Pilih nama TV Anda di layar HP. Proses transfer akan berjalan cepat dalam beberapa detik.
3. **Instal di TV**:
   * Setelah selesai, klik file tersebut langsung dari layar aplikasi *Send Files to TV* di TV, lalu pilih **Open with Package Installer**.
   * Jika tidak bisa langsung dibuka, buka aplikasi **File Commander / AnExplorer** di TV, masuk ke folder **Download**, lalu klik file APK IDLIX untuk menginstalnya.
   * Pilih **Install**. Selesai!

---

### 🔹 Cara 2: Menggunakan Flashdisk / USB Drive (Paling Mudah jika ada Port USB)
*Sangat cocok untuk Android TV Box (ZTE B860H, dsb.) atau Smart TV yang memiliki port USB.*

1. **Siapkan Flashdisk**:
   * Salin (copy) file APK IDLIX dari komputer ke dalam Flashdisk.
2. **Pasang File Manager di TV**:
   * Buka **Google Play Store** di TV.
   * Pasang salah satu aplikasi File Manager gratis (contoh: **File Commander** atau **AnExplorer**).
3. **Colok Flashdisk ke TV**:
   * Masukkan Flashdisk ke port USB di TV Box atau TV Anda.
4. **Buka dan Pasang**:
   * Buka aplikasi File Manager di TV.
   * Buka folder Flashdisk Anda, cari file APK IDLIX.
   * Tekan tombol **OK** pada file APK, lalu pilih **Install**.
   * Tunggu hingga muncul pemberitahuan *"Aplikasi Terpasang"*.

---

### 🔹 Cara 3: Menggunakan Aplikasi "Downloader" (Download Langsung di TV)

1. Buka **Google Play Store** di TV, cari dan pasang aplikasi **Downloader by AFTVnews**.
2. Buka aplikasi **Downloader** di TV.
3. Masukkan link download langsung dari file APK pada kolom URL.
4. Tekan tombol **Go**. File akan terunduh langsung ke TV.
5. Setelah unduhan selesai, jendela instalasi otomatis muncul. Pilih **Install**.

---

## ❓ Pertanyaan & Masalah yang Sering Terjadi (Troubleshooting)

### 1. Muncul peringatan "Diblokir oleh Play Protect"?
* **Penyebab**: Karena aplikasi dipasang secara manual (sideload) di luar Play Store resmi.
* **Solusi**: Klik tulisan **"Detail Selengkapnya (More details)"**, lalu pilih **"Tetap Instal (Install anyway)"**. Aplikasi ini 100% aman dan bebas iklan judol.

### 2. Apakah butuh laptop/server menyala saat menonton?
* **Tidak sama sekali!** Aplikasi ini sudah 100% mandiri (*standalone*). Cukup buka aplikasinya di TV dan Anda bisa langsung streaming film dan serial kapan saja selama TV terhubung ke internet.

### 3. Subtitle tidak muncul atau ingin ganti bahasa?
* Saat film diputar, tekan tombol arah **Atas/Bawah** di remote TV untuk memunculkan panel kontrol player.
* Pilih tombol **Ikon Subtitle (CC)** di pojok kanan bawah untuk memilih subtitle bawaan (Bahasa Indonesia & English) atau mencari subtitle tambahan via integrasi SubDL.
