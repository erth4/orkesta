# Orkesta

**Orkesta** adalah aplikasi produktivitas untuk developer di Windows. Todo, catatan, riwayat clipboard, timer fokus, jadwal sholat, kirim file, rekam layar, rekam suara, dan alat bantu developer tersedia dalam satu aplikasi. Hampir semuanya bisa dibuka dari notch kecil di bagian atas layar, tanpa perlu berpindah jendela.

*Orkesta is a desktop productivity app for developers on Windows: a notch at the top of the screen with todo, notes, clipboard history, a focus timer and prayer times, plus LAN file transfer, screen and voice recording with Zoom and Google Meet detection, and an HTTP client.*

**[Unduh versi terbaru](https://github.com/erth4/orkesta/releases/latest)**

## Cara pasang

1. Buka halaman [Releases](https://github.com/erth4/orkesta/releases/latest), lalu unduh `Orkesta-Setup-<versi>-x64.exe`.
2. Jalankan installer. Saat instalasi, Anda bisa memilih halaman yang ingin ditampilkan dan apakah Orkesta berjalan otomatis saat Windows dimulai.
3. Installer belum ditandatangani secara digital, jadi Windows SmartScreen mungkin menampilkan peringatan. Pilih **More info**, lalu **Run anyway**.

Orkesta dipasang untuk akun Anda saja, tanpa hak administrator. Pembaruan berikutnya bisa diperiksa dan dipasang dari dalam aplikasi lewat **Pengaturan > Cek pembaruan**.

**Kebutuhan sistem:** Windows 10 atau 11 64 bit, dengan driver grafis yang mendukung OpenGL.

## Notch di bagian atas layar

Notch tampil di bagian atas layar dan mengecil menjadi garis tipis saat Anda bekerja. Arahkan kursor ke sana untuk melihat todo hari ini, catatan, isi clipboard terakhir, jadwal sholat, cuaca, dan timer fokus.

- Video YouTube yang sedang diputar tampil di notch, lengkap dengan tombol putar dan lirik yang berjalan mengikuti lagu.
- Baterai, volume, kecerahan, dan Wi-Fi terlihat dalam satu panel.
- Pesan WhatsApp baru tampil sebentar di notch.
- Tarik file ke notch untuk mengirimnya ke komputer lain atau ke HP.
- Warna, bentuk, dan transparansi notch bisa diatur. Notch juga bisa diganti dengan maskot yang berjalan di layar.

## Todo dan catatan

- Catat pekerjaan dalam bentuk kartu, lengkap dengan catatan, tanda favorit, dan tenggat waktu. Kalender di halaman Todo menampilkan tenggat per tanggal.
- Todo yang terlambat atau jatuh tempo hari ini muncul di notch dan bisa langsung dicentang dari sana.
- Tekan **Win+Alt+N** untuk menulis catatan cepat dari mana saja.
- Halaman Catatan mendukung teks tebal, miring, daftar, daftar centang, dan warna. Kartu catatan bisa diberi warna dan disematkan.

## Riwayat clipboard

Orkesta menyimpan teks dan gambar yang Anda salin. Tekan **Win+Alt+V** untuk membukanya, lalu klik salah satu item untuk menyalinnya lagi. Snippet teks menyimpan kalimat yang sering dipakai. Password yang disalin dari password manager tidak ikut disimpan.

## Fokus, pengingat, dan jadwal sholat

- Timer fokus dengan durasi pilihan, istirahat otomatis, dan ringkasan waktu fokus harian.
- Pengingat untuk mengistirahatkan mata, minum air, dan peregangan.
- Jadwal sholat dengan hitung mundur, arah kiblat, dan pengingat yang muncul kembali sampai Anda menandai sudah sholat.

## Rekam layar dan rekam suara

- Rekam seluruh layar, satu monitor, atau satu jendela ke MP4, lengkap dengan suara komputer dan mikrofon.
- Rekam suara saja ke M4A. Suara Anda dan suara peserta rapat masuk ke satu file.
- Jeda lalu lanjutkan rekaman; hasilnya tetap satu file.
- Pilih mikrofon, pantau level suara, dan lihat equalizer di notch selama merekam.
- Tekan **Win+Alt+M** untuk mulai atau menghentikan rekaman.
- Saat rapat Zoom atau Google Meet dimulai, notch menawarkan untuk merekam. Saat rapat selesai, notch menawarkan untuk menghentikan rekaman. Rekaman tidak pernah dimulai tanpa pilihan Anda.

Rekaman memerlukan FFmpeg. Orkesta menawarkan untuk mengunduhnya sekali saja, sekitar 35 MB, saat Anda pertama kali merekam.

## Kirim file

- Kirim file dan folder ke komputer lain yang memakai Orkesta di Wi-Fi atau jaringan kantor yang sama.
- Kirim dan terima file dari HP cukup dengan memindai QR code. HP tidak perlu memasang aplikasi.
- File dikirim langsung antarperangkat, tidak melewati internet, dan secara bawaan isinya dienkripsi. Transfer pertama dengan perangkat baru harus Anda setujui dengan mencocokkan kode di kedua layar.

## Alat bantu developer

- Mencoba endpoint API dengan collection, environment, dan riwayat request, termasuk impor dari cURL, Postman, dan OpenAPI.
- Load test sederhana untuk melihat ketahanan layanan saat diakses banyak pengguna.
- Pemeriksaan jaringan: Ping, DNS Lookup, Traceroute, dan cek port.

## Privasi

- Tidak perlu akun. Semua data tersimpan di komputer Anda dan dienkripsi dengan akun Windows Anda.
- Orkesta hanya menghubungi internet untuk jadwal sholat, cuaca, lirik lagu, pemeriksaan pembaruan, unduhan FFmpeg, dan request API yang Anda kirim sendiri.
- Bila Orkesta berhenti tidak normal, catatan kesalahannya disimpan di komputer Anda dan tidak dikirim ke mana pun. Folder log bisa dibuka dari **Pengaturan > Buka folder log**.

## Bahasa dan tampilan

Tersedia dalam bahasa Indonesia dan Inggris, dengan mode terang dan gelap.

## Perlu diketahui

- Rekam suara, jeda rekaman, pilihan mikrofon, dan deteksi rapat saat ini baru tersedia di Windows.
- Rapat Google Meet dikenali saat tab Meet sedang aktif di browser.
- Kirim file ke HP sebaiknya dilakukan di jaringan yang Anda percaya, seperti jaringan rumah atau kantor.
- Jaringan yang memblokir komunikasi antarperangkat, seperti sebagian Wi-Fi tamu, membuat perangkat Orkesta tidak saling terlihat.

## Melaporkan masalah

Buka [Issues](https://github.com/erth4/orkesta/issues) dan jelaskan langkah yang Anda lakukan, apa yang terjadi, serta versi Orkesta yang dipakai. Lampirkan isi folder log bila Orkesta berhenti tidak normal.
