# Flappy Bombi - Sensor Jari 🚀🖐️

Game Flappy Bird interaktif berbasis sensor gerakan tangan menggunakan webcam, ditenagai oleh **MediaPipe Hands** dan **HTML5 Canvas**. Pemain mengendalikan karakter **Bombi** meluncur melewati rintangan pipa menggunakan gerakan jari tanpa perlu menyentuh keyboard atau mouse!

---

## 🌟 Fitur Utama

- **Kontrol Gerakan Tangan (Real-time Hand Tracking)**: Gerakkan jari telunjuk Anda naik dan turun di depan webcam untuk mengarahkan terbangnya Bombi.
- **Navigasi Menu Bebas Sentuh (Touchless UI)**:
  - **Dwell Auto-Click**: Cukup arahkan jari telunjuk ke tombol (*Main Lagi*, *Berhenti*, atau *Mulai Game*) selama 1 detik untuk memilih otomatis.
  - **Gesture Cubit (Pinch)**: Sentuhkan ujung jempol dan telunjuk untuk klik instan.
- **Karakter Bombi**: Menampilkan karakter Bombi dengan animasi kemiringan dan efek jetpack saat meluncur.
- **Efek Audio & Suara**: Umpan balik suara interaktif untuk poin, tabrakan, dan klik tombol.
- **Sistem Rekor Tertinggi (High Score)**: Skor terbaik tersimpan otomatis di penyimpanan lokal browser (*localStorage*).

---

## 🚀 Cara Menjalankan

1. Clone repositori ini:
   ```bash
   git clone https://github.com/chusni-moklet/game-bombiflap.git
   cd game-bombiflap
   ```
2. Buka proyek menggunakan local web server (seperti VS Code **Live Server**, Python HTTP server, atau ekstensi server lokal lainnya):
   ```bash
   # Menggunakan Python
   python3 -m http.server 5500
   ```
3. Buka browser di `http://127.0.0.1:5500`.
4. Izinkan akses webcam saat diminta.
5. Arahkan jari telunjuk Anda ke depan kamera dan selamat bermain!

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 Canvas & JavaScript (ES6+)**
- **Tailwind CSS**
- **Google MediaPipe Hands** (Deteksi pose tangan via WebGL & WebAssembly)
- **Web Audio API**
