

 📖 Bab 13  
 Menyusun Dokumentasi Proyek Riset Menggunakan GitBook

---

 📚 Dokumentasi Itu Penting

Dalam dunia riset dan pengembangan digital, dokumentasi adalah seperti papan penunjuk jalan—tanpanya, bahkan proyek paling canggih bisa membingungkan, bahkan oleh pembuatnya sendiri. Dokumentasi bukan hanya pelengkap; ia adalah penghubung antara ide dan pemahaman, antara data dan dampak.

Setelah kamu menyusun struktur proyek dengan rapi dan membagikannya lewat GitHub, kini saatnya membuatnya mudah dibaca, indah dilihat, dan terstruktur seperti buku digital.

Di sinilah GitBook berperan.

---

 🌐 Apa Itu GitBook?

GitBook adalah platform online yang mengubah file Markdown (.md) menjadi buku digital interaktif, lengkap dengan navigasi bab, pencarian, dan tampilan profesional.

GitBook sangat cocok untuk:
- Dokumentasi riset
- Modul belajar mandiri
- Panduan penggunaan aplikasi
- Catatan proyek kolaboratif

Dengan GitBook, kamu bisa menampilkan isi folder `docs/` dari repositori GitHub kamu sebagai sebuah buku digital, tanpa perlu menulis HTML, CSS, atau membuat desain dari nol.

---

 🔧 Persiapan Awal: Struktur `docs/`

Sebelum menggunakan GitBook, pastikan kamu sudah memiliki struktur folder `docs/` dalam repositori GitHub-mu. Misalnya:

```
docs/
├── README.md
├── latar-belakang.md
├── metode.md
├── analisis.md
└── kesimpulan.md
```

File-file ini akan otomatis menjadi bab-bab buku di GitBook.

> 📝 Gunakan format Markdown untuk menulis: ` Judul`, ` Subjudul`, `- daftar`, dan sebagainya.

---

 🧭 Langkah-Langkah Menggunakan GitBook

 1. Buat Akun GitBook

- Buka [https://app.gitbook.com](https://app.gitbook.com)
- Klik Sign up
- Pilih metode login (GitHub, Google, email)

 2. Hubungkan ke GitHub

Setelah login:
- Klik New space → Import from GitHub
- GitBook akan minta izin akses ke akun GitHub kamu
- Pilih repo yang ingin kamu tampilkan (misalnya `riset-ku`)

 3. Pilih Folder `docs/` Sebagai Sumber

GitBook akan membaca isi folder dan menampilkannya sebagai struktur buku.  
Jika file `docs/README.md` ada, itu akan menjadi halaman pertama buku.

---

 📖 Menyusun Bab dan Navigasi

GitBook memungkinkan kamu:
- Menyusun urutan bab
- Menambahkan judul dan subjudul
- Menautkan antarhalaman
- Menambahkan gambar dan grafik

Semua ini bisa kamu atur dari panel navigasi GitBook (sidebar kiri).

Kamu bisa klik dan tarik untuk menyusun ulang urutan bab.  
Jika ingin menambahkan halaman baru, cukup klik “+ Add page” atau edit langsung file `.md` di GitHub.

---

 🔄 Sinkronisasi Otomatis dengan GitHub

Setiap kali kamu melakukan:
- Perubahan isi `.md` di `docs/`
- Commit dan push ke GitHub

GitBook akan secara otomatis memperbarui tampilan bukumu!

Ini sangat berguna untuk proyek yang terus berkembang. Tidak perlu salin-tempel ke platform lain. Cukup ubah di GitHub Desktop, dan GitBook akan mengurus sisanya.

---

 ✨ Tampilan Profesional, Tanpa Coding

Beberapa fitur menarik GitBook:
- Navigasi samping yang rapi
- Tema gelap dan terang otomatis
- Pencarian instan di seluruh isi buku
- URL publik yang bisa dibagikan ke siapa saja

Contoh:
```
https://nama-kamu.gitbook.io/riset-ku/
```

Ini bisa kamu sertakan dalam CV, publikasi ilmiah, atau bahkan sebagai bahan ajar.

---

 🧠 Tips Penulisan Dokumentasi yang Baik

| Tips                               | Penjelasan                                                              |
|------------------------------------|-------------------------------------------------------------------------|
| Gunakan bahasa yang ringkas        | Hindari paragraf terlalu panjang                                        |
| Gunakan daftar (bullet/numbered)   | Membantu keterbacaan                                                    |
| Tambahkan contoh penggunaan        | Jika kamu menulis dokumentasi kode atau metode                         |
| Gunakan visual                     | Grafik, diagram, atau tabel akan memperjelas isi                       |
| Periksa konsistensi format         | Judul, subjudul, dan penomoran                                          |

---

 ✅ Checklist Bab Ini

- [ ] Sudah memiliki struktur folder `docs/`
- [ ] Sudah menulis file Markdown untuk tiap bab
- [ ] Sudah punya akun GitBook
- [ ] Sudah menghubungkan ke repo GitHub
- [ ] Sudah melihat hasil dokumentasi sebagai buku digital

---

 🚀 Bab Selanjutnya: Memoles Dokumentasi dan Menyiapkannya untuk Publikasi

Di Bab 14, kamu akan belajar cara memoles tampilan GitBook, menambahkan referensi, lisensi, dan DOI.  
Karena dokumentasi yang baik tidak hanya lengkap, tapi juga siap dibaca oleh dunia.

