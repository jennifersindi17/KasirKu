# Kasir Duta Graha 🎀 — Kasir Sederhana

Aplikasi kasir ringan berbasis web (single-file HTML) — tanpa backend, tanpa instalasi.

## 🔗 Akses

**Live:** https://jennifersindi17.github.io/KasirKu/

## ✨ Fitur

- **Kasir** — katalog produk dengan pencarian & filter kategori, keranjang belanja, hitung kembalian otomatis, alokasi stok per gudang
- **Produk** — tambah/ubah/hapus produk, harga, stok awal, kategori
- **Gudang** — kelola lokasi gudang & lihat matriks stok per produk per gudang
- **Stock Opname** — cocokkan stok sistem vs fisik, riwayat opname dengan detail selisih
- **Laporan** — dashboard pendapatan (harian/bulanan/tahunan), grafik tren, filter rentang tanggal, export ke Excel (3 sheet)
- **Cetak Struk** — pratinjau & cetak struk thermal, kirim struk via WhatsApp ke pelanggan

## 💾 Data

Semua data (produk, transaksi, gudang, riwayat opname, nama kasir) tersimpan **otomatis di localStorage browser** — tidak ada server. Catatan:

- Data tersimpan per perangkat/browser — buka di perangkat lain = data terpisah.
- **Backup:** export laporan ke Excel secara rutin, atau salin data via localStorage browser.

## 🛠 Cara menjalankan lokal

Buka `index.html` langsung di browser, atau jalankan server sederhana:

```bash
cd KasirKu
python3 -m http.server 8080
# buka http://localhost:8080
```

## 🏗 Struktur

- `index.html` — aplikasi lengkap (HTML + CSS + JS, single-file)
- Library eksternal via CDN: SheetJS (export Excel), Chart.js (grafik), Google Fonts

Dibuat dengan 💖 untuk usaha kecil.
