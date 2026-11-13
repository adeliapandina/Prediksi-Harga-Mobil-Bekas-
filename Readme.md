# 🚗 Prediksi Harga Mobil Bekas

Aplikasi web berbasis Google Apps Script dan Google Sheets untuk memprediksi estimasi harga jual mobil bekas berdasarkan spesifikasi kendaraan (Merek/Model, Tahun Pembuatan, Kilometer, Transmisi, dan Kapasitas Mesin).

## Fitur Utama
- **User Interface Interaktif:** Form input spesifikasi kendaraan dan dashboard riwayat prediksi real-time.
- **Integrasi Model Prediksi:** Kalkulasi estimasi harga otomatis di sisi server (`Code.gs`).
- **Database Otomatis:** Pencatatan log prediksi secara langsung ke Google Sheets (`RiwayatPrediksiHargaMobil`).

## Struktur File
- `Code.gs` : Logika backend, kalkulasi model prediksi, dan koneksi database Google Sheets.
- `Index.html` : Antarmuka pengguna (UI), styling, dan skrip klien.

Link Demo App : https://script.google.com/macros/s/AKfycbwsa2m2IeNqLNhogZQ9CtINvOrnq-SC3rqhlkqVp67PgVv74ES_L5CQqRTtUsNvrZ-wJQ/exec