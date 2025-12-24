Sistem Monitoring Permasalahan Barang (SHINPO)

Website ini adalah aplikasi berbasis web (Single Page Application) yang terintegrasi dengan Supabase untuk manajemen data dan pemantauan real-time.

Fitur Utama:

Multi-Role Access (Admin & Operator)
Halaman Pemilihan Peran: Pengguna disambut dengan pilihan untuk masuk sebagai Admin (akses penuh) atau Operator (monitor & pencarian).
Dashboard Admin (Manajemen Data)
CRUD Barang: Admin dapat Menambah, Mengedit, dan Menghapus data permasalahan barang (Kode, Nama, Deskripsi Masalah, dan Foto).
Upload Gambar: Mendukung unggah foto bukti permasalahan barang.
Monitoring Pengunjung: Admin dapat melihat siapa saja yang sedang online dan riwayat aktivitas pengguna.
Tampilan Operator (Monitoring & Pencarian)
Pencarian Cepat: Fitur pencarian canggih berdasarkan Kode Barang atau Masalah.
Katalog Visual: Menampilkan daftar masalah barang dalam bentuk kartu (Grid) yang responsif dengan foto yang jelas.
Image Zoom: Fitur untuk memperbesar foto barang (Lightbox) agar detail masalah terlihat jelas.
Real-time Updates: Data otomatis diperbarui tanpa perlu reload jika Admin menambahkan data baru (tergantung konfigurasi real-time Supabase).
Sistem Pelacakan (Visitor Tracking)
Mendeteksi perangkat pengguna (Android, iOS, PC, dll).
Menampilkan status "Online" secara live dan mencatat riwayat kunjungan.
Desain UI/UX Premium
Responsif: Tampilan menyesuaikan dengan sempurna di HP, Tablet, dan Desktop.
Estetika Modern: Menggunakan efek Glassmorphism (kaca), animasi latar belakang (floating blobs), dan transisi yang halus untuk pengalaman pengguna yang nyaman.
Secara keseluruhan, sistem ini berfungsi sebagai database visual digital untuk mencatat dan memantau cacat atau masalah pada barang produksi agar mudah diakses oleh tim di lapangan.

Ringkasan Arsitektur: Ini adalah aplikasi Single File HTML yang berjalan di sisi klien (Client-Side Rendering) dan berkomunikasi langsung dengan Supabase (PostgreSQL) melalui API JavaScript.
