# Implementation Plan

## Prinsip pelaksanaan
Kerjakan per fase. Setelah setiap fase, tampilkan hasil dan ringkasan perubahan, lalu berhenti untuk meminta persetujuan eksplisit sebelum melanjutkan.

## Phase 1 — SOT dan persetujuan
**Status:** dokumen perancangan disiapkan dalam paket ini.
- PRD, UI-GUIDELINE, IMPLEMENTATION_PLAN.
- Konfirmasi batasan: front-end saja, data dummy, React + Vite, Node.js sebagai runtime.
- **Gate:** persetujuan pengguna sebelum Phase 2.

## Phase 2 — Fondasi UI
- Inisialisasi React + Vite.
- Siapkan struktur folder, routing, design tokens, layout responsif, dan data dummy.
- Bangun login demo dan navigasi.
- Uji build dan tampilkan preview.
- **Gate:** minta persetujuan sebelum Phase 3.

## Phase 3 — Fitur inti
- Dashboard, Data Siswa, Data Guru, Kelompok Kelas.
- Tahun ajaran/semester dan interaksi CRUD lokal.
- **Gate:** minta persetujuan sebelum Phase 4.

## Phase 4 — Absensi dan rekap
- Absensi harian, pencarian/filter, rekapitulasi, kalkulasi persentase.
- Uji alur tanggal, kelompok, dan status absensi.
- **Gate:** minta persetujuan sebelum Phase 5.

## Phase 5 — Narasi dan laporan
- Form narasi perkembangan.
- Pratinjau laporan dan ekspor PDF sisi klien jika disetujui dan sesuai dependensi.
- Empty state, validasi ringan, aksesibilitas.
- **Gate:** minta persetujuan sebelum Phase 6.

## Phase 6 — QA dan paket final
- Uji navigasi, alur utama, responsif, dan build produksi.
- Perbaiki error yang ditemukan.
- Dokumentasikan cara instalasi dan penggunaan.
- Buat ZIP proyek final yang dapat diekstrak.

## Struktur target (rencana)
```text
src/
  app/
  components/
  layouts/
  pages/
  data/
  hooks/
  utils/
  styles/
public/
AGENTS.md
PRD.md
UI-GUIDELINE.md
IMPLEMENTATION_PLAN.md
PROMPT_EXECUTION.md
```

## Definition of Done
- Semua fitur dalam lingkup memiliki UI yang dapat dijelajahi.
- Interaksi prototipe menggunakan data dummy lokal.
- Tidak ada klaim backend/auth produksi.
- Build berhasil dan README menjelaskan langkah menjalankan aplikasi.
- ZIP final berisi source project dan dokumen yang disepakati.
