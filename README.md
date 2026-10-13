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
<img width="1454" height="726" alt="image" src="https://github.com/user-attachments/assets/ea802f35-0233-43ec-ba07-8e7a1e62e660" />
<img width="1475" height="763" alt="image" src="https://github.com/user-attachments/assets/e4162371-bc70-43af-a184-cc4a68513ec0" />
<img width="1475" height="805" alt="image" src="https://github.com/user-attachments/assets/3750c325-b92f-4dbc-b7ed-8efbf817e1ea" />
<img width="1481" height="785" alt="image" src="https://github.com/user-attachments/assets/121ed376-e99e-4344-90dd-3dfb9a4e607d" />



| Halaman | Desktop | Mobile |
|---|---|---|
| Dashboard | ![](docs/screenshots/dashboard-desktop.png) | ![](docs/screenshots/dashboard-mobile.png) |
| Daftar | ![](docs/screenshots/daftar-desktop.png) | ![](docs/screenshots/daftar-mobile.png) |
| Form | ![](docs/screenshots/form-desktop.png) | ![](docs/screenshots/form-mobile.png) |
| Detail | ![](docs/screenshots/detail-desktop.png) | ![](docs/screenshots/detail-mobile.png) |

## Identitas
Muhammad Fauzan Bahri - Tugas Pemrograman Web
