# Web Weather

Aplikasi web cuaca modern yang menampilkan informasi cuaca real-time dengan tampilan responsif dan elegan. Aplikasi ini menggunakan API Open-Meteo untuk mendapatkan data cuaca terkini dan ramalan harian.

## Fitur Utama

- **Pencarian Kota**: Cari informasi cuaca berdasarkan nama kota
- **Deteksi Lokasi**: Otomatis mendeteksi lokasi pengguna (dengan izin)
- **Cuaca Real-time**: Menampilkan suhu, kelembaban, kecepatan angin, dan kondisi cuaca saat ini
- **Ramalan 6 Hari**: Prakiraan cuaca untuk 6 hari ke depan
- **Ikon Cuaca**: Visual ikon yang sesuai dengan kondisi cuaca
- **Responsive Design**: Tampilan optimal di desktop, tablet, dan mobile
- **Loading States**: Animasi loading yang smooth saat mengambil data

## Teknologi yang Digunakan

- **HTML5**: Struktur halaman web
- **CSS3**: Styling dan responsive design
- **JavaScript (ES6+)**: Logika aplikasi dan manipulasi DOM
- **Bootstrap 5**: Framework CSS untuk styling dan grid system
- **Open-Meteo API**: Sumber data cuaca
- **Geocoding API**: Untuk konversi nama kota ke koordinat
- **Nominatim API**: Reverse geocoding untuk deteksi lokasi

## API yang Digunakan

1. **Open-Meteo Weather API**: Untuk data cuaca real-time dan ramalan
2. **Open-Meteo Geocoding API**: Untuk pencarian koordinat berdasarkan nama kota
3. **Nominatim API**: Untuk reverse geocoding (koordinat ke nama kota)

## Cara Menjalankan

1. Clone atau download repository ini
2. Buka file `index.html` di browser
3. Izinkan akses lokasi untuk fitur deteksi otomatis (opsional)
4. Gunakan kolom pencarian untuk mencari cuaca kota lain

## Struktur File

- `index.html` - Halaman utama aplikasi
- `descriptions.js` - Data mapping kode cuaca ke deskripsi dan ikon
- `README.md` - Dokumentasi proyek

## Fitur Browser yang Diperlukan

- Geolocation API (untuk deteksi lokasi otomatis)
- Fetch API (untuk request data)
- ES6+ JavaScript support

## Screenshot

Aplikasi menampilkan:

- Waktu dan tanggal saat ini
- Suhu dengan ikon cuaca
- Deskripsi kondisi cuaca
- Detail: kelembaban, kecepatan angin, curah hujan
- Kartu ramalan 6 hari ke depan

## Catatan

- Aplikasi memerlukan koneksi internet untuk mengambil data cuaca
- Fitur deteksi lokasi memerlukan izin dari browser
- Data cuaca diperbarui setiap kali pencarian atau refresh halaman

---

Dibuat oleh Fadhlan Khusnaini Al Barid
