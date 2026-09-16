# TPQ Miftahul Huda

Website profil Taman Pendidikan Al-Qur'an Miftahul Huda — Perumahan Taman Cherry, Luwung, Mundu, Cirebon.

Static site (HTML + CSS), siap deploy ke Vercel.

## Jalankan lokal

Buka `index.html` di browser, atau:

```bash
npx serve .
```

## Deploy ke Vercel

1. Push repo ini ke GitHub.
2. Buka https://vercel.com/new → Import `TPQ-Miftahul-Huda`.
3. Framework Preset: **Other**. Build Command: kosong. Output Directory: `.` (default).
4. Deploy.

## Struktur

- `index.html` — halaman utama
- `style.css` — styling
- `*.jpg / *.jpeg` — foto pengajar & kegiatan
- `vercel.json` — konfigurasi Vercel (cleanUrls + cache header)
