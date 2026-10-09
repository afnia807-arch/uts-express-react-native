# Fullstack Express + React Native — CRUD Posts

Tugas UTS Individu IK300 Mobile Programming
Afni Alya Putri — 2401659 — Pendidikan Ilmu Komputer UPI

Aplikasi mobile untuk mengelola data posts (Create, Read, Update, Delete) beserta upload gambar.
Mengikuti kelas Fullstack JavaScript Developer dengan Express dan React Native di Santri Koding.

## Struktur Project
- `backend-express` — REST API dengan Express.js, Prisma, dan MySQL
- `LearnReactNative` — aplikasi Android dengan React Native, React Navigation, Axios, dan Image Picker

## Cara Menjalankan
1. Jalankan MySQL (XAMPP), lalu di folder `backend-express`: `npm install` lalu `node index.js`
2. Di folder `LearnReactNative`: `npm install`, buat file `.env` berisi `BACKEND_API_URL=http://10.0.2.2:3000`
3. Jalankan `npx react-native start`, lalu `npm run android`
