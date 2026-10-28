# MAJUMI — Futuristic Pitching Website

Website landing page MAJUMI berbahasa Indonesia, bergaya **dark futuristic / AI business**, responsif, dan menggunakan satu berkas `index.html` tanpa dependensi build.

## Cara melihat

Buka `index.html` di browser desktop atau smartphone. Dashboard memiliki empat tab demo, kontrol periode simulasi, interaksi persetujuan draft, dan simulasi delegasi AI Orchestrator.

## Publikasi dari GitHub ke Vercel

1. Buat repository GitHub, misalnya `majumi-website`.
2. Upload `index.html` dan `README.md` ke root repository.
3. Masuk Vercel → Add New Project → Import dari GitHub.
4. Framework Preset: **Other**, Root Directory: `./`, tanpa build command. Atur output sebagai direktori root bila diperlukan.
5. Deploy. Setelah terhubung, commit GitHub berikutnya otomatis memicu deployment.

## Catatan penting tentang klaim dan fungsionalitas

Website ini **prototype pitching dengan interaksi lokal**. Angka dashboard, tabel kompetitor, dan hasil simulasi adalah data fiktif. UI disiapkan seperti platform SaaS premium, **bukan klaim backend MAJUMI sudah beroperasi**.

- Sales Intelligence, Competitor Radar, Growth Strategist adalah **Target MVP**.
- Campaign Agent, Customer Intelligence, dan Experiment Evaluation adalah **Roadmap**.
- Formulir saat ini **menyalin pesan**, tidak menyimpan atau mengirim lead ke server.
- Rencana harga Starter/Growth/Scale adalah **hipotesis**, belum paket aktif.
- Aktivitas "Approve" hanya mengubah status simulasi, bukan menerbitkan kampanye.
- Sebelum membuka layanan berbayar: selesaikan Supabase auth/RLS, lead capture yang aman, kebijakan privasi, integrasi resmi, serta verifikasi kualitas output.

## Penyesuaian

- Warna dan gaya: CSS `:root`.
- Copywriting, CTA, harga, FAQ: konten HTML.
- Grafis interaktif: JS `sales`, `updateGraph`, dan penanganan tombol demo.
- Form pilot: `lead-form` perlu backend/CRM dan pemberitahuan privasi sebelum benar-benar menerima data.

Terinspirasi oleh pola storytelling landing page SaaS premium. Seluruh implementasi dan materi brand MAJUMI ditulis ulang khusus untuk proyek ini.
