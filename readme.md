Recycle Puzzle Tizen
====================
Merupakan kelas [Belajar Membangun Game 2D dan 3D dengan Unity](https://www.dicoding.com/academies/39 "Game dengan Unity") sebagai salah satu prasyarat dalam mengikuti [Masterclass 05: Pengembangan Game dengan TIZEN](https://www.dicoding.com/events/592 "Game dengan TIZEN").

Acara ini merupakan bagian dari [BEKRAF Developer Day 2017 - Bali](https://www.dicoding.com/events/577 "Event BEKRAF").

---

### Teknologi yang digunakan :
* [Unity Personal](https://store.unity.com/download?ref=personal "Download Unity Personal")
* [Tizen Studio](https://developer.tizen.org/development/tizen-studio/download "Download Tizen Studio")
* [Asset Game Puzzle (sudah di download)](https://gifdicoding.blob.core.windows.net/academytizenunity/AsssetGamePuzzle.unitypackage "Download Asset Game Puzzle")
* Jika menggunakan device Tizen, download driver [Samsung Android USB Driver for Windows](http://developer.samsung.com/galaxy/others/android-usb-driver-for-windows "Download driver Samsung")

### Tizen Certificate
Berikut ini beberapa ID Device yang dapat ditambahkan supaya nantinya game Anda dapat direview oleh tim Dicoding:
* 2.0#Iag89nZm4VuTJ3RJ5uo7kvEUFxs=
* 2.0#rec1rkdIgNAXjNHbe7JOK67/TA0=
* 2.0#GOl4YrUSlp+NDpaFf2zE22r8NIA=
* 2.0#wCgOA1R6yqfaI6C8xAWUCs7hoiw=

### Set Ukuran Device
* Tizen Z2 (800x480)

### Catatan
* Bedakan ruang Canvas dengan Gameplay. Untuk penempatan tulisan Score posisinya ditempatkan pada ruang Canvas.
* Supaya tampilan UI bisa menyatu dengan tampilan Gameplay maka perlu atur konfigurasi Canvas. Render Mode menjadi Screen Space - Camera, Render Camera > Main Camera, Plane Distance = 10;
* Untuk mengetahui config dari Tizen cli, masuk ke folder `C:\tizen-studio\tools\ide\bin`, lalu ketik `tizen cli-config -l`.
* Kemudian masukkan path profile dengan perintah `tizen.bat cli-config –g "default.profiles.path=[DirecktoriWorkspace]\.metadata\.plugins\org.tizen.common.sign\profiles.xml"`. Gantilah `[DirecktoriWorkspace]` sesuai dengan folder workspace tizen yang terinstall.
* Untuk mengubah arsitektur device atau store, ketik `tizen.bat cli-config "default.build.architecture=arm"`
* Untuk mengubah konfigurasi dari Debug ke Release, ketik `tizen.bat cli-config "default.build.configuration=Release"`
* Untuk mengaktifkan Developer Option pada device Tizen, klik icon Call, dan ketik *#84936#
* Nyalakan emulator Tizen, lalu atur Deployment Target ke Device Tizen yang sedang terhubung dengan menekan tombol Discover pada Publishing Setting di Unity.
* Masukkan Signing Profile Name yang sudah dibuat (contoh: Default).
* Lalu klik tombol Build And Run.