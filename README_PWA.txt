# CV Online Indira - PWA Basic

Project ini sudah ditambahkan fitur PWA Basic:

1. `manifest.json` untuk identitas web app.
2. `sw.js` sebagai service worker dasar.
3. Tag PWA di `<head>` pada `index.html`.
4. Registrasi service worker sebelum `</body>`.
5. Folder `icons/` berisi icon 192x192, 512x512, dan maskable.

## Cara deploy ulang ke Vercel

1. Upload semua isi folder ini ke repository GitHub.
2. Pastikan file utama bernama `index.html`.
3. Deploy ulang di Vercel.
4. Buka link Vercel di Chrome Android.
5. Pilih menu titik tiga > Add to Home Screen / Install App.
6. Buka dari ikon di Home Screen. Jika tampil tanpa address bar, PWA Basic berhasil.

## Catatan

Kalau sebelumnya file utama kamu bernama `index(1).html`, di paket ini sudah saya ubah menjadi `index.html` agar langsung terbaca oleh Vercel.
