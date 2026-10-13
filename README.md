# OtoPartID (Tailwind CSS)

Katalog dan pembanding harga sparepart kendaraan (motor dan mobil). Pengguna dapat melihat daftar komponen, membandingkan harga di beberapa marketplace, dan menambahkan data sparepart baru.

Tahap ini: kerangka tampilan (frontend skeleton) memakai **Tailwind CSS**, belum terhubung ke backend/database.

## Halaman
| File | Isi |
|---|---|
| `index.html` | Dashboard dengan layout grid (kartu ringkasan, tabel terbaru, ringkasan kategori) |
| `daftar.html` | Tabel daftar sparepart |
| `form.html` | Form tambah data sparepart |
| `detail.html` | Detail produk dan perbandingan harga marketplace |

Navbar responsif (collapse menjadi tombol menu di layar kecil) ada di semua halaman.

## Cara menjalankan
Buka `index.html` di browser. Tailwind dimuat lewat CDN (Play CDN) untuk keperluan tugas, jadi perlu koneksi internet. Untuk produksi sebaiknya memakai build Tailwind CLI.

## Alasan memilih Tailwind CSS
Tampilan OtoPartID (kartu harga, badge status Termurah, tabel perbandingan marketplace) cenderung spesifik, dan Tailwind memberi kendali penuh lewat utility class tanpa perlu menimpa gaya bawaan seperti di framework berbasis komponen. Utility `grid`, `flex`, dan prefix responsif (`md:`, `lg:`) membuat layout dashboard mudah disesuaikan per ukuran layar. Cocok bila proyek akhir memakai stack berbasis komponen seperti React, karena gaya ditulis langsung di markup.

## Screenshot
Simpan di `docs/screenshots/`.

| Halaman | Desktop | Mobile |
|---|---|---|
| Dashboard | ![](docs/screenshots/dashboard-desktop.png) | ![](docs/screenshots/dashboard-mobile.png) |
| Daftar | ![](docs/screenshots/daftar-desktop.png) | ![](docs/screenshots/daftar-mobile.png) |
| Form | ![](docs/screenshots/form-desktop.png) | ![](docs/screenshots/form-mobile.png) |
| Detail | ![](docs/screenshots/detail-desktop.png) | ![](docs/screenshots/detail-mobile.png) |

## Identitas
Muhammad Fauzan Bahri - Tugas Pemrograman Web
