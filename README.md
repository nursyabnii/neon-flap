# Neon Flap: Cyberpunk Edition 🕹️

Neon Flap adalah interpretasi modern dari game klasik "Flappy Bird" dengan estetika cyberpunk/neon yang futuristik. Dibangun sepenuhnya menggunakan HTML5 Canvas dan JavaScript murni tanpa dependensi eksternal.

## ✨ Fitur Utama

- Tema Neon Modern: Visual bergaya cyberpunk dengan efek glow (cahaya) dan partikel.
- Audio Prosedural (Offline): Suara efek (lompat, skor, tabrakan) dihasilkan secara real-time menggunakan Web Audio API. Tidak perlu men-download file MP3/WAV terpisah.
- Multi-Platform: Responsif dan dapat dimainkan dengan lancar di:
    - 💻 PC/Desktop (Mouse & Keyboard)
    - 📱 HP/Tablet (Layar Sentuh)
- Sistem Tingkat Kesulitan:
    - 🟢 Easy: Celah pipa lebar, kecepatan rendah.
    - 🟡 Medium: Celah standar, kecepatan sedang.
    - 🔴 Hard: Celah sempit, kecepatan tinggi.
- Penyimpanan Highscore: Skor tertinggi tersimpan otomatis di browser (Local Storage).
- Fitur Pause: Game dapat dijeda kapan saja.
- Optimasi Performa: Dirancang agar ringan dan tidak lag di perangkat dengan spesifikasi rendah.

## 🎮 Cara Bermain

Tujuan permainan adalah mengendalikan kotak neon ("burung") untuk melewati celah di antara pipa-pipa tanpa menabraknya.

Kontrol
| Perangkat| Aksi | Deskripsi |
| --- | --- | --- |
| PC (Keyboard) | Spasi atau Panah Atas | Melompat |
| PC (Keyboard) | P atau Esc | Pause / Jeda Game |
| PC (Mouse) | Klik Kiri | Melompat |
| Mobile (Touch) | Tap Layar | Melompat |
| UI | Tombol ` |  |

## 🚀 Cara Menjalankan Game

Game ini terdiri dari satu file tunggal (Single File HTML). Anda tidak perlu menginstal server atau aplikasi khusus.
1. Pastikan Anda memiliki file `index.html`.
2. Klik dua kali file `index.html` untuk membukanya di web browser favorit Anda (Chrome, Firefox, Safari, Edge, dll).
3. Game siap dimainkan!

## 🛠️ Teknologi yang Digunakan

- HTML5 Canvas: Untuk rendering grafis 2D yang cepat.
- Vanilla JavaScript (ES6+): Logika game, fisika, dan sistem partikel.
- Web Audio API: Sintesis suara efek secara langsung di browser.
- CSS3: Styling antarmuka pengguna (UI) dan font.
- Local Storage: Menyimpan data skor tertinggi pengguna.

## 📝 Catatan Pengembang

Jika Anda ingin memodifikasi game, semua logika terdapat di dalam tag `<script>` pada file HTML.
- Ubah variabel `this.settings` di dalam `class Game` untuk mengatur kecepatan atau gravitasi.
- Ubah warna di fungsi `draw()` untuk mengganti tema warna neon.
Dibuat dengan ❤️ dan sedikit kode JavaScript.