

 ☁️ Bab 6  
 Melakukan Push ke GitHub: Menyimpan Proyek ke Cloud

---

 🌍 Dari Lokal ke Global

Bayangkan kamu baru saja menyusun folder riset dengan rapi: data tersimpan, kode berjalan, dokumentasi lengkap, dan commit sudah kamu buat. Tapi semua masih ada di satu tempat: laptop kamu sendiri.

Apa yang terjadi jika laptop rusak? Atau kamu ingin bekerja dari perangkat lain? Atau kamu ingin membagikan proyekmu ke pembimbing atau tim?

Di sinilah GitHub hadir sebagai jembatan. Dengan satu langkah kecil—push—kamu bisa menyimpan seluruh proyek ke awan (cloud), menjadikannya versi online, aman, dan siap kolaborasi.

Bab ini akan membimbingmu melakukan push pertama ke GitHub menggunakan GitHub Desktop, dengan penjelasan sederhana, aman, dan menyenangkan.

---

 🚀 Apa Itu Push?

Dalam dunia Git:
- Commit = menyimpan perubahan ke dalam riwayat lokal
- Push = mengirim riwayat lokal itu ke repositori online (GitHub)

Think of it this way: commit itu seperti menulis di buku harian pribadimu, sedangkan push itu seperti memasang hasilnya di papan pengumuman digital. Orang lain bisa lihat, unduh, dan bahkan ikut membantu.

---

 💡 Mengapa Push Itu Penting?

1. Backup otomatis — file kamu tidak hanya di satu tempat
2. Kolaborasi real-time — tim bisa ambil, baca, bahkan ubah proyek
3. Publikasi terbuka — kode kamu bisa dikutip, disebarluaskan
4. Terhubung ke layanan lain — seperti GitBook, Zenodo, dsb.

---

 ✅ Syarat Sebelum Push

Sebelum kamu push, pastikan:
- Sudah punya akun GitHub (jika belum, daftar di [https://github.com](https://github.com))
- Sudah login di GitHub Desktop
- Sudah membuat repositori lokal dan melakukan commit (Bab 3–5)

---

 🧭 Langkah-Langkah Push Pertama di GitHub Desktop

 1. Buka GitHub Desktop  
Pilih proyek `riset-ku` yang sudah kamu buat.

 2. Klik “Publish repository” (pojok kanan atas)  
Sebuah jendela baru akan muncul.

 3. Isi pengaturan publikasi  
- Name: Sesuai nama lokal (`riset-ku`)
- Description: Ringkasan proyekmu
- Keep this code private: Jangan dicentang jika kamu ingin proyek ini bisa dilihat orang lain (misalnya untuk publikasi di GitBook atau Zenodo)

 4. Klik Publish Repository

Selesai! 🎉  
Proyek kamu kini sudah online, dan bisa diakses di:  
`https://github.com/username-kamu/riset-ku`

---

 🔍 Coba Lihat Repositori Online

Setelah push, kamu bisa:
- Klik kanan nama proyek di GitHub Desktop → “View on GitHub”
- GitHub akan membuka browser dan menampilkan halaman repositori

Di sana, kamu akan melihat:
- File README kamu tampil otomatis
- Folder `code`, `data`, `docs` sudah tersusun
- Commit history kamu bisa dilihat publik

---

 💻 Apa yang Terjadi di Balik Layar?

Saat kamu klik Publish Repository, GitHub Desktop:
- Membuat repositori kosong di GitHub
- Menghubungkan repositori lokal ke repositori cloud (disebut remote)
- Mengirim semua commit yang sudah kamu buat

Setelah itu, setiap kali kamu klik Push origin, semua perubahan terbaru akan disimpan ke GitHub.

---

 🔄 Push & Pull: Dua Arah

GitHub dan GitHub Desktop bekerja dua arah:

| Aksi      | Arti                                                             |
|-----------|------------------------------------------------------------------|
| Push  | Kirim perubahan dari laptop ke GitHub (online)                  |
| Pull  | Ambil perubahan dari GitHub ke laptop (misalnya dari teman tim) |

Untuk kerja tim, pull dulu sebelum mulai kerja, agar kamu tidak mengedit file lama.

---

 🧪 Tips Aman Saat Push

- Selalu commit dulu, baru push. Kamu tidak bisa push perubahan yang belum dicatat.
- Kalau kamu bekerja dengan tim, pull dulu sebelum push, agar tidak bentrok.
- Gunakan commit message yang rapi supaya riwayat proyek mudah dibaca siapa pun.

---

 ⚠️ Awas Kesalahan Umum

| Kesalahan                             | Solusi                                                                    |
|--------------------------------------|---------------------------------------------------------------------------|
| Push tidak bisa karena konflik       | Lakukan pull dulu, selesaikan konflik, lalu push                          |
| Tidak muncul tombol “Push”           | Belum ada commit baru yang perlu dikirim                                  |
| Salah folder dipush (misalnya data besar)| Tambahkan ke `.gitignore`, lalu hapus dari repo jika perlu               |

---

 ✅ Checklist Bab Ini

- [ ] Sudah login ke GitHub Desktop
- [ ] Klik Publish repository
- [ ] Repo muncul online di GitHub
- [ ] Sudah melihat struktur file dari browser
- [ ] Siap untuk lanjut ke kolaborasi tim

---

 🚀 Bab Selanjutnya: Menjelajahi GitHub dan Pull

Di Bab 7, kamu akan menjelajah halaman GitHub:  
- Melihat commit history  
- Memahami peran tab Issues, Pull Requests, dan Actions  
- Dan belajar cara mengambil perubahan dari cloud ke lokal (pull)

Git tidak hanya tentang menyimpan—tapi juga tentang sinkronisasi cerdas.

