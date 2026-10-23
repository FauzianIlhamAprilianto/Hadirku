HadirKu adalah mockup MVP aplikasi web untuk presensi kehadiran kelas di perguruan tinggi. Aplikasi ini dibuat untuk menjawab masalah pencatatan kehadiran yang manual, sulit dipantau, dan lambat dilaporkan. Dengan HadirKu, dosen membuka sesi presensi, mahasiswa mengisinya lewat kode atau QR, dan admin memantau serta mengekspor laporannya.

Aplikasi ini memakai tiga peran yang sama dengan requirement dan use case diagram kelompok Anda: Admin, Dosen, dan Mahasiswa.

Fitur per peran

Admin mengelola data akademik dan memantau kehadiran:

Ringkasan kehadiran: jumlah mahasiswa dan kelas, rata-rata kehadiran, batang kehadiran per kelas, dan daftar mahasiswa dengan kehadiran di bawah 75%.
Tambah, ubah, dan hapus data mahasiswa.
Tambah, ubah, dan hapus kelas beserta dosen pengampu dan jadwalnya.
Laporan kehadiran.

Dosen menjalankan presensi di kelasnya sendiri:

Membuka sesi presensi, yang menampilkan kode 6 karakter dan kode QR.
Menandai status tiap mahasiswa secara manual (Hadir, Izin, Sakit, Alpa), sambil melihat berapa mahasiswa yang sudah hadir. Yang belum ditandai dicatat Alpa saat sesi ditutup.
Menutup sesi, lalu hasilnya masuk ke riwayat kehadiran.
Melihat laporan kelas yang diampunya saja.

Mahasiswa mengisi dan memantau kehadirannya sendiri:

Mengisi presensi dengan memasukkan kode dari dosen. Kode divalidasi dulu, mewakili use case Validasi Kehadiran. Tombol “Demo: simulasikan scan QR” menggantikan scan kamera sungguhan.
Melihat persentase dan riwayat kehadiran tiap mata kuliah, per pertemuan lengkap dengan tanggalnya.
Menerima peringatan otomatis di halaman utama jika kehadiran suatu mata kuliah di bawah 75%.

Fitur umum:

Login dan pendaftaran akun untuk ketiga peran, dengan akses menu sesuai peran.
Laporan yang bisa disaring per kelas, per mahasiswa, dan per rentang tanggal.
Ekspor laporan ke CSV (dibuka di Excel) dan ke PDF lewat fitur cetak browser.
Tampilan dan teknologi

Status kehadiran ditampilkan sebagai kotak kecil berwarna dan berhuruf (H, I, S, A), jadi riwayat satu semester terbaca sekilas. Warna dan huruf dipakai bersamaan supaya tetap terbaca bagi yang sulit membedakan warna. Navigasi berupa tab horizontal di atas yang bisa digeser, sehingga nyaman di HP maupun laptop.
