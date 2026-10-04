[README.txt](https://github.com/user-attachments/files/33030726/README.txt)
KK SCAN RT
==========

Fungsi:
- Foto/ambil gambar Kartu Keluarga dari kamera HP atau upload JPG/PNG.
- OCR bahasa Indonesia berjalan di browser.
- Otomatis mencoba membaca No. KK, Kepala Keluarga, alamat, wilayah, dan baris anggota yang memiliki NIK 16 digit.
- Semua hasil dapat diedit sebelum disimpan.
- Data yang sudah disimpan berada di localStorage perangkat/browser.
- Ekspor ke Excel (.xlsx) menjadi dua sheet: Data KK dan Data Anggota.

CATATAN PRIVASI:
- Foto KK diproses oleh JavaScript di browser.
- Tidak ada kode pada aplikasi ini yang mengirim foto KK ke server milik aplikasi.
- Library OCR dan Excel diambil dari CDN saat aplikasi pertama kali dibuka.
- Untuk penggunaan tanpa internet atau instalasi internal, library CDN dapat di-vendoring/self-host.

PENTING:
OCR tidak menjamin akurasi 100%. Untuk data kependudukan, selalu cek hasil terhadap KK asli sebelum menandai "Sudah Diverifikasi".

DEPLOY GITHUB PAGES:
1. Upload index.html ke repository GitHub.
2. Settings > Pages > Deploy from branch.
3. Pilih branch main dan folder /root.
4. Buka URL Pages melalui HTTPS agar akses kamera HP bisa digunakan.

BROWSER:
Gunakan Chrome/Edge/Safari versi modern. Fitur kamera memerlukan konteks HTTPS (GitHub Pages termasuk HTTPS).
