## Kasir Restoran

Aplikasi Kasir Restoran (POS) Sederhana
Sebuah aplikasi Point-of-Sale (POS) berbasis web yang dirancang untuk mengelola pesanan dan pembayaran di restoran. Aplikasi ini dibangun menggunakan teknologi native tanpa framework.

## Teknologi
Backend: PHP
Database: MySQL / MariaDB
Frontend: HTML, CSS, JavaScript

## Fitur Utama
Halaman Pelanggan/Waiter: Menampilkan menu, menambah item ke keranjang, dan membuat pesanan berdasarkan nomor meja.
Dashboard Admin: Menampilkan pesanan masuk secara real-time dan memungkinkan pembaruan status pesanan (Pending → Cooking → Ready).
Sistem Kasir: Memproses pembayaran untuk pesanan yang sudah siap (ready), mencatat metode pembayaran, dan menyediakan fitur cetak struk.
Manajemen Keranjang Interaktif: Pengguna dapat menambah, mengurangi, atau menghapus item langsung dari halaman keranjang.

Login System

Aplikasi ini menggunakan sistem login dengan multi-role dalam satu halaman login. Berdasarkan role yang terdeteksi saat login, pengguna akan diarahkan ke halaman yang sesuai:

Admin → diarahkan ke admin.php untuk mengelola dashboard, pesanan, dan laporan.

User → diarahkan ke index.php untuk membuat pesanan berdasarkan nomor meja.

Kasir → diarahkan ke kasir.php untuk memproses pembayaran dan mencetak struk.
