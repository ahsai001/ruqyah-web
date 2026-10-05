# Ruqyah Syar'iyyah Interactive Web App

Aplikasi web interaktif islami untuk mendengarkan audio lantunan Ruqyah Syar'iyyah yang menenangkan, dilengkapi teks ayat Al-Qur'an (Arab, Latin, & Terjemahan), penanda waktu presisi, auto-scroll otomatis mengikuti bacaan, dan kontrol pemutaran multi-track.

🌐 **Live URL**: [https://ruqyah.ahsailabs.my.id](https://ruqyah.ahsailabs.my.id)  
🌐 **Jalur Alternatif**: [https://ahsailabs.my.id/ruqyah/](https://ahsailabs.my.id/ruqyah/)

## ✨ Fitur Utama

- **Audio Streaming Cepat & Ringan**: Format AAC M4A (~48.6 MB total untuk 5 sesi ruqyah) dengan dukungan HTTP 206 Partial Content (Range Requests / audio seeking).
- **Multi-Track Selection & Sequential Looping**:
  - Trek ruqyah dapat dipilih/dicentang sesuai kebutuhan.
  - Pemutaran berulang secara otomatis hanya pada trek-trek yang aktif dipilih.
- **Sinkronisasi Ayat & Terjemahan**:
  - Highlight ayat aktif secara *real-time* sesuai lantunan suara qari.
  - Tombol lompat langsung (`▶`) per ayat untuk mendengarkan bagian tertentu.
- **Auto-Scroll Pintar**:
  - Layar bergeser secara halus (*smooth scroll*) memusatkan ayat aktif tepat di tengah area pandang mata di smartphone maupun laptop.
  - Tombol kontrol toggle auto-scroll (ON / Manual).
- **Dukungan Media Session API**:
  - Judul audio, qari, cover art, dan kontrol pemutaran terintegrasi langsung di *lock screen* ponsel dan sistem audio bluetooth.
- **Tipografi Arab Nyaman**:
  - Menggunakan font *Amiri* dan *Scheherazade New* berharakat lengkap.
  - Tombol pengubah ukuran font Arab (`Aa`) dan toggle transliterasi Latin.
- **Panduan & Adab Mendengarkan Ruqyah**:
  - Accordion tips dan adab syar'i saat mendengarkan ruqyah mandiri.

## 🎧 Daftar Trek Audio Ruqyah

1. **Ruqyah 'Ain** (10:15) — QS. Al-Kahfi: 39, Al-Qalam: 51, Al-Falaq: 1-5, Doa Syifa HR. Muslim 2185.
2. **Ruqyah Penghancur Sihir** (10:20) — QS. Al-Furqan: 23, Al-Anfal: 11, An-Nahl: 26, At-Tawbah: 1, Al-An'am: 162-163.
3. **Ruqyah Sleep Paralysis / Ketindihan** (10:55) — QS. Az-Zukhruf: 13, Al-Jinn: 21-22, Al-Mu'minun: 97-98, An-Nahl: 99-100.
4. **Ruqyah Was-Was & Gelisah** (10:28) — QS. At-Tawbah: 51, Al-A'raf: 201, Al-Mu'minun: 97-98, An-Nas: 1-6.
5. **Ruqyah Jin Leluhur** (10:46) — QS. As-Saffat: 158, Al-An'am: 100 & 128, Saba': 40-41, Al-Jinn: 6, At-Tawbah: 1, Al-An'am: 162-163.

*Sumber Audio: Indra Permana (Cahaya Ruqyah Indonesia).*

## 🛠️ Teknologi

- **Frontend**: HTML5, Modern CSS3 (Glassmorphism, Mobile-First), Vanilla JavaScript (ES6+), Google Fonts.
- **Backend/Host**: Python 3 (`ThreadingHTTPServer`), Cloudflare Tunnel (`cloudflared`), Systemd.

---
© 2026 [Ahsailabs Studio](https://ahsailabs.my.id). Semoga menjadi wasilah ketenangan dan kesembuhan.
