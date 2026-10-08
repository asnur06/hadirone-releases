# HadirOne 1.5.4

Versi Android 1.5.4, version code 28. Distribusi APK langsung.

- Dukungan membuka tautan detail transaksi PPOB dari WhatsApp ke aplikasi.
- Android App Links untuk transaksi guru dan siswa pada absensi.isl.sch.id.
- Tombol Buka di HadirOne pada halaman penghubung web.
- Validasi sekolah pada tautan agar transaksi tidak terbuka pada server sekolah berbeda.

Server harus menerapkan pembaruan halaman penghubung dan menyediakan `/.well-known/assetlinks.json` melalui HTTPS tanpa login atau pengalihan. Pengguna harus memilih sekolah yang sesuai dan masuk sebagai pemilik transaksi. APK 1.5.4 ditandatangani dengan sertifikat yang sama dengan rilis sebelumnya.

Pembukaan otomatis bergantung pada verifikasi domain Android dan pengaturan buka tautan perangkat. Pengujian fisik dari WhatsApp belum dilakukan.
