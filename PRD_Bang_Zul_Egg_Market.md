# Product Requirement Document (PRD)

# Bang Zul Egg Market

**Website Penjualan Telur Kabupaten Tanggamus**

## 1. Latar Belakang

Perkembangan teknologi informasi memberikan peluang bagi pelaku usaha untuk mengembangkan kegiatan perdagangan melalui platform digital. Salah satu usaha yang dapat dikembangkan adalah penjualan telur.

Proses penjualan telur yang masih dilakukan secara konvensional memiliki beberapa keterbatasan, seperti jangkauan pemasaran yang terbatas, pencatatan transaksi secara manual, serta kesulitan konsumen dalam memperoleh informasi harga dan ketersediaan stok.

Oleh karena itu, dikembangkan Bang Zul Egg Market, yaitu website penjualan telur yang bertujuan mempermudah proses pemasaran, pemesanan, pembayaran, dan pengelolaan penjualan telur di Kabupaten Tanggamus.

## 2. Tujuan Produk

1. Membantu Bang Zul memasarkan produk telur secara online.

2. Mempermudah masyarakat melakukan pembelian telur.

3. Menyediakan informasi harga dan stok produk secara langsung.

4. Mempermudah pengelolaan pesanan dan transaksi.

5. Menyediakan laporan penjualan secara otomatis.

6. Mendukung digitalisasi perdagangan lokal di Kabupaten Tanggamus.

## 3. Target Pengguna

| Pengguna | Kebutuhan |
| --- | --- |
| Admin | Mengelola seluruh data dan aktivitas website. |
| Penjual (Bang Zul) | Mengelola produk, harga, stok, dan pesanan. |
| Pembeli | Melihat produk, membeli telur, dan memantau pesanan. |
| Kurir | Melihat informasi pengiriman dan memperbarui status pesanan. |

## 4. Permasalahan dan Solusi

| Permasalahan | Solusi Sistem |
| --- | --- |
| Pemasaran masih terbatas | Menyediakan katalog produk online. |
| Informasi harga sulit diperoleh | Menampilkan harga produk pada website. |
| Stok tidak terpantau | Menyediakan pengelolaan stok otomatis. |
| Pemesanan masih manual | Menyediakan fitur checkout. |
| Pencatatan transaksi kurang efektif | Menyediakan riwayat dan laporan transaksi. |
| Konsumen kesulitan mengetahui pesanan | Menyediakan pelacakan status pesanan. |

## 5. Ruang Lingkup Produk

Website Bang Zul Egg Market memiliki dua bagian utama:

### A. Halaman Pengunjung dan Pembeli

- Beranda website.

- Katalog produk telur.

- Detail produk.

- Pencarian dan filter produk.

- Keranjang belanja.

- Checkout dan pemesanan.

- Pembayaran.

- Riwayat transaksi.

- Pelacakan pesanan.

- Profil dan alamat pembeli.

### B. Dashboard Admin dan Penjual

- Dashboard statistik penjualan.

- Manajemen produk telur.

- Manajemen kategori produk.

- Manajemen stok.

- Manajemen pesanan.

- Verifikasi pembayaran.

- Manajemen pelanggan.

- Manajemen pengiriman.

- Laporan penjualan.

- Pengaturan profil toko.

## 6. Kebutuhan Fungsional (Functional Requirements)

Kebutuhan fungsional merupakan fitur-fitur yang harus tersedia di dalam sistem.

| ID | Fitur | Deskripsi |
| --- | --- | --- |
| FR-01 | Registrasi | Pembeli dapat membuat akun. |
| FR-02 | Login | Pengguna dapat masuk sesuai hak akses. |
| FR-03 | Katalog Produk | Menampilkan berbagai produk telur. |
| FR-04 | Detail Produk | Menampilkan foto, harga, stok, dan deskripsi telur. |
| FR-05 | Pencarian | Mencari produk berdasarkan nama atau kategori. |
| FR-06 | Keranjang | Menambahkan dan menghapus produk belanja. |
| FR-07 | Checkout | Melakukan pemesanan produk. |
| FR-08 | Pembayaran | Memilih metode pembayaran yang tersedia. |
| FR-09 | Manajemen Produk | Penjual dapat menambah, mengubah, dan menghapus produk. |
| FR-10 | Manajemen Stok | Penjual dapat memperbarui jumlah stok telur. |
| FR-11 | Manajemen Pesanan | Penjual dapat memproses pesanan pelanggan. |
| FR-12 | Status Pengiriman | Pembeli dapat memantau status pengiriman. |
| FR-13 | Laporan Penjualan | Menampilkan rekap transaksi dan pendapatan. |
| FR-14 | Manajemen Pengguna | Admin dapat mengelola akun pengguna. |
| FR-15 | Riwayat Transaksi | Pembeli dapat melihat transaksi sebelumnya. |

## 7. Kebutuhan Non-Fungsional (Non-Functional Requirements)

| Aspek | Kebutuhan |
| --- | --- |
| Keamanan | Password harus disimpan dalam bentuk hash. |
| Performa | Halaman dan proses transaksi harus memiliki waktu respons yang baik. |
| Responsif | Website dapat digunakan melalui laptop, tablet, dan smartphone. |
| Database | Menggunakan PostgreSQL untuk menyimpan data. |
| Backend | Menggunakan bahasa pemrograman Rust. |
| Kemudahan | Tampilan mudah dipahami oleh pengguna. |
| Ketersediaan | Sistem dapat diakses selama server tersedia. |
| Validasi | Sistem memvalidasi data sebelum disimpan. |
| Hak Akses | Setiap pengguna memiliki akses sesuai perannya. |

## 8. Rancangan Arsitektur Teknologi

Teknologi yang digunakan dalam pengembangan website Bang Zul Egg Market adalah sebagai berikut.

![Ilustrasi image1.png](bang_zul_prd_assets/image1.png)

### Penjelasan teknologi:

- **Rust: Digunakan untuk membangun backend agar pengolahan data dan logika bisnis berjalan secara efisien.**

- **Axum: Framework Rust untuk membangun REST API.**

- **SQLx: Library Rust untuk menghubungkan backend dengan PostgreSQL.**

- **PostgreSQL: Digunakan sebagai database utama.**

- **Bootstrap: Membantu membuat tampilan website responsif dan mudah digunakan.**

## 9. Rancangan Database PostgreSQL

Berikut rancangan tabel database yang dibutuhkan.

| Nama Tabel | Fungsi |
| --- | --- |
| users | Menyimpan data admin, penjual, dan pembeli. |
| categories | Menyimpan kategori telur. |
| products | Menyimpan informasi produk dan harga. |
| carts | Menyimpan keranjang belanja. |
| cart_items | Menyimpan detail produk dalam keranjang. |
| orders | Menyimpan data pesanan. |
| order_items | Menyimpan detail produk yang dipesan. |
| payments | Menyimpan informasi pembayaran. |
| shipments | Menyimpan informasi pengiriman. |
| addresses | Menyimpan alamat pembeli. |

### Relasi database:

![Ilustrasi image2.png](bang_zul_prd_assets/image2.png)

### Relasi utama:

- Users memiliki banyak pesanan.

- Categories memiliki banyak produk.

- Orders memiliki banyak detail produk.

- Products dapat muncul dalam banyak detail pesanan.

- Orders memiliki informasi pembayaran dan pengiriman.

## 10. Alur Penggunaan Sistem

Berikut alur proses pembelian telur melalui website.

![Ilustrasi image3.png](bang_zul_prd_assets/image3.png)

## 11. Rancangan Halaman Website

Halaman yang perlu dibuat dalam pengembangan Bang Zul Egg Market:

| Halaman | Keterangan |
| --- | --- |
| Beranda | Informasi toko dan produk unggulan. |
| Katalog | Daftar seluruh produk telur. |
| Detail Produk | Informasi lengkap produk. |
| Login/Register | Autentikasi pengguna. |
| Keranjang | Daftar belanja pembeli. |
| Checkout | Formulir pemesanan dan alamat. |
| Riwayat Pesanan | Daftar transaksi pembeli. |
| Dashboard Admin | Statistik penjualan dan aktivitas toko. |
| Data Produk | Pengelolaan produk dan stok. |
| Data Pesanan | Pengelolaan pesanan pelanggan. |
| Laporan | Rekap penjualan dan pendapatan. |

## 12. Validasi PRD Berdasarkan Kebutuhan

Validasi dilakukan untuk memastikan bahwa rancangan website sesuai dengan kebutuhan pengguna dan teknologi yang digunakan.

| No. | Aspek Validasi | Kriteria Keberhasilan |
| --- | --- | --- |
| 1 | Kebutuhan pengguna | Fitur sesuai kebutuhan pembeli dan penjual. |
| 2 | Fungsionalitas | Semua fitur utama dapat berjalan. |
| 3 | Backend Rust | REST API dapat menangani permintaan data. |
| 4 | Database PostgreSQL | Data produk, pengguna, dan transaksi tersimpan dengan benar. |
| 5 | Keamanan | Password terenkripsi menggunakan hashing dan akses dibatasi berdasarkan peran. |
| 6 | Integrasi | Backend Rust berhasil terhubung dengan PostgreSQL. |
| 7 | Responsivitas | Website dapat digunakan di berbagai ukuran layar. |
| 8 | Transaksi | Perhitungan harga dan pengurangan stok berjalan dengan benar. |

### Skenario Pengujian

| Pengujian | Hasil yang Diharapkan |
| --- | --- |
| Registrasi akun | Akun berhasil dibuat. |
| Login | Pengguna berhasil masuk. |
| Tambah produk | Produk tersimpan di database. |
| Update stok | Jumlah stok berhasil diperbarui. |
| Pemesanan | Pesanan berhasil dibuat. |
| Pembayaran | Status pembayaran dapat diperbarui. |
| Laporan penjualan | Data transaksi ditampilkan sesuai database. |
| Koneksi database | Rust berhasil membaca dan menyimpan data PostgreSQL. |

> **Catatan validasi: Tabel di atas merupakan kriteria dan rencana pengujian PRD, bukan hasil pengujian implementasi yang sudah dilakukan. Pengujian nyata perlu dilakukan setelah aplikasi selesai dikembangkan.**

## 13. Prioritas Pengembangan

Pengembangan dilakukan secara bertahap agar fitur utama dapat diselesaikan terlebih dahulu.

| Prioritas | Fitur |
| --- | --- |
| Tinggi | Login, katalog produk, detail produk, keranjang, checkout. |
| Tinggi | Dashboard penjual, pengelolaan produk dan stok. |
| Tinggi | Manajemen pesanan dan transaksi. |
| Menengah | Riwayat pesanan dan laporan penjualan. |
| Menengah | Pengelolaan pengiriman dan status pesanan. |
| Rendah | Notifikasi otomatis dan analisis penjualan. |

## 14. Kesimpulan

Berdasarkan hasil brainstorming dan penyusunan Product Requirement Document (PRD), Bang Zul Egg Market merupakan solusi digital untuk membantu kegiatan penjualan telur di Kabupaten Tanggamus.

Website ini dirancang untuk mempermudah penjual dalam mengelola produk, stok, pesanan, dan transaksi. Sementara itu, pembeli dapat memperoleh informasi produk, melakukan pemesanan, serta memantau status pengiriman secara online.

Penggunaan teknologi Rust sebagai backend dan PostgreSQL sebagai database diharapkan dapat menghasilkan sistem yang terstruktur, aman, dan efisien. Dengan demikian, pengembangan Bang Zul Egg Market diharapkan dapat mendukung digitalisasi perdagangan lokal sebagai bagian dari penerapan konsep Smart City di Kabupaten Tanggamus.
