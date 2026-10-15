# HadirOne 1.5.5 — perbaikan input angka

Version code: 29. Distribusi langsung, application ID `com.example.absensiapp`.

Parent WebView tetap aktif ketika input atau modal dibuka. Aplikasi memblokir
gestur tarik refresh secara terpisah, tanpa menonaktifkan parent ketika fokus
berpindah ke editor. Fokus diarahkan ke child WebView.

Perubahan ini menangani potensi gangguan fokus/sentuhan saat keyboard muncul.
Gejala keyboard menutup setelah satu digit belum direproduksi pada perangkat
fisik dalam sesi ini. Perlu validasi PIN PPOB, PIN tabungan, input nominal,
nomor telepon, perpindahan kolom, dan tarik refresh setelah modal ditutup.

Tidak ada perubahan validasi PIN atau proses transaksi server.

Hasil validasi: build DirectRelease berhasil, 18 unit test lulus, sumber uji
instrumentasi berhasil dikompilasi. Signature APK v1 dan v2 terverifikasi.
Uji instrumentasi belum dijalankan karena perangkat/emulator tidak tersedia.
