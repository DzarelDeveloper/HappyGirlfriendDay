<div align="center">

# Happy Girlfriend Day

Website ucapan personal berbasis HTML dan CSS untuk menyampaikan pesan spesial melalui foto, musik, dan halaman interaktif yang sederhana.

[Live Demo](https://dzareldeveloper.github.io/HappyGirlfriendDay/) · [Report an Issue](https://github.com/DzarelDeveloper/HappyGirlfriendDay/issues)

</div>

## Tentang Proyek

**Happy Girlfriend Day** adalah website ucapan digital yang dapat dikustomisasi untuk seseorang yang spesial. Pengunjung akan melihat halaman pembuka berisi foto dan tombol navigasi, kemudian diarahkan ke halaman utama yang menampilkan kumpulan foto, pesan personal, musik latar, serta tombol untuk memberikan balasan.

Proyek ini dibuat sebagai website statis sehingga ringan, mudah dipelajari, dan dapat langsung dipublikasikan melalui GitHub Pages tanpa backend atau database.

## Fitur

- Halaman pembuka dengan foto dan tombol navigasi
- Halaman ucapan dengan tata letak berbasis grid
- Dukungan foto dan pesan yang dapat dipersonalisasi
- Musik latar menggunakan elemen audio HTML
- Tombol balasan yang dapat diarahkan ke WhatsApp
- Efek hover dan transisi sederhana
- Tampilan yang menyesuaikan ukuran layar perangkat

## Teknologi

- **HTML5** — struktur halaman, konten, dan audio
- **CSS3** — layout, warna, animasi, dan tampilan responsif
- **GitHub Pages** — publikasi website statis

## Struktur Utama

```text
HappyGirlfriendDay/
├── index.html       # Halaman pembuka
├── next.html        # Halaman utama ucapan
├── Background.jpg   # Gambar latar
├── Example.jpg      # Foto pada halaman pembuka
├── MyGirl.jpg       # Foto pertama
├── My-Girl.jpg      # Foto kedua
└── MyGirl.mp3       # Musik latar
```

## Menjalankan Secara Lokal

Tidak diperlukan instalasi dependensi.

1. Clone repositori:

   ```bash
   git clone https://github.com/DzarelDeveloper/HappyGirlfriendDay.git
   ```

2. Masuk ke direktori proyek:

   ```bash
   cd HappyGirlfriendDay
   ```

3. Jalankan local server:

   ```bash
   python -m http.server 8000
   ```

4. Buka `http://localhost:8000` melalui browser.

## Kustomisasi

Untuk membuat versi personal:

1. Ganti gambar dengan file milik sendiri dan pertahankan nama file yang digunakan, atau sesuaikan atribut `src` pada HTML.
2. Ubah isi pesan di dalam `next.html`.
3. Ganti `MyGirl.mp3` dengan audio pilihan sendiri.
4. Sesuaikan tautan tombol balasan dengan tujuan kontak yang diinginkan.
5. Periksa kembali tampilan dan seluruh tautan sebelum dipublikasikan.

> [!IMPORTANT]
> Jangan menyimpan nomor telepon, foto pribadi, atau media berhak cipta di repositori publik tanpa izin. Gunakan data contoh apabila proyek akan dijadikan template untuk pengguna lain.

## Demo

Versi publik proyek dapat dibuka melalui:

**[Buka Live Demo](https://dzareldeveloper.github.io/HappyGirlfriendDay/)**

> Beberapa browser membatasi audio autoplay. Jika musik tidak langsung diputar, pengguna mungkin perlu berinteraksi dengan halaman terlebih dahulu.

## Lisensi

Proyek ini didistribusikan di bawah [MIT License](LICENSE).

## Author

Dibuat oleh [DzarelDeveloper](https://github.com/DzarelDeveloper).
