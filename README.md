# HE HOLDING — Cek Aktual (Paket Lengkap)

Paket mandiri untuk GitHub Pages. Tidak terhubung ke Spreadsheet atau database.
Data aplikasi disimpan lokal pada browser/perangkat yang digunakan.

## File
- `index.html` — halaman aplikasi, sudah terhubung ke manifest dan ikon.
- `style.css` — tampilan responsif.
- `script.js` — kalkulasi dan interaksi.
- `manifest.json` — nama aplikasi dan konfigurasi ikon.
- `icon-192.png`, `icon-512.png` — ikon aplikasi.
- `apple-touch-icon.png` — ikon perangkat Apple.
- `favicon-32.png`, `favicon-64.png` — ikon tab browser.

## Upload ke GitHub
1. Ekstrak ZIP ini.
2. Buka repository `he-holding`.
3. Unggah SEMUA file di dalam folder `he-holding` ke root repository, timpa file lama.
4. Commit changes.
5. Pastikan Settings → Pages memakai branch `main` dan folder `/ (root)`.

## Pasang ulang ikon di HP
1. Hapus shortcut lama dari layar utama.
2. Buka `https://chuumyxx.github.io/he-holding/` melalui Chrome.
3. Refresh halaman; bila perlu hapus cache situs.
4. Pilih menu Chrome → Tambahkan ke layar utama / Install app.

## Catatan
- Ikon baru sudah ditautkan dari `index.html`.
- GitHub Pages harus selesai membangun sebelum perubahan terlihat.
- Browser/Android dapat menyimpan ikon lama dalam cache.
- Data lokal tidak otomatis tersinkron antarperangkat atau antar-browser.
