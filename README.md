# MAJUMI — Website Pitching (Logo Infinity #13)

Website pitching MAJUMI dengan simbol infinity cyan–biru yang dipilih dari opsi 13. Slogan: **Saatnya Maju, Ubah Data Jadi Aksi.**

## GitHub dan Vercel
1. Ekstrak ZIP dan upload seluruh isi folder ini ke root repository GitHub `majumi-website`.
2. Di Vercel pilih Add New → Project → Import GitHub repository.
3. Framework Preset **Other**, Root Directory `./`, Build Command kosong, Output Directory `.` (untuk static HTML).
4. Deploy. Pada update berikutnya, commit perubahan melalui GitHub agar Vercel melakukan redeploy.

`index.html` adalah halaman HTML mandiri: logo dan favicon sudah ditanam langsung di dalam HTML agar preview tetap berfungsi jika dibuka terpisah. Versi logo individual ada di folder `assets` untuk pengembangan nanti.

## Status produk
Dashboard menggunakan data simulasi; website belum terhubung ke Supabase, n8n, Apify, dan Hermes. Form minat pilot hanya menyalin pesan; belum menyimpan pengajuan ke backend. Paket dan harga merupakan rancangan.

## Aset
- `assets/majumi-infinity-mark.png` — simbol infinity cyan-biru dari gambar logo yang dipilih, dengan latar transparan.
- `assets/favicon.png` — favicon untuk website.

Logo diekstraksi dari gambar referensi pilihan pengguna. Lakukan finalisasi berkas vector dan pemeriksaan merek sebelum pendaftaran atau produksi besar.
