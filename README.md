# Sistem Informasi Absensi Siswa — TK Bogor Utara

Prototipe front-end untuk Tahfizh Plus Khoiru Ummah Tingkat TK Bogor Utara. Aplikasi dibuat dengan React + Vite dan memakai data ilustrasi lokal.

## Persyaratan

- Node.js 20.19+ (atau 22.12+)
- npm yang disertakan bersama Node.js

## Instalasi dan menjalankan

1. Ekstrak ZIP proyek.
2. Buka terminal pada folder hasil ekstrak (folder yang berisi `package.json`).
3. Pasang dependensi dari lockfile:

   ```bash
   npm ci
   ```

4. Jalankan server pengembangan:

   ```bash
   npm run dev
   ```

5. Buka alamat lokal yang ditampilkan Vite, biasanya `http://localhost:5173`.

Untuk memeriksa build produksi lokal:

```bash
npm run build
npm run preview
```

## Akses demo

Form masuk menyediakan email `admin@demo.sch.id` dan kata sandi `demo1234`. Pilih peran Admin, Guru, atau Pimpinan. Email dan kata sandi hanya validasi simulasi; tidak ada akun atau autentikasi sungguhan.

Menu demo mengikuti peran yang dipilih. Guru demo adalah Aisyah Rahmawati dan melihat kelompok yang ditugaskan kepadanya. Admin mengelola data master dan periode; Pimpinan melihat dashboard serta rekap/laporan. Pembatasan ini hanya untuk demonstrasi antarmuka, bukan keamanan produksi.

## Batasan prototipe

- Data siswa, guru, kelompok, absensi, narasi, dan perubahan lainnya bersifat ilustrasi. Perubahan hanya hidup di state selama sesi dan hilang setelah halaman dimuat ulang.
- Tidak ada backend, database, API, penyimpanan permanen, atau integrasi eksternal.
- Laporan dicetak melalui dialog cetak browser; pilih “Save as PDF / Simpan sebagai PDF” untuk menyimpan PDF di perangkat.
- Grafik dashboard merupakan ilustrasi, bukan rekam historis.
- Jangan gunakan data ini sebagai catatan resmi siswa.

## Dokumen acuan

`PRD.md`, `UI-GUIDELINE.md`, `IMPLEMENTATION_PLAN.md`, `AGENTS.md`, dan `PROMPT_EXECUTION.md` berisi kebutuhan, pedoman, rencana, serta kontrak kerja proyek.