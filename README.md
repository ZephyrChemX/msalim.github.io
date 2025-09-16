# Portfolio: Muhammad Salim

Website statis (Tailwind CDN) siap deploy ke GitHub Pages.

## Struktur
- `index.html` — landing + portfolio + kontak
- `blog.html` — daftar artikel sederhana
- `shop.html` — kartu layanan digital
- `404.html` — halaman error
- `assets/favicon.svg`

## Cara Pakai (GitHub Pages)
1. Buat repo publik bernama `<username>.github.io` atau repo apa saja dengan Pages.
2. Upload semua file ini ke branch `main` (root).
3. Aktifkan **Settings → Pages → Deploy from a branch (main / root)**.

## Ubah Link Sosial & Kontak
- Cari bagian `social_row()` (HTML sudah di-inline) di `index.html` dan ganti URL:
  - YouTube, Instagram, X/Twitter, Telegram, Bluesky, GitHub, LinkedIn, Email.
- Ubah nomor WhatsApp di tautan `wa.me/` (format internasional tanpa 0, contoh `6285...`). Saat ini: `6285156676715`.

## Kustomisasi
- Warna dan font via Tailwind CDN di tag `<script src="https://cdn.tailwindcss.com"></script>`.
- Tambah postingan: duplikasi blok `<article>` di `blog.html`.
- Tambah produk: duplikasi kartu di `shop.html`.

## Lisensi
Bebas dipakai pribadi. Icon brand adalah milik masing-masing pemegang merek.
