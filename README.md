NinjaSaga CC Panel 1.0.0 - Portable
=====================================

Cara download
-------------
Masuk ke link berikut:
https://github.com/n0faxe/Levelling-Panel/releases/
Pilih NinjaSagaCC.Portable.1.0.0.zip

Cara menjalankan
----------------
1. Extract seluruh folder ini ke lokasi mana pun di s
2. Double-click "Start Panel.bat".
3. Browser akan terbuka otomatis ke http://127.0.0.1:8000/

Membuka beberapa akun sekaligus
-------------------------------
Double-click "Start Panel.bat" lagi. Instance kedua otomatis memakai port 8001,
instance ketiga port 8002, dan seterusnya. Setiap instance punya sesi, log, dan
folder data sendiri di data/instances/<port>/.

Opsi command line
-----------------
  Start Panel.bat --no-browser     mulai tanpa membuka browser
  Start Panel.bat --port=8010      paksa port tertentu (tetap auto-naik jika dipakai)
  Start Panel.bat --app            buka dengan Edge mode aplikasi (tanpa address bar)
  Start Panel.bat --shared-data    semua instance memakai data bersama
  Start Panel.bat --version        tampilkan versi panel

Data & keamanan
---------------
- Quick login menyimpan username + password dalam bentuk plaintext di folder
  data/instances/<port>/. Jangan bagikan folder ini.
- Panel hanya listen di 127.0.0.1 dan tidak punya autentikasi. Jangan ubah ke
  0.0.0.0 tanpa menambahkan autentikasi.

Lisensi
-------
Folder ini membawa binary Node.js. Sertakan LICENSE Node.js saat mendistribusikan
ulang. Panel ini bukan produk resmi NinjaSaga.cc / Ninja Saga.

Note
-----
Pembuat tidak bertanggung jawab untuk penyalah gunaan panel ini

<a href="https://discord.gg/mKgWezvtc">
  <img src="https://cdn.simpleicons.org/discord/5865F2" width="18" alt="Discord">
  Gabung dengan Discord kami untuk pemberitahuan update
</a>
