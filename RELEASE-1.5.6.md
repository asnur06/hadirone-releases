# HadirOne 1.5.6 — perbaikan autofill dan keyboard angka

Version code: 30. Distribusi APK langsung.

- Menonaktifkan autofill Android dan popup riwayat formulir di WebView APK
  untuk menangani gangguan keyboard ketika saran nomor HP muncul di kolom angka/PIN.
- Menonaktifkan autocomplete pada input angka/PIN, termasuk input modal dinamis.
- Tampilan input, nilai formulir, validasi PIN, dan proses transaksi tetap sama.
- Autofill sistem di portal APK tidak digunakan; sesi login tetap tersimpan.

Laporan pengguna: Redmi Note 14 dengan Gboard mengalami keyboard menutup saat
popup autofill muncul dan digit pertama diketik; HP tanpa popup autofill aman.

Build signed release berhasil. 18 unit test Android dan 5 uji skrip lulus.
Uji instrumentasi berhasil dikompilasi. Perilaku versi 1.5.6 masih memerlukan
konfirmasi pada Redmi Note 14 karena perangkat tidak tersambung di lingkungan build.
