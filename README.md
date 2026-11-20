<div align="center">
<img src="assets/banner.svg" alt="Banner pixel art" width="100%">
# NAMA-PROYEK-KAMU
 
**Satu kalimat yang menjelaskan proyek ini, ditulis untuk orang yang baru pertama kali melihatnya.**
 
![Status](https://img.shields.io/badge/STATUS-LEVEL_1-ffd23f?style=for-the-badge&labelColor=1b1b2f)
![Versi](https://img.shields.io/badge/VERSI-0.1.0-2ec4b6?style=for-the-badge&labelColor=1b1b2f)
![Lisensi](https://img.shields.io/badge/LISENSI-MIT-3a86ff?style=for-the-badge&labelColor=1b1b2f)
![PRs](https://img.shields.io/badge/PRs-WELCOME-e63946?style=for-the-badge&labelColor=1b1b2f)
 
[Main Game](https://USERNAME.github.io/NAMA-REPO/game/) · [Demo](https://USERNAME.github.io/NAMA-REPO/) · [Laporkan Bug](https://github.com/USERNAME/NAMA-REPO/issues) · [Request Fitur](https://github.com/USERNAME/NAMA-REPO/issues)
 
</div>
---
 
## Main Game Mini
 
Istirahat sebentar sebelum baca dokumentasi. Game platformer pixel ada di folder [`game/`](game/index.html), jalan langsung di browser tanpa instalasi.
 
| Tombol | Aksi |
|---|---|
| Panah kiri / kanan atau `A` / `D` | Jalan |
| Spasi atau panah atas | Lompat (tahan lebih lama untuk lompat lebih tinggi) |
| Injak slime | Kalahkan musuh (+100) |
| Ambil koin | +10 |
| Capai bendera | Menang |
 
Di HP, tombol layar muncul otomatis.
 
> GitHub tidak menjalankan JavaScript di dalam README. Karena itu game di-host lewat GitHub Pages dan di-link dari sini. Lihat bagian [Aktifkan GitHub Pages](#aktifkan-github-pages).
 
---
 
## Tentang Proyek
 
Jelaskan di sini:
 
- Masalah apa yang diselesaikan proyek ini
- Siapa yang akan memakainya
- Apa yang membedakannya dari alternatif lain
### Fitur
 
- [x] Fitur yang sudah jadi
- [x] Fitur lain yang sudah jadi
- [ ] Fitur yang sedang dikerjakan
### Teknologi
 
![HTML5](https://img.shields.io/badge/HTML5-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572b6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
 
Ganti atau tambah badge sesuai stack kamu di [shields.io](https://shields.io).
 
---
 
## Tampilan
 
<!-- Taruh screenshot di folder assets/ lalu ganti nama file di bawah -->
<div align="center">
  <img src="assets/screenshot.png" alt="Screenshot aplikasi" width="80%">
</div>
---
 
## Mulai Cepat
 
### Prasyarat
 
- Node.js 18 atau lebih baru (hapus jika tidak dipakai)
- Git
### Instalasi
 
```bash
# 1. Clone repositori
git clone https://github.com/USERNAME/NAMA-REPO.git
 
# 2. Masuk ke folder proyek
cd NAMA-REPO
 
# 3. Pasang dependensi
npm install
 
# 4. Jalankan
npm run dev
```
 
### Contoh Penggunaan
 
```js
// Tunjukkan contoh kode paling sederhana yang berhasil dijalankan
import { halo } from './src/index.js';
 
halo('dunia');
```
 
---
 
## Struktur Folder
 
```text
NAMA-REPO/
├── assets/
│   └── banner.svg        # banner animasi di bagian atas README
├── game/
│   └── index.html        # mini game, satu file
├── src/                  # kode utama proyek
├── README.md
└── LICENSE
```
 
---
 
## Aktifkan GitHub Pages
 
Supaya game bisa dimainkan lewat link:
 
1. Buka repositori di GitHub, lalu **Settings → Pages**.
2. Di **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu satu sampai dua menit. Game bisa dibuka di `https://USERNAME.github.io/NAMA-REPO/game/`.
5. Ganti semua `USERNAME` dan `NAMA-REPO` di README ini dengan milik kamu.
---
 
## Kustomisasi Game
 
Semua pengaturan level ada di bagian `LEVEL` pada `game/index.html`:
 
| Variabel | Fungsi |
|---|---|
| `gaps` | Posisi lubang di tanah, format `[kolomAwal, kolomAkhir]` |
| `plats` | Platform melayang, format `[kolomAwal, kolomAkhir, baris]` |
| `enemyCols` | Kolom tempat slime muncul |
| `HERO`, `SLIME` | Sprite karakter, satu huruf per piksel, warna ada di `PAL` |
 
Ingin karakter sendiri? Ubah teks pada `HERO` dan `PAL`, simpan, lalu refresh browser.
 
---
 
## Roadmap
 
- [ ] Tambah level 2
- [ ] Tambah musik dan efek suara 8-bit
- [ ] Papan skor tertinggi
Lihat [issues](https://github.com/USERNAME/NAMA-REPO/issues) untuk daftar lengkap fitur yang diusulkan.
 
---
 
## Kontribusi
 
Kontribusi sangat diterima.
 
1. Fork repositori ini
2. Buat branch fitur: `git checkout -b fitur/nama-fitur`
3. Commit perubahan: `git commit -m "Tambah nama-fitur"`
4. Push ke branch: `git push origin fitur/nama-fitur`
5. Buka Pull Request
---
 
## Lisensi
 
Dirilis dengan lisensi MIT. Lihat [`LICENSE`](LICENSE) untuk detailnya.
 
## Kontak
 
**Nama Kamu** · [@USERNAME](https://github.com/USERNAME) · email@contoh.com
 
<div align="center">
**GAME OVER? Beri bintang di atas untuk lanjut main.**
 
</div>
 
