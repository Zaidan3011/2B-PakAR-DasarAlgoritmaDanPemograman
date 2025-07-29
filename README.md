Aplikasi Manajemen Inventori Sederhana
Dokumentasi Teknis
Struktur File/Kode
inventory.py: File utama aplikasi.
Kelas InventoryItem: Menyimpan informasi item (nama, stok, harga).
Kelas Inventory: Mengelola daftar item dengan metode untuk menambah, menampilkan, mengedit, menghapus, mencari, menghitung nilai total, dan mengekspor data.
Fungsi main(): Antarmuka pengguna untuk interaksi.
Library yang Digunakan
json: Untuk menyimpan dan memuat data inventori ke/dari file JSON.
Diagram Alur Kerja

Run
Copy code
[Start] -> [Display Menu] -> [User  Input] -> [Process Input] -> [Display Result] -> [Repeat or Exit] -> [End]
User Manual
Cara Menjalankan Aplikasi
Jalankan program dengan perintah: python inventory.py.
Pilih opsi dari menu yang ditampilkan.
Contoh Input
Tambah Barang: Pilih 1, masukkan nama, stok, dan harga.
Edit Barang: Pilih 3, masukkan nomor barang, dan data baru.
Hapus Barang: Pilih 4, masukkan nomor barang yang ingin dihapus.
Fitur Tambahan
Cari Barang: Pilih 5, masukkan nama barang.
Laporan Ringkas: Pilih 6, lihat jumlah total barang dan nilai inventori.
Ekspor ke File: Pilih 7, masukkan nama file (misal: inventory.json).
Keluar dari Aplikasi
Pilih 8 untuk keluar.
