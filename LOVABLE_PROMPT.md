# Prompt untuk Lovable

Kembangkan repository ini menjadi portal resmi Bidang Pengembangan ASN pada BKD Provinsi Banten dengan tetap mempertahankan identitas visual navy, putih, dan aksen emas yang sudah ada.

Prioritas:
1. Pertahankan tampilan modern, rapi, aksesibel, dan responsif untuk desktop/tablet/ponsel.
2. Jadikan seluruh konten berita, publikasi, layanan, kontak, dan profil dapat dikelola dari dashboard admin.
3. Hubungkan aplikasi dengan Supabase untuk database dan autentikasi admin. Jangan membuat kredensial admin hard-coded.
4. Buat tabel `news`, `publications`, `services`, `service_requests`, dan `profiles` dengan tipe data yang sesuai.
5. Aktifkan Row Level Security. Pengunjung umum hanya boleh membaca konten yang berstatus published/active. Hanya admin terautentikasi yang boleh membuat, mengubah, atau menghapus konten.
6. Formulir layanan harus menyimpan permohonan ke Supabase, membuat nomor referensi, menampilkan konfirmasi, dan tidak mengklaim pengajuan resmi sebelum alur operasional BKD disetujui.
7. Tambahkan halaman admin terlindungi untuk mengelola berita, publikasi, layanan, dan melihat permohonan. Jangan membuka data permohonan kepada publik.
8. Tambahkan pencarian, filter, validasi form, status loading/error/success, dan empty states.
9. Tambahkan halaman detail berita dan halaman detail layanan.
10. Tambahkan halaman kebijakan privasi dan pemberitahuan pemrosesan data.
11. Gunakan konten contoh yang diberi label draft sampai diverifikasi. Jangan mengarang regulasi, persyaratan, jadwal, statistik, atau berita aktual.
12. Pertahankan semua tautan eksternal resmi yang valid dan gunakan `target="_blank"` dengan `rel="noreferrer"`.

Sebelum mengubah skema atau menghapus fitur, jelaskan rencana singkat. Setelah implementasi, jalankan pemeriksaan build dan perbaiki error TypeScript.
