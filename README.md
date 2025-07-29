Dokumentasi Teknik

Deskripsi Sistem
Sistem ini adalah aplikasi manajemen inventori yang memungkinkan pengguna untuk menambah, mengedit, menghapus, mencari, dan menampilkan barang dalam inventori. Selain itu, sistem ini juga dapat menghitung total nilai inventori dan mengekspor data ke file JSON.

Struktur Kelas
InventoryItem: Kelas ini merepresentasikan item dalam inventori.

Atribut:
name: Nama barang.
stock: Jumlah stok barang.
price: Harga barang.
Metode:
to_dict(): Mengonversi objek menjadi dictionary untuk ekspor ke file.
Inventory: Kelas ini mengelola koleksi InventoryItem.

Atribut:
items: List yang menyimpan objek InventoryItem.
Metode:
add_item(item): Menambahkan item baru ke dalam inventori.
display_items(): Menampilkan semua item dalam inventori.
edit_item(index, name, stock, price): Mengedit informasi item berdasarkan indeks.
delete_item(index): Menghapus item berdasarkan indeks.
search_item(name): Mencari item berdasarkan nama.
total_inventory_value(): Menghitung total nilai inventori.
export_to_file(filename): Mengekspor data inventori ke file JSON.

Contoh Penggunaan
Menambahkan barang baru ke dalam inventori.
Mengedit informasi barang yang sudah ada.
Menghapus barang dari inventori.
Mencari barang berdasarkan nama.
Menampilkan ringkasan total barang dan nilai inventori.
Mengekspor data inventori ke file JSON.

User Manual
USER MANUAL: SISTEM INVENTORI
1. Tambah Barang
Pilih menu '1'.
Masukkan nama barang, jumlah stok, dan harga barang.
Barang akan ditambahkan ke dalam inventori.
2. Tampilkan Daftar Barang
Pilih menu '2'.
Semua barang yang tersimpan dalam inventori akan ditampilkan beserta informasi stok dan harga.
3. Edit Barang
Pilih menu '3'.
Masukkan nomor barang yang ingin diedit.
Masukkan nama baru, stok baru, dan harga baru untuk barang tersebut.
4. Hapus Barang
Pilih menu '4'.
Masukkan nomor barang yang ingin dihapus dari inventori.
5. Cari Barang
Pilih menu '5'.
Masukkan nama barang yang ingin dicari.
Jika barang ditemukan, informasi tentang barang tersebut akan ditampilkan.
6. Laporan Ringkas
Pilih menu '6'.
Sistem akan menampilkan jumlah total barang dan total nilai inventori.
7. Export ke File
Pilih menu '7'.
Masukkan nama file untuk menyimpan data inventori (misal: inventory.json).
Data inventori akan diekspor ke file JSON.
8. Keluar
Pilih menu '8' untuk keluar dari aplikasi.
