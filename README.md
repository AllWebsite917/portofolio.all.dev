# Portofolio 3D card

## Menjalankan
    npm install
    npm run dev
Buka http://localhost:3000

## Yang diubah
- Semua teks, proyek, sertifikat, tech stack, kontak: `data/profile.ts`
- Foto bagian About: taruh di `public/`, isi `photo` di `data/profile.ts`
- Gambar proyek / sertifikat: `public/projects/` dan `public/certs/`
- Tali kartu (tulisan): `public/assets/bandd.png`
- Wajah kartu: `public/assets/kartu.glb` (edit di Blender)
- Ikon tab: `app/favicon.ico`
- Warna: `tailwind.config.ts` dan `app/globals.css`
- Pengaturan 3D: bagian atas `components/band/App.js`
