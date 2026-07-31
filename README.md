# Gulo Abang Kito — Bio UMKM

Landing page bio (gaya Linktree) untuk UMKM **Gulo Abang Kito**, produsen gula aren asli dari
Desa Talang Beringin, Kecamatan Pulau Panggung, Kabupaten Tanggamus, Provinsi Lampung.

Dibuat murni dengan **HTML5, CSS3, dan Vanilla JavaScript** — tanpa framework.

## Struktur File

```
index.html
style.css
script.js
assets/
  images/
    logo-placeholder.svg
    og-placeholder.svg
  icons/
    favicon.svg
README.md
```

## Fitur

- Kartu profil terpusat, mobile-first & responsif (HP, tablet, laptop, desktop)
- 4 tombol sosial animatif: Instagram, Facebook, Shopee, WhatsApp (ikon, teks, panah, ripple, glow)
- Dark mode toggle tersimpan di Local Storage (mengikuti preferensi sistem saat pertama kali)
- Animasi: fade in, slide up, floating logo, hover glow, ripple, smooth transition
- Tombol Back To Top, Copy Link, dan loading animation
- SEO: title, description, Open Graph, Twitter Card, favicon placeholder
- Aksesibilitas: HTML semantik, ARIA label, fokus keyboard, kontras warna baik
- Menghormati `prefers-reduced-motion`

## Palet Warna

| Nama          | Hex     |
| ------------- | ------- |
| Primary Brown | #6D4C41 |
| Cream         | #FFF8E7 |
| Palm Green    | #4CAF50 |
| Gold          | #D4AF37 |
| White         | #FFFFFF |

Font: **Poppins** (Google Fonts). Ikon: **Font Awesome 6 CDN**.

## Cara Menjalankan

Buka `index.html` langsung di browser, atau jalankan server statis sederhana:

```bash
python3 -m http.server 8000
```

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub, unggah seluruh isi folder ini ke root repository.
2. Buka **Settings → Pages**.
3. Source: **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`.
4. Simpan, lalu tunggu beberapa menit. URL akan tampil di halaman tersebut.
5. Tempelkan URL tersebut ke Bio Instagram.

## Kustomisasi

- Ganti tautan sosial pada `index.html` (atribut `href` tiap `.link-btn`).
- Ganti nomor WhatsApp pada tautan `https://wa.me/62...`.
- Ganti logo dengan mengganti file `assets/images/logo-placeholder.svg`.
- Warna dapat diubah pada variabel CSS di blok `:root` dalam `style.css`.

---

© 2026 Gulo Abang Kito — Program Kerja Individu PKPM, Institut Informatika dan Bisnis Darmajaya.
