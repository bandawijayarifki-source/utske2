# Bang Zul Egg Market 🥚
> **Website Penjualan Telur Segar Peternak Lokal Kabupaten Tanggamus**

Website e-commerce dan platform manajemen penjualan telur berbasis web responsif untuk UD. Bang Zul di Kabupaten Tanggamus, Lampung. Menghubungkan pembeli, penjual (Bang Zul), kurir pengantaran lokal, dan pengawas pasar.

---

## 🌟 Fitur Utama

### 1. Pembeli (Customer Portal)
- **Beranda Interaktif (`index.html`)**: Info stok panen pagi, harga pasar harian resmi, produk unggulan, dan jaminan 100% ganti telur pecah.
- **Katalog Lengkap (`katalog.html`)**: 9 varian komoditas telur (Ras, Kampung, Omega-3, Bebek Tambak, Puyuh, Grosir) dengan filter kategori, slider harga, dan tombol belanja cepat.
- **Belanja Cepat (`katalog-cepat.html`)**: Tampilan bento grid dengan keranjang langsung di samping (*sticky cart*).
- **Detail Produk (`detail-produk.html`)**: Pilihan varian (karpet/krat/mika), estimasi berat timbangan digital, spesifikasi kandang, dan ulasan pembeli lokal.
- **Keranjang Belanja (`keranjang.html`)**: Manajemen kuantitas, kalkulasi diskon voucher lokal (`PETERNABANGZUL`), asuransi busa pengiriman.
- **Checkout & Pembayaran (`checkout.html`)**: Pilihan kecamatan Tanggamus (Gisting, Kota Agung, Talang Padang, Wonosobo), slot jadwal antar (pagi/sore), serta 3 metode pembayaran (**COD / Bayar di Tempat**, **QRIS Bebas Biaya**, dan **Transfer BRI**).
- **Masuk & Daftar (`login.html`)**: Registrasi pembeli baru berdasarkan wilayah dan verifikasi cepat via WhatsApp Bot.

### 2. Penjual (Bang Zul Dashboard)
- **Dashboard Operasional (`dashboard.html`)**: KPI omzet harian, input cepat panen kandang subuh, grafik tren harga 7 hari, dan tabel pesanan masuk real-time.
- **Manajemen Inventaris Stok (`produk-stok.html`)**: Master data produk, peringatan stok kritis (*Critical Stock Alert*), dan modal formulir tambah varian baru.
- **Laporan Penjualan & Analisis Omzet (`laporan.html`)**: Grafik tren penjualan 30 hari, proporsi komoditas terlaris, rasio metode bayar, dan distribusi omzet per kecamatan di Tanggamus.

### 3. Logistik & Admin
- **Portal Kurir Tanggamus (`kurir.html`)**: Antarmuka ramah layar sentuh untuk kurir motor, peta rute pengantaran, rekap penerimaan kas COD, dan tombol klaim telur pecah instan.
- **Panel Admin Pasar (`admin.html`)**: Pengawasan sentra pasar, verifikasi transaksi, manajemen kuota mitra warung, dan matriks tarif wilayah.

---

## 🚀 Cara Menjalankan

### Cara 1: Buka Langsung (Offline)
Cukup buka folder proyek dan **klik 2x pada file `index.html`** di browser apa pun (Google Chrome, Microsoft Edge, Mozilla Firefox).

### Cara 2: Menjalankan Server Lokal
1. **Klik 2x file `start-web.bat`** (Windows), atau
2. Jalankan perintah terminal:
   ```bash
   node server.js
   ```
3. Buka browser pada alamat:
   ```
   http://localhost:3000/
   ```

---

## 📂 Struktur File

```text
├── index.html           # Beranda Utama Toko
├── katalog.html         # Katalog Produk Lengkap & Filter
├── katalog-cepat.html   # Belanja Cepat Bento + Sticky Cart
├── detail-produk.html   # Halaman Rincian Produk Telur
├── keranjang.html       # Keranjang Belanja & Kalkulator
├── checkout.html        # Checkout Alamat & Pembayaran Tanggamus
├── login.html           # Autentikasi Pembeli & Peternak
├── dashboard.html       # Dashboard Penjual (Bang Zul)
├── produk-stok.html     # Manajemen Stok & Tambah Produk
├── laporan.html         # Laporan Omzet & Grafik Penjualan
├── kurir.html           # Portal Kurir Tanggamus & Klaim Pecah
├── admin.html           # Panel Admin Pasar Telur
├── server.js            # Node.js Static Server
├── start-web.bat        # Shortcut Launcher Server Lokal
├── PRD_Bang_Zul_Egg_Market.md
└── Desain_UI_UX_Bang_Zul_Egg_Market.md
```

---

## 🛠️ Teknologi
- **HTML5 & Vanilla JavaScript**
- **Tailwind CSS (CDN)**
- **Google Fonts (Plus Jakarta Sans & Inter)**
- **Material Symbols Outlined**
- **Node.js (Lightweight Built-in HTTP Server)**

---
*Dibuat untuk digitalisasi agrikultur dan perdagangan lokal Kabupaten Tanggamus, Lampung.*
