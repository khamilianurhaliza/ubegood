 # Ubegood — Ubi Oven & Topping Lezat

 ![Ubegood Preview](p2.jpg)

 > Menu camilan sehat dan topping kreatif — tampil modern dengan efek animasi.

 - **Status:** Prototype statis (HTML/PHP)
 - **Teknologi:** Tailwind CSS, AOS (Animate On Scroll), Font Awesome, PHP

 ---

 **Demo & Preview**

 <p align="center">
   <img src="p2.jpg" alt="Ubegood Hero" width="900" style="border-radius:12px; box-shadow:0 12px 30px rgba(0,0,0,0.15)" />
 </p>

 **Gallery**

 <p align="center">
   <img src="p6.jpg" alt="Banana Delight" width="280" style="margin:8px; border-radius:10px;" />
   <img src="p3.jpg" alt="Savory Cheese" width="280" style="margin:8px; border-radius:10px;" />
   <img src="p5.jpg" alt="Sweet Crunch" width="280" style="margin:8px; border-radius:10px;" />
 </p>

 <p align="center">
   <img src="p1.jpg" alt="1kg Ubi Oven" width="280" style="margin:8px; border-radius:10px;" />
   <img src="p9.jpg" alt="Bola Ubi Crispy" width="280" style="margin:8px; border-radius:10px;" />
 </p>

 ---

 **Fitur Utama**

 - Visual modern dengan Tailwind CSS dan font Playfair / Poppins
 - Animasi scroll halus menggunakan AOS (fade-up, delay)
 - Kartu menu dengan hover transform, bayangan, dan tombol order via WhatsApp
 - Responsif — grid yang menyesuaikan kolom untuk mobile/tablet/desktop

 ---

 **Struktur Proyek Singkat**

 - index.php — halaman utama (HTML + referensi CSS/JS)
 - p1.jpg, p2.jpg, p3.jpg, p5.jpg, p6.jpg, p9.jpg — aset gambar menu (letakkan di root proyek)

 ---

 **Jalankan Lokal**

 1. Buka terminal di folder proyek.
 2. Jalankan PHP built-in server (jika terpasang):

 ```bash
 php -S localhost:8000
 ```

 3. Buka browser ke `http://localhost:8000/index.php` atau cukup buka file `index.php` langsung.

 ---

 **Kustomisasi Cepat**

 - Ubah teks menu, harga, dan gambar di `index.php`.
 - Ganti warna utama dengan utilitas Tailwind di kelas `bg-orange-50` / `bg-orange-600`.
 - Ubah durasi/efek AOS pada inisialisasi `AOS.init({...})` di bagian bawah `index.php`.

 ---

 **Tips menambahkan screenshot berkualitas**

 1. Buka `index.php` di browser (desktop).  
 2. Ambil screenshot penuh halaman atau area kartu menu.  
 3. Simpan sebagai `p2.jpg` (hero) dan `p6.jpg`, `p3.jpg` dst. di root proyek agar gallery tampil otomatis.

 ---

 Jika Anda mau, saya bisa:

 - Men-generate contoh screenshot placeholder jika Anda ingin (PNG/GIF).  
 - Menambahkan file `assets/` dan memperbarui path gambar.  

 Terima kasih — beri tahu apakah mau desain README berbeda atau saya tambahkan screenshot otomatis.
