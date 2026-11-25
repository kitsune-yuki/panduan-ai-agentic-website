# Panduan AI Agentic: Website dari Nol sampai Production

Panduan belajar berbahasa Indonesia untuk pemula yang ingin membangun website sendiri dengan bantuan AI agentic — dari ide pertama sampai websitenya tayang di production.

Contoh proyek yang dipakai di sepanjang panduan ini: **Website KPI Perpajakan**.

## Untuk siapa panduan ini?

Untuk seseorang yang memulai dari hampir nol — misalnya pernah mencoba membuat website KPI, tetapi proyek itu tidak pernah selesai. Tidak perlu pengalaman ngoding sebelumnya. Yang dibutuhkan hanya kemauan mengikuti langkah kecil, satu per satu, dan berani mencoba (dan salah) di tengah jalan.

## Isi panduan

Panduan ini terdiri dari tiga halaman:

| File | Isi |
| --- | --- |
| `index.html` | Landing page + halaman baca utama: visi, misi, kata pengantar, daftar isi, ringkasan isi utama, dan cara memakai panduan ini. |
| `workflow.html` | Bagian 1 — Workflow AI Agentic: cara kerja AI agentic (loop Plan → Act → Observe → Iterate) dan 8 fase dari persiapan sampai maintenance, lengkap dengan bank prompt, peta alat, template brief, dan checklist sebelum production. |
| `dokumentasi.html` | Bagian 2 — Dokumen Pendukung: 14 dokumen untuk Website KPI Perpajakan, yaitu PRD, User Flow, ERD, Skema Database + SQL, Spesifikasi API, Arsitektur & Tech Stack, AGENTS.md, Implementation Plan, Roadmap, Product Backlog, Rencana Testing & UAT, Deploy, Devlog, dan Glosarium. |

## Cara memakai

1. Buka halaman utama dan baca kata pengantar serta visinya.
2. Ikuti workflow fase demi fase di `workflow.html`, mulai dari Fase 0 — Persiapan.
3. Sebelum dan selama membangun, isi dokumen pendukung di `dokumentasi.html` (mulai dari PRD dan ERD).
4. Deploy websitemu ke production, lalu rawat dan perbaiki terus.

## Membaca secara online

Setelah GitHub Pages diaktifkan, panduan ini bisa dibaca di:

**https://kitsune-yuki.github.io/panduan-ai-agentic-website/**

## Menjalankan secara lokal

Tidak perlu server atau build apa pun — ini situs statis. Cukup buka `index.html` di browser, atau jalankan server lokal sederhana dari folder ini:

```bash
python3 -m http.server 8000
```

lalu buka <http://localhost:8000>.

## Struktur repo

```
.
├── index.html        # Landing page + halaman baca utama
├── workflow.html     # Bagian 1 — Workflow AI Agentic
├── dokumentasi.html  # Bagian 2 — Dokumen Pendukung
├── README.md
├── LICENSE           # MIT
└── .nojekyll         # Menonaktifkan pemrosesan Jekyll di GitHub Pages
```

## Lisensi

Lisensi MIT — lihat file `LICENSE`. © 2026 Yumina / kitsune-yuki.
