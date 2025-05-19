

 🔧 Bab 2  
 Instalasi Git dan GitHub Desktop di MacBook

---

 🧭 Sebelum Memulai

Pada bab sebelumnya, kamu telah mengenal Git: alat ajaib yang mampu mencatat setiap jejak perubahan file kamu. Seperti mesin waktu digital untuk proyek. Tapi... semua itu baru bisa kamu rasakan jika Git sudah terpasang di laptopmu.

Bab ini adalah gerbang teknis pertama. Jangan khawatir—kita akan melangkah pelan-pelan. Tujuan kita adalah memastikan:
1. Git tersedia di MacBook kamu.
2. Kalau belum ada, kamu tahu cara menginstalnya.
3. Dan kalau kamu lebih suka antarmuka visual (tanpa mengetik perintah), kamu juga bisa memakai GitHub Desktop.

Siap? Yuk kita mulai!

---

 💻 Apakah Git Sudah Terinstal?

 Langkah 1: Buka Terminal

Pertama, buka aplikasi Terminal di MacBook kamu.  
Cara mudahnya:
- Klik ikon kaca pembesar (🔍 Spotlight)
- Ketik `Terminal`, lalu tekan Enter

Terminal adalah jendela ke dunia teks, tempat kamu bisa mengetik perintah-perintah seperti hacker di film. Tapi tenang, kita tidak akan nge-hack siapa pun hari ini 😄

 Langkah 2: Cek Git

Ketik perintah berikut di Terminal:

```bash
git --version
```

Jika muncul hasil seperti ini:

```
git version 2.30.1 (Apple Git-130)
```

🎉 Selamat! Git sudah terinstal di komputermu.  
Kamu bisa langsung lanjut ke bab berikutnya.

---

 ❌ Jika Git Belum Ada...

Beberapa Mac yang baru atau belum pernah digunakan untuk coding mungkin belum punya Git.  
Kalau setelah mengetik `git --version` kamu melihat notifikasi seperti:

> “The ‘git’ command requires the command line developer tools.”

Itu artinya kamu harus memasang Xcode Command Line Tools, yang berisi Git di dalamnya.

---

 🛠️ Cara Install Git (via Xcode Tools)

1. Buka Terminal
2. Ketik perintah berikut:

```bash
xcode-select --install
```

3. Akan muncul pop-up, klik Install
4. Tunggu proses download dan instalasi selesai

Biasanya ini hanya butuh beberapa menit, tergantung koneksi internet kamu.

Setelah selesai, kamu bisa ulangi `git --version` untuk memastikan Git sudah siap digunakan.

---

 🎨 Alternatif GUI: Install GitHub Desktop

Kalau kamu tidak suka Terminal—tenang, kamu tidak sendiri.  
Banyak pemula merasa lebih nyaman dengan klik-klik daripada ketik-ketik.  
Untuk itu, tersedia aplikasi GitHub Desktop, yaitu cara memakai Git lewat antarmuka grafis.

GitHub Desktop adalah pilihan ideal untuk:
- Mahasiswa
- Peneliti non-programmer
- Penulis dokumentasi
- Siapa pun yang suka hal visual

---

 📥 Cara Instal GitHub Desktop di Mac

1. Buka browser dan kunjungi:  
   👉 [https://desktop.github.com](https://desktop.github.com)

2. Klik Download for macOS

3. Setelah file `.dmg` selesai diunduh, buka dan drag ikon GitHub Desktop ke folder Applications

4. Jalankan aplikasi GitHub Desktop  
   Kamu akan diminta login ke akun GitHub.  
   Kalau belum punya akun, daftar di [https://github.com](https://github.com)

---

 🤔 Git atau GitHub Desktop: Mana yang Lebih Baik?

Jawabannya: keduanya bagus, tergantung kamu nyaman yang mana.

| Kriteria                  | Terminal (Git CLI) | GitHub Desktop |
|---------------------------|--------------------|----------------|
| Perlu ketik perintah      | ✅ Ya               | ❌ Tidak       |
| Visual & klik-klik        | ❌ Tidak            | ✅ Ya          |
| Cocok untuk pemula        | ⚠️ Bisa, tapi menakutkan | ✅ Sangat       |
| Fleksibilitas tinggi      | ✅ Sangat           | ⚠️ Terbatas    |
| Cocok untuk skrip otomatis| ✅ Ya               | ❌ Tidak       |

Saran kami: mulai dulu dengan GitHub Desktop, lalu nanti kamu bisa mencoba Terminal seiring waktu.

---

 ✅ Checklist Bab Ini

- [ ] Sudah buka Terminal dan cek `git --version`
- [ ] Jika belum ada Git, sudah install via `xcode-select --install`
- [ ] Sudah download dan install GitHub Desktop
- [ ] Sudah login ke akun GitHub

Kalau semua sudah, kamu siap untuk membuat proyek Git pertamamu!  
Kita akan memulainya di Bab 3, langsung dengan klik-klik lewat GitHub Desktop.

---

