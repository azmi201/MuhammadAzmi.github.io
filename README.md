# LED Control via Wi-Fi (ESP32)

Proyek ini memungkinkan Anda untuk mengontrol LED menggunakan Wi-Fi dengan memanfaatkan ESP32. Anda dapat mengakses antarmuka web melalui browser dengan memasukkan alamat IP ESP32 yang diberikan setelah terhubung ke jaringan Wi-Fi.

## Fitur
- Mengontrol LED melalui antarmuka web menggunakan browser.
- Akses melalui alamat IP yang diberikan oleh ESP32 setelah terhubung ke Wi-Fi.

## Persyaratan
- ESP32 DevKit (atau mikrokontroler ESP32 lainnya)
- Kabel USB untuk menghubungkan ESP32 ke komputer
- LED dan resistor (untuk menghubungkan LED ke ESP32)
- Jaringan Wi-Fi untuk koneksi ESP32
- Arduino IDE atau platform pemrograman lain yang mendukung ESP32

## Cara Penggunaan
1. **Koneksi ESP32 ke Wi-Fi**:
   - Program akan secara otomatis menghubungkan ESP32 ke jaringan Wi-Fi yang telah ditentukan di kode (masukkan SSID dan password Wi-Fi Anda di dalam kode).

2. **Menjalankan Program**:
   - Setelah mengupload program ke ESP32, buka Serial Monitor untuk mendapatkan alamat IP ESP32.
   - Akses alamat IP ini di browser untuk mengontrol LED.

3. **Kontrol LED**:
   - Di halaman web, klik tombol untuk menyalakan atau mematikan LED.

## Instalasi

1. Clone repository ini ke komputer Anda:
2. 2. Buka file `.ino` dengan Arduino IDE atau platform lainnya yang mendukung ESP32.

3. Masukkan SSID dan password jaringan Wi-Fi Anda dalam kode.

4. Upload kode ke ESP32 melalui kabel USB.

5. Cek Serial Monitor untuk alamat IP ESP32.

6. Akses IP tersebut menggunakan browser untuk mengontrol LED.

## Kontak
Jika Anda memiliki pertanyaan, Anda dapat menghubungi kami melalui email di ARDU.ESP.IoT@proton.me
