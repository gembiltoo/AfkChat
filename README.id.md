# 🌬️ BreezeChat (Bahasa Indonesia)

🇬🇧 **English:** [README.md](README.md)

**BreezeChat** adalah klien chat Minecraft Java untuk Android. Masuk ke server, ngobrol, biarkan beberapa akun tetap online di latar belakang, dan lihat sekitar lewat minimap, tanpa membuka game-nya dan hemat baterai.

> Masih **beta**. Proyek buatan penggemar, tidak berafiliasi dengan Mojang atau Microsoft.

## 🤖 Dibuat dengan AI (mohon dibaca)

BreezeChat dibuat dengan **vibe coding** (atau "slop coding", kalau mau). Hampir semua kodenya ditulis oleh asisten AI ([Claude](https://claude.ai) dari Anthropic). Pembuatnya ([@gembiltoo](https://github.com/gembiltoo)) menentukan fitur, mengirim laporan bug dan tangkapan layar, lalu mencoba tiap versi di HP dan server sungguhan. Seluruh aplikasi dibuat lewat HP Android, tanpa PC.

Artinya untuk kamu:

- 🐛 **Mungkin masih ada bug.** Wajar jika ada bug karena pembuatannya lewat HP. Kodenya belum diperiksa secara profesional atau diaudit keamanannya, dan belum semua fitur dicoba di semua server.
- 🔐 **Periksa dulu sebelum mempercayakan akun.** Akun online masuk lewat halaman resmi Microsoft, BreezeChat tidak pernah melihat kata sandi Microsoft-mu. Kata sandi akun offline (untuk `/login` otomatis) hanya disimpan di HP-mu. BreezeChat tidak punya iklan dan tidak punya analitik sendiri. Aplikasi hanya terhubung ke server Minecraft, login Microsoft/Mojang, GitHub (cek pembaruan), dan layanan terjemahan web gratis saat kamu menerjemahkan chat.
- 🔍 **Kodenya kecil dan mudah dibaca.** Berupa Java biasa dalam beberapa file. Silakan baca, utak-atik, dan perbaiki.
- 🤝 **Issue dan pull request diterima**, dari manusia maupun AI.

## Fitur utama

- **Chat**: filter chat, menu **Cmds**, **Quick commands** (tombol perintah sendiri), jam di depan tiap baris (opsional), **peringatan chat** (getar saat namamu disebut), ketuk baris chat untuk **membalas (/msg)**, **mengabaikan** pemain, atau **menerjemahkan**
- **Akun**: banyak akun sekaligus (offline dan Microsoft), mode latar belakang, auto login, auto respawn, **sambung ulang otomatis**, **AFK anti-kick** dengan metode pilihan (Jump, Swing, Sneak, Walk, Turn, Quiet), **statistik sesi**
- **Minimap**: warna biome yang detail, bayangan bukit, kedalaman air, pemain dan mob, zoom, panah arah hadap yang halus
- **Peta jelajah**: area yang pernah kamu lihat tetap tampil (lebih gelap) dan tersimpan di HP
- **Waypoint** 📍 dengan nama dan jarak, **titik kematian otomatis**, dan **koordinat portal** Overworld ↔ Nether
- **Chest, barrel, ender chest dan shulker** bisa dibuka dari peta, dengan tombol **Take all**, **Quick stack**, **Put backpack**
- **Trade dengan villager** dari peta
- Joystick, sneak, lompat otomatis, ikuti pemain, fisika air sederhana
- Menu samping ☰, **shortcut layar utama** dengan ikon server
- Tampilan berwarna, 7 bahasa, 5 tema (termasuk AMOLED hitam)
- Backup akun, server, waypoint dan quick commands ke folder

## Versi yang didukung

Server **1.19 sampai 26.1**. Versi 1.19.4, 1.20 dan 1.20.1 didukung penuh. Versi lain tersambung sebagai 1.19.4, jadi servernya harus menerima klien lama (ViaVersion / ViaBackwards).

## Cara pakai singkat

1. Unduh APK terbaru dari halaman [Releases](https://github.com/gembiltoo/BreezeChat/releases), lalu pasang.
2. Aplikasi awalnya berbahasa Inggris. Ganti di **⚙ Settings → Language**.
3. Geser kartu akun sampai kartu **+**, lalu tambah akun: **Offline** (nama bebas) atau **Online (Microsoft)**.
4. Tambah server (nama, alamat, versi), lalu ketuk kartu server untuk masuk.
5. Di dalam game ada empat tab: 💬 chat, 👥 pemain, 🎒 inventori, 📍 peta dan gerak.

## Agar tetap online saat di latar belakang

Di **Settings → Stay connected in the background**, buka daftar baterai dan set BreezeChat ke **Tanpa batasan (Unrestricted)**. Kalau tidak, beberapa HP mematikan aplikasi dan server memutus kamu dengan "Timed out".

## Keterbatasan

- Ini klien chat, bukan launcher dan tidak ada tampilan 3D. Di medan tidak rata, air, atau pagar, server bisa menarik kamu kembali.
- **Hanya server Java.** Server Bedrock tidak bisa dimasuki.
- Login Microsoft tidak ikut di backup, silakan login lagi setelah restore.
- Terjemahan memakai layanan web gratis dan butuh internet. Layanan itu bisa menolak kalau dipakai terlalu sering.

## Lapor bug

Buka [Issues](https://github.com/gembiltoo/BreezeChat/issues) dan tulis: versi BreezeChat, tipe HP dan versi Android, versi server, langkah yang dilakukan, apa yang terjadi, dan tangkapan layar.
