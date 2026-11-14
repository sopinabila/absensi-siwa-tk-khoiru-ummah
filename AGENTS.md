# AGENTS.md — Kontrak Kerja Agen

## Misi
Membangun prototipe front-end Sistem Informasi Absensi Siswa berbasis web untuk Tahfizh Plus Khoiru Ummah Tingkat TK Bogor Utara sesuai PRD, UI-GUIDELINE, dan IMPLEMENTATION_PLAN.

## Sumber kebenaran
1. `PRD.md`
2. `UI-GUIDELINE.md`
3. `IMPLEMENTATION_PLAN.md`
Jika ada konflik, berhenti dan minta klarifikasi; jangan menebak ruang lingkup baru.

## Batasan wajib
- Gunakan React + Vite; Node.js hanya sebagai runtime/perkakas untuk fase front-end.
- Gunakan data dummy lokal. Jangan menghubungkan database, API eksternal, atau data nyata tanpa persetujuan.
- Jangan menambahkan fitur di luar PRD.
- Jangan mengubah nama institusi, identitas produk, atau palet brand tanpa persetujuan.
- Jangan mengklaim autentikasi atau hak akses sebagai keamanan produksi.
- Jangan membuat tahapan berikutnya sebelum persetujuan eksplisit pengguna.
- Hindari dependensi baru jika fitur dapat dibuat secara sederhana; jelaskan alasan bila perlu dependensi.
- Jangan meninggalkan tombol yang tampak berfungsi tetapi tidak memiliki aksi. Beri aksi demo atau label yang jujur.

## Alur kerja setiap fase
1. Baca dokumen SOT terkait.
2. Kerjakan hanya fase yang sedang disetujui.
3. Jalankan pemeriksaan yang relevan (mis. build/lint bila tersedia).
4. Ringkas file yang dibuat/diubah, hasil pemeriksaan, dan batasan yang masih ada.
5. Tampilkan preview yang dapat diperiksa.
6. Berhenti dan minta persetujuan sebelum fase berikutnya.

## Standar kualitas
- UI berbahasa Indonesia, responsif, dan konsisten.
- Gunakan komponen reusable dan penamaan yang jelas.
- Validasi input dasar dan konfirmasi aksi destruktif.
- Sediakan empty state, status feedback, serta label status selain warna.
- Pastikan data dummy diberi konteks demo.
- Perbarui README jika instruksi menjalankan proyek berubah.

## Larangan
- Jangan membuat backend, database, deployment, akun sungguhan, atau integrasi eksternal tanpa persetujuan.
- Jangan memasukkan kredensial, token, atau data pribadi nyata ke repository.
- Jangan menghapus file penting atau mengganti konfigurasi proyek tanpa alasan dan persetujuan jika berdampak luas.
