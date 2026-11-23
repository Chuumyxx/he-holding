# Cek Aktual — Stok HE Hatchery Papua

Aplikasi web mandiri untuk menghitung stok fisik HE dan CSR serta membandingkannya dengan angka stok data.

## Menjalankan
Buka `index.html` langsung di browser, atau publikasikan folder ini melalui GitHub Pages.

## Fitur
- Kalkulator HE: Keranjang 210/180, Setter Tray 42/36.
- Kalkulator CSR: Keranjang 210/180, Tray kertas 150.
- Hitungan fisik dipisahkan menurut asal HE dan CSR.
- Perbandingan Stok HE, Stok CSR, dan Stok HE + CSR.
- Preview, laporan teks WhatsApp, ekspor CSV yang dapat dibuka di Excel, dan ekspor gambar SVG.
- Penyimpanan hitungan fisik pada localStorage browser.

## Aturan hitung
- Keranjang 210 = 210 butir; kalkulator juga menerima tambahan Tray 42 dan eceran.
- Keranjang 180 = 180 butir; kalkulator juga menerima tambahan Tray 36 dan eceran.
- Setter Tray 42: (R + L) × 168 + eceran.
- Setter Tray 36: (R + L) × 144 + eceran.
- Tray kertas 150: ikat × 150 + tray × 30 + eceran.
- Selisih = stok aktual − stok data.

## Catatan penting
Aplikasi ini dibuat mandiri berdasarkan spesifikasi yang diberikan, bukan hasil ekstraksi dari `Index.html` asli karena file sumber aplikasi utama belum diunggah. Karena itu, ini merupakan implementasi standalone awal. Data `localStorage` hanya tersimpan di browser/perangkat yang sama dan tidak sinkron antarperangkat. Tombol Gambar menghasilkan file SVG; tombol Excel menghasilkan CSV kompatibel dengan Excel.

## GitHub Pages
1. Buat repository GitHub, lalu unggah keempat file ini.
2. Buka **Settings → Pages**.
3. Pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu Save.
