# Portal Bidang Pengembangan ASN — BKD Provinsi Banten

Starter website berbasis React + TypeScript + Vite + Tailwind CSS, disiapkan agar dapat diimpor ke GitHub lalu diedit menggunakan Lovable.

## Fitur yang tersedia
- Landing page profil Bidang Pengembangan ASN
- Navigasi responsif untuk desktop dan ponsel
- Kartu layanan dengan filter kategori dan modal informasi
- Formulir minat layanan (simulasi lokal menggunakan localStorage)
- Pencarian konten layanan, berita, dan publikasi
- Bagian berita dan publikasi dengan tautan ke kanal resmi
- Kontak dan tautan resmi BKD

## Menjalankan secara lokal
Memerlukan Node.js 20+.

```bash
npm install
npm run dev
```

Untuk build produksi:

```bash
npm run build
npm run preview
```

## Mengedit melalui Lovable
1. Ekstrak ZIP ini.
2. Buat repository baru di GitHub dan unggah seluruh isi folder project (bukan folder ZIP-nya).
3. Masuk ke Lovable, pilih opsi untuk mengimpor/connect repository GitHub, lalu pilih repository tersebut.
4. Setelah project terbuka, gunakan prompt pengembangan yang disediakan pada `LOVABLE_PROMPT.md`.
5. Setiap perubahan yang disetujui dapat disinkronkan melalui integrasi GitHub Lovable.

## Penting sebelum dipublikasikan
- Ini adalah frontend siap dikembangkan, bukan sistem backend produksi.
- Formulir layanan saat ini hanya menyimpan simulasi di browser pengguna (`localStorage`). Data tidak dikirim ke BKD.
- Belum ada autentikasi admin, CMS, database, tracking pengajuan, atau notifikasi email.
- Berita, persyaratan layanan, kontak, dan tautan harus diverifikasi oleh pejabat/pengelola konten BKD sebelum publikasi.
- Tambahkan logo resmi dan aset foto resmi yang telah memperoleh izin.
- Untuk layanan online sungguhan, hubungkan Supabase melalui Lovable dan buat kebijakan akses/RLS, validasi server, serta persetujuan pengelolaan data pribadi.
- Hindari mengumpulkan data pribadi sebelum ada dasar pemrosesan, pemberitahuan privasi, dan pengamanan yang sesuai.

## Struktur
- `src/App.tsx`: halaman, komponen UI, interaksi
- `src/data.ts`: konten berita, layanan, publikasi (mudah diedit)
- `src/index.css`: gaya visual
- `index.html`: metadata halaman
