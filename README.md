## Kasir Restoran

Aplikasi Kasir Restoran (POS) Sederhana
Sebuah aplikasi Point-of-Sale (POS) berbasis web yang dirancang untuk mengelola pesanan dan pembayaran di restoran. Aplikasi ini dibangun menggunakan teknologi native tanpa framework.

## Teknologi
Backend: PHP
Database: MySQL
Frontend: HTML, CSS, JavaScript

## Fitur Utama
Halaman Pelanggan: Menampilkan menu, menambah item ke keranjang, dan membuat pesanan berdasarkan nomor meja.

Dashboard Admin: Menampilkan pesanan masuk secara real-time dan memungkinkan pembaruan status pesanan (Pending → Preparing → Ready).

Sistem Kasir: Memproses pembayaran untuk pesanan yang sudah selesai (completed), mencatat metode pembayaran, dan menyediakan fitur cetak struk.

Manajemen Keranjang Interaktif: Pengguna dapat menambah, mengurangi, atau menghapus item langsung dari halaman keranjang.

## Login System

Aplikasi ini menggunakan sistem login dengan multi-role dalam satu halaman login. Berdasarkan role yang terdeteksi saat login, pengguna akan diarahkan ke halaman yang sesuai:

Admin → diarahkan ke admin.php untuk mengelola dashboard, pesanan, dan laporan.

User → diarahkan ke index.php untuk membuat pesanan berdasarkan nomor meja.

Kasir → diarahkan ke kasir.php untuk memproses pembayaran dan mencetak struk.

## Admin

Admin dapat masuk melalui halaman admin.php dan memiliki hak akses penuh untuk mengelola aplikasi. Melalui halaman ini, admin bisa menambah, mengedit, dan menghapus data menu, memantau pesanan yang masuk secara real-time, memperbarui status pesanan, serta melihat laporan transaksi restoran. Admin juga bisa merubah users seperti mengedit atau mengubah data dari users tersebut.

## Status Makanan

Status makanan digunakan untuk memantau progres setiap pesanan mulai dari dibuat hingga selesai atau dibatalkan. Berikut daftar status yang tersedia:

Pending → Pesanan baru dibuat dan menunggu diproses.

Preparing → Pesanan sedang dimasak/ dipersiapkan oleh dapur.

Ready → Pesanan sudah selesai dimasak dan siap diantar.

Completed → Pesanan sudah diantar ke pelanggan dan pembayaran selesai.

Cancelled → Pesanan dibatalkan oleh pelanggan atau admin.
