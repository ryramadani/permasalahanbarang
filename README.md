SHINPO – Sistem Monitoring Permasalahan Barang
Solusi Digital untuk Pemantauan dan Dokumentasi Masalah Barang Secara Real-Time. SHINPO adalah aplikasi berbasis web (Single Page Application) yang dirancang sebagai database visual digital untuk mencatat, memantau, dan menelusuri permasalahan barang produksi secara cepat dan akurat. Sistem ini terintegrasi langsung dengan Supabase sebagai backend untuk manajemen data, autentikasi peran, serta pembaruan data secara real-time.

Deskripsi Sistem
SHINPO mendukung multi-role access dengan dua peran utama, yaitu Admin dan Operator, yang masing-masing memiliki fungsi dan tampilan berbeda sesuai kebutuhan operasional. Admin memiliki kendali penuh terhadap manajemen data permasalahan barang, mulai dari menambah, mengedit, hingga menghapus data, termasuk unggahan foto sebagai bukti visual. Selain itu, Admin juga dapat memantau aktivitas pengguna dan status pengunjung yang sedang online. Sementara itu, Operator difokuskan pada monitoring dan pencarian data, dengan fitur pencarian cepat berdasarkan kode barang atau jenis permasalahan, serta tampilan katalog visual berbentuk kartu yang responsif dan mudah dipahami. Fitur image zoom (lightbox) memungkinkan pengguna melihat detail foto masalah barang dengan lebih jelas.

Keunggulan Utama
Real-Time Monitoring
Data otomatis diperbarui tanpa perlu memuat ulang halaman, mendukung pengambilan keputusan yang lebih cepat.

Visual & Mudah Digunakan
Informasi disajikan dalam bentuk kartu dengan foto yang jelas, memudahkan identifikasi masalah di lapangan.

Visitor Tracking System
Sistem mampu mendeteksi jenis perangkat pengguna (Android, iOS, PC, dll), menampilkan status online secara langsung, serta mencatat riwayat kunjungan.

UI/UX Modern & Responsif
Mengusung desain glassmorphism, animasi latar belakang dinamis, dan transisi halus yang memberikan pengalaman pengguna premium di berbagai perangkat.

Ringkasan Arsitektur
SHINPO dibangun sebagai single-file HTML application yang berjalan sepenuhnya di sisi klien (client-side rendering) dan berkomunikasi langsung dengan Supabase (PostgreSQL) melalui JavaScript API, menjadikannya ringan, cepat, dan mudah untuk dikembangkan lebih lanjut.
