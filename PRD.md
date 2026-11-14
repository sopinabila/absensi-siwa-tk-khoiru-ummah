# PRD — Product Requirements Document

## 1. Ringkasan
Aplikasi web untuk membantu pengelolaan absensi harian siswa pada Tahfizh Plus Khoiru Ummah Tingkat TK Bogor Utara. Fase awal berupa prototipe front-end interaktif dengan data dummy.

## 2. Tujuan
- Memusatkan data siswa, guru, kelompok kelas, dan periode akademik.
- Memudahkan pencatatan serta pencarian absensi harian.
- Menampilkan rekap absensi dan narasi perkembangan secara ringkas.
- Menyediakan tampilan laporan yang siap dikembangkan ke PDF.

## 3. Pengguna dan hak akses
- **Admin:** mengelola data master, periode, akun demo, dan melihat seluruh laporan.
- **Guru:** melihat kelompok yang ditugaskan, mencatat absensi, serta mengisi narasi perkembangan.
- **Pimpinan/Kepala sekolah:** melihat dashboard dan rekap/laporan.
> Pada prototipe, peran hanya simulasi UI; bukan kontrol keamanan produksi.

## 4. Ruang lingkup fitur
1. **Login dan logout pengguna** — form login, validasi ringan, pilihan/role demo, logout.
2. **Login dan hak akses** — navigasi dan aksi disesuaikan dengan role demo.
3. **Dashboard** — ringkasan siswa, guru, hadir, izin/sakit/alpa, tren absensi dan aktivitas terbaru.
4. **Data Siswa** — daftar, detail ringkas, tambah/ubah/hapus data dummy, status aktif.
5. **Data Guru** — daftar dan pengelolaan data dummy guru.
6. **Kelompok Kelas** — kelompok A/B atau kelompok yang ditentukan sekolah, guru pendamping, jumlah siswa.
7. **Tahun Ajaran dan Semester** — memilih tahun ajaran/semester aktif.
8. **Absensi Harian** — pilih tanggal dan kelompok; status Hadir, Izin, Sakit, Alpa; simpan ke state lokal.
9. **Pencarian dan Filter** — pencarian kata kunci serta filter kelompok, status, tanggal, dan periode sesuai halaman.
10. **Rekapitulasi Absensi** — rekap per siswa/kelompok/periode, total dan persentase kehadiran.
11. **Narasi Perkembangan** — form catatan perkembangan siswa; bukan sistem penilaian klinis/diagnostik.
12. **Laporan PDF** — halaman pratinjau laporan dan titik integrasi ekspor PDF; kemampuan final ditetapkan pada fase implementasi.

## 5. Kebutuhan nonfungsional
- Responsif untuk desktop, tablet, dan ponsel.
- Bahasa UI Indonesia.
- Kontras warna dan fokus keyboard yang jelas.
- Komponen konsisten, status kosong/loading/error yang wajar.
- Data dummy tidak boleh disajikan sebagai data siswa nyata.
- Tidak menyimpan data permanen atau mengirim data ke server.

## 6. Kriteria penerimaan prototipe
- Pengguna dapat masuk/keluar dari sesi demo.
- Navigasi fitur utama dapat dibuka dan memiliki tampilan yang relevan.
- CRUD data master berfungsi pada state lokal selama sesi.
- Absensi dapat diubah dan direkap dari data dummy.
- Filter/pencarian menghasilkan perubahan daftar yang terlihat.
- Narasi dapat ditulis dan ditampilkan dalam sesi demo.
- Laporan memiliki pratinjau yang jelas dan label bila ekspor masih simulasi.
- Tidak ada tombol utama yang inert tanpa keterangan.

## 7. Di luar ruang lingkup
Backend Node.js/Express, database, autentikasi aman, reset kata sandi email, integrasi WhatsApp, impor data nyata, hosting, dan keamanan produksi.
