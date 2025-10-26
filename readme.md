# 💖 Album Cinta - Interactive Flipbook with Music

Sebuah album digital interaktif bertema cinta dengan efek **buku 3D**, **musik latar**, dan **animasi romantis**.  
Proyek ini dibuat menggunakan **HTML**, **CSS**, dan **JavaScript** murni tanpa framework — ringan, cantik, dan cocok untuk hadiah digital atau galeri kenangan pribadi.

## 🌸 Tampilan Umum

📘 Album ini menampilkan halaman-halaman yang bisa dibalik seperti buku sungguhan, lengkap dengan:
- Efek bayangan realistis.
- Sparkle (kilau bintang kecil) di cover.
- Animasi bintang jatuh di seluruh layar.
- Musik romantis yang sinkron dengan perpindahan halaman.
- Kontrol manual dan autoplay.

## 🪶 Fitur Utama

✨ **3D Flipbook Animation**  
Halaman bergerak seperti buku nyata dengan efek bayangan dan kedalaman perspektif.

🎵 **Music Panel**  
Terdapat pemutar musik lengkap dengan:
- Tombol Play / Pause
- Progress bar interaktif (dapat diklik & digeser)
- Penunjuk waktu berjalan & total durasi
- Nama file lagu yang sedang diputar

🕊️ **Autoplay Mode**  
Album dapat berjalan otomatis dengan kecepatan yang dapat diatur di file `script.js`.

🌠 **Efek Visual Tambahan**
- Sparkles di cover depan dan belakang.
- Bintang jatuh (shooting stars) yang terus bergerak acak.
- Rotasi ringan di tiap halaman untuk kesan alami.

## 📁 Struktur Folder

project-root/
├── index.html # Halaman utama album
├── css/
│ └── style.css # Gaya visual, efek, dan animasi
├── js/
│ └── script.js # Logika interaksi, musik, dan efek bintang
├── images/
│ ├── photo1.webp
│ ├── photo2.jpg
│ ├── photo3.jpg
│ ├── photo4.jpg
│ └── emote/ # Folder berisi emotikon PNG/GIF
└── music/
└── Alamak-rizkyfebian.mp3


---

## 🚀 Cara Menjalankan Proyek

1. Pastikan struktur folder seperti di atas.
2. Buka file **`index.html`** menggunakan browser (Chrome, Edge, Firefox, Safari).
3. Tunggu halaman termuat, lalu:
   - Klik **▶️ Play Album** untuk memulai otomatis.
   - Gunakan **← Sebelumnya** dan **Selanjutnya →** untuk navigasi manual.
4. Musik akan otomatis diputar bersamaan dengan halaman berganti secara halus.

> 💡 Jika musik tidak langsung berjalan, klik tombol “▶️” di panel musik — beberapa browser memblokir autoplay dengan suara.

### ⏱️ Durasi Tiap Halaman

Di file `js/script.js`, kamu bisa mengatur waktu tampil tiap halaman (dalam milidetik):

```js
const PAGE_DURATIONS = {
  0: 3000,  // Cover
  1: 3870,
  2: 6000,
  3: 500,
  4: 5000,
  5: 6000   // Back cover
};

Musik Latar

- **Lokasi** : `music/Alamak-rizkyfebian.mp3`
- **Format** : `.mp3`
- **Pembuat**: Rizky Febian 
- **Lisensi**: Gratis untuk penggunaan pribadi dan komersial
