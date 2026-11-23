HE HOLDING – PAKET IKON

Isi:
- icon-192.png dan icon-512.png: ikon PWA / layar utama
- apple-touch-icon.png: ikon iOS/iPadOS
- favicon-32.png dan favicon-64.png: favicon browser
- manifest.json: nama dan konfigurasi ikon aplikasi

CARA PASANG:
1. Unggah semua file PNG dan manifest.json ke folder root repository he-holding.
2. Tambahkan baris berikut di dalam bagian <head> pada index.html:

<link rel="manifest" href="./manifest.json">
<link rel="icon" type="image/png" sizes="32x32" href="./favicon-32.png">
<link rel="icon" type="image/png" sizes="64x64" href="./favicon-64.png">
<link rel="apple-touch-icon" href="./apple-touch-icon.png">
<meta name="theme-color" content="#0b663c">

3. Commit changes dan tunggu GitHub Pages diperbarui.
4. Hapus shortcut lama di HP, buka ulang situs, lalu pilih Tambahkan ke layar utama / Install app.

Catatan: Paket ini berisi aset ikon dan manifest. index.html tetap perlu ditambahkan baris tautan manifest di atas agar browser mengenali ikon aplikasi.
