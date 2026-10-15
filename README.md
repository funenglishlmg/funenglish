# Fun English English Training Centre

Website resmi **Fun English English Training Centre**.

🌐 Website: https://funenglishlmg.com

Website ini merupakan website company profile yang berisi informasi program pembelajaran, profil lembaga, kegiatan belajar, promo, lokasi, serta informasi kontak Fun English.

## 📌 Halaman Website

- `index.html` — Beranda
  - Hero section
  - Keunggulan Fun English
  - Video suasana belajar
  - Statistik
  - FAQ
  - Form pendaftaran
  - Lokasi cabang
  - Yuk Gabung Fun English
  - Tim Pengajar

- `tentang-kami.html` — Tentang Kami
  - Profil lembaga
  - Mengapa memilih Fun English
  - Profil pengajar
  - Suasana belajar
  - Dokumentasi kegiatan

- `program-kids.html` — Fun Kids English
  - Program untuk TK dan SD

- `program-teen.html` — Teen & Academic English
  - Program untuk SMP dan SMA

- `program-general.html` — General & Professional
  - General English
  - School Partnership
  - Company Training

- `promo.html` — Promo
  - Penawaran
  - Placement Test

- `privacy.html` — Kebijakan Privasi

## 📁 Struktur Folder

```text
funenglishlmg/
│
├── index.html
├── tentang-kami.html
├── program-kids.html
├── program-teen.html
├── program-general.html
├── promo.html
├── privacy.html
│
├── assets/
│   ├── images/
│   ├── videos/
│   ├── posters/
│   └── file pendukung lainnya
│
└── README.md
🚀 Teknologi
Website menggunakan:
- HTML5
- CSS
- JavaScript
- Tailwind CSS melalui CDN
- GitHub Pages
- Custom Domain
- HTTPS / SSL
Website bersifat static website dan tidak menggunakan backend atau database.
🌐 Deployment
Website saat ini menggunakan GitHub Pages sebagai layanan deployment.
Custom Domain:
https://funenglishlmg.com
HTTPS:
Aktif
Repository:
GitHub - funenglishlmg
🔄 Cara Update Website
Jika ingin mengubah isi website:
1. Buka repository GitHub.
2. Pilih file HTML yang ingin diubah.
3. Klik file tersebut.
4. Klik ikon Edit atau ikon pensil.
5. Lakukan perubahan.
6. Klik Commit changes.
7. Tunggu beberapa saat sampai GitHub Pages melakukan deployment ulang.
8. Buka kembali https://funenglishlmg.com
9. Jika perubahan belum terlihat, tunggu beberapa menit kemudian refresh browser.
🖼️ Cara Mengganti Foto
Foto website berada di dalam folder:
assets/

Format foto yang disarankan:
- .jpg
- .jpeg
- .png
- .webp
Gunakan nama file yang sederhana.
Contoh:
kelas-fun-english.jpg
kegiatan-anak.jpg
guru-fun-english.jpg

Hindari nama file yang terlalu panjang atau menggunakan banyak simbol.
Mengganti Foto Melalui GitHub
1. Buka repository GitHub.
2. Masuk ke folder assets.
3. Cari foto yang ingin diganti.
4. Upload foto baru.
5. Jika ingin mengganti foto lama, gunakan nama file yang sama.
6. Klik Commit changes.
7. Tunggu GitHub Pages melakukan deployment.
8. Buka kembali website untuk mengecek hasilnya.
Penting: nama file foto yang digunakan di HTML harus sama dengan nama file yang ada di folder assets.

Contoh:
<img src="assets/kegiatan-anak.jpg" alt="Kegiatan Fun English">

Maka file tersebut harus berada di:
assets/kegiatan-anak.jpg

🎥 Cara Mengganti Video
Video website berada di dalam folder:
assets/

Format video yang disarankan:
.mp4

Contoh:
suasana-belajar.mp4
kegiatan-fun-english.mp4

Mengganti Video Melalui GitHub
1. Siapkan video baru.
2. Gunakan format .mp4.
3. Beri nama file yang sederhana.
4. Buka repository GitHub.
5. Masuk ke folder assets.
6. Upload video baru.
7. Pastikan nama file sesuai dengan yang digunakan oleh HTML.
8. Klik Commit changes.
9. Tunggu GitHub Pages melakukan deployment.
10. Buka website dan cek video tersebut.
Penting: jangan menghapus video lama sebelum memastikan video baru sudah terhubung dengan HTML.

📷 Cara Menambahkan Foto Baru
Misalnya ingin menambahkan foto kegiatan baru.
Upload foto ke:
assets/kegiatan-baru.jpg

Kemudian tambahkan foto tersebut pada file HTML yang diinginkan.
Contoh:
<img src="assets/kegiatan-baru.jpg" alt="Kegiatan Fun English">

Setelah itu lakukan:
Edit HTML
↓
Upload foto
↓
Commit changes
↓
Tunggu deployment
↓
Cek website

🎬 Cara Menambahkan Video Baru
Upload video ke folder:
assets/

Contoh:
assets/kegiatan-baru.mp4

Kemudian tambahkan video tersebut ke HTML.
Contoh:
<video controls>
    <source src="assets/kegiatan-baru.mp4" type="video/mp4">
</video>

Setelah itu klik Commit changes dan tunggu GitHub Pages melakukan deployment.
🔄 Cara Redeploy Setelah Mengubah Foto atau Video
Setelah melakukan perubahan pada repository GitHub:
1. Pastikan semua perubahan sudah di-Commit.
2. GitHub Pages akan otomatis menjalankan proses deployment.
3. Tidak perlu upload ulang seluruh website ke GitHub Pages secara manual.
4. Tunggu beberapa saat.
5. Buka https://funenglishlmg.com
6. Refresh halaman.
7. Jika masih menampilkan versi lama, lakukan hard refresh atau tunggu beberapa menit sampai cache diperbarui.
Urutannya:
Ubah Foto / Video
↓
Upload ke GitHub
↓
Commit changes
↓
GitHub Pages otomatis deploy
↓
Tunggu beberapa saat
↓
Buka website
↓
Refresh
↓
Perubahan tampil

💾 Backup Sebelum Mengubah Website
Sebelum melakukan perubahan besar pada website, sebaiknya buat backup terlebih dahulu.
Jangan menghapus file atau folder secara sembarangan karena beberapa file dapat digunakan oleh halaman website lainnya.
Khusus folder:
assets/

sebaiknya tidak dihapus karena berisi foto, video, logo, poster, dan file pendukung website.
📱 Tampilan Website
Website dibuat responsive sehingga dapat digunakan melalui:
- 📱 Smartphone
- 💻 Laptop
- 🖥️ Desktop
- 📱 Tablet
🔗 Fitur Website
Website menyediakan beberapa fitur:
- Informasi program pembelajaran
- Informasi pengajar
- Galeri foto
- Video kegiatan
- Informasi lokasi
- Tombol WhatsApp
- Form pendaftaran
- FAQ
- Promo
- Placement Test
- Informasi kontak
- Custom domain
- HTTPS
📞 Informasi Kontak
Fun English English Training Centre
Website:
https://funenglishlmg.com
Email:
englishfun251@gmail.com
⚠️ Catatan
Sebelum melakukan perubahan pada website, pastikan file yang akan diubah sudah diketahui kegunaannya.
Jika tidak yakin dengan perubahan yang akan dilakukan, buat backup terlebih dahulu.
Perubahan pada file HTML, CSS, JavaScript, foto, atau video dapat memengaruhi tampilan website.
© Copyright
© 2026 Fun English English Training Centre.
All rights reserved.