Grand Luxury Interactive 3D Christmas Tree

Gambaran Umum
Ini adalah aplikasi web pohon Natal 3D interaktif berbasis React dan Three.js dengan kontrol gestur AI. Aplikasi ini bukan sekadar tampilan 3D, tapi galeri kenangan. Ribuan partikel, lampu bercahaya, dan foto bergaya polaroid membentuk satu pohon Natal mewah. Kamu bisa mengontrol bentuk pohon dan sudut pandang hanya dengan gerakan tangan di depan kamera.

Fitur Utama

1. Visual sinematik
Pohon dibentuk dari lebih dari 45 ribu partikel bercahaya dengan efek glow dan bloom sehingga tampilan terasa hidup dan halus.


2. Galeri kenangan
Foto tampil seperti polaroid yang melayang di pohon. Setiap foto punya cahaya sendiri dan terlihat dari dua sisi.


3. Kontrol gestur AI
Tanpa mouse atau keyboard. Kamera menangkap gerakan tangan untuk mengatur pohon dan kamera.


4. Detail lengkap
Ada lampu yang berkedip, salju emas dan perak yang jatuh, serta dekorasi hadiah dan permen yang tersebar acak.


5. Mudah dikustom
Kamu bisa mengganti foto dengan foto sendiri dan mengatur jumlahnya sesuai kebutuhan.



Teknologi yang Digunakan

1. React 18 dengan Vite


2. React Three Fiber sebagai penghubung ke Three.js


3. Drei dan Maath untuk utilitas 3D


4. Postprocessing untuk efek visual


5. MediaPipe Vision dari Google untuk deteksi gestur tangan



Cara Menjalankan Proyek

1. Siapkan lingkungan
Pastikan Node.js sudah terpasang. Disarankan versi 18 ke atas.


2. Install dependensi
Buka terminal di folder proyek lalu jalankan perintah npm install


3. Jalankan aplikasi
Ketik npm run dev lalu buka alamat lokal yang muncul di browser



Cara Mengganti Foto

1. Siapkan foto
Masuk ke folder public slash photos



Foto puncak pohon
Gunakan nama file top.jpg. Foto ini akan muncul di bagian paling atas pohon.

Foto di badan pohon
Gunakan nama 1.jpg, 2.jpg, 3.jpg dan seterusnya

Saran
Gunakan foto persegi atau rasio 4 banding 3. Ukuran file sebaiknya di bawah 500 KB agar tetap lancar.

2. Ganti foto
Salin foto milikmu ke folder public slash photos dan timpa file lama. Nama file harus tetap sama.


3. Ubah jumlah foto
Jika kamu menambah atau mengurangi jumlah foto, buka file src slash App.tsx
Cari variabel TOTAL_NUMBERED_PHOTOS lalu ubah angkanya sesuai jumlah foto yang kamu pakai



Panduan Kontrol Gestur
Pastikan kamera aktif dan kamu berdiri di depannya. Di layar ada tombol debug untuk melihat tampilan kamera.

1. Telapak tangan terbuka
Efek pohon menyebar. Partikel dan foto terbang ke segala arah.


2. Tangan mengepal
Efek pohon menyatu kembali membentuk pohon Natal utuh.


3. Gerakkan tangan ke kiri atau kanan
Sudut pandang ikut berputar ke arah gerakan tangan.


4. Gerakkan tangan ke atas atau bawah
Sudut pandang kamera naik dan turun mengikuti tangan.



Pengaturan Lanjutan
Jika kamu nyaman dengan kode, buka src slash App.tsx dan cari objek CONFIG.
Di sana kamu bisa

1. Mengubah warna pohon, lampu, dan bingkai foto


2. Mengatur jumlah partikel daun, foto, dan lampu


3. Mengubah tinggi dan lebar pohon



Contoh
Jumlah partikel daun terlalu tinggi bisa membuat laptop lemah menjadi lag. Kurangi nilainya untuk performa lebih stabil.

Lisensi
Proyek ini memakai lisensi MIT. Kamu bebas memakai, mengubah, dan mengembangkan untuk kebutuhan pribadi atau proyek belajar.

Tetap semangat dan selamat mencoba.
