

 ✍️ Bab 19  
 Menulis Proyek Non-Koding dengan Git

---

 🧠 Git Bukan Hanya untuk Koding

Ketika mendengar kata Git, banyak orang langsung membayangkan baris-baris kode, terminal hitam, dan proyek software rumit. Padahal kenyataannya, Git adalah alat untuk siapa pun yang bekerja dengan dokumen teks—dan itu mencakup hampir semua orang di dunia akademik, pendidikan, dan kreatif.

Mulai dari menulis artikel ilmiah, laporan pelatihan, materi kelas, hingga puisi dan buku non-fiksi, Git dapat digunakan untuk:
- Menyimpan jejak versi tulisan
- Mengelola dokumen besar secara modular
- Menjaga konsistensi revisi
- Mencatat proses berpikir dan perubahan narasi

Pada bab ini, kita akan mengeksplorasi bagaimana Git bisa diandalkan dalam proyek non-koding, dan justru memberikan kekuatan _creative versioning_ yang sering tak dimiliki aplikasi pengolah kata biasa.

---

 📚 Contoh Proyek Non-Koding

| Jenis Proyek                     | Format File       | Tools Pendukung       |
|----------------------------------|--------------------|------------------------|
| Artikel ilmiah / esai            | `.md`, `.tex`, `.docx` | GitHub + Pandoc       |
| Modul pelatihan                  | `.md`, `.pdf`      | GitBook, Reveal.js     |
| Buku pelajaran / fiksi           | `.md`, `.epub`     | GitBook, Leanpub       |
| Laporan organisasi / CSR         | `.md`, `.html`     | Hugo, MkDocs           |
| Catatan riset / log lapangan     | `.md`, `.csv`      | GitHub Desktop         |

---

 ✏️ Mengapa Git Bermanfaat untuk Penulis?

 1. Histori yang Transparan
Git mencatat semua perubahan secara otomatis. Kamu bisa:
- Melihat versi minggu lalu
- Menelusuri siapa menulis apa (jika bekerja tim)
- Kembali ke versi awal tanpa takut kehilangan

 2. Modularitas Bab
Dokumen bisa dipisah jadi beberapa file: `bab1.md`, `bab2.md`, `lampiran.md`.  
Ini membuat penulisan besar terasa lebih ringan dan terorganisir.

 3. Kolaborasi Efisien
Git memungkinkan penulis dan editor bekerja pada file yang sama tanpa saling menimpa.  
Komentar, revisi, dan penggabungan bisa dilakukan melalui Pull Request.

 4. Sinkronisasi Lintas Perangkat
Bekerja di laptop kampus, revisi di rumah, cek di HP.  
Semua bisa dilakukan lewat GitHub dan GitBook yang saling terhubung.

---

 🧭 Contoh Alur Penulisan Buku dengan Git

1. Buat folder `buku-ku/`
2. Tambahkan file:
   - `README.md` → Ringkasan proyek
   - `bab1-pendahuluan.md`
   - `bab2-isi.md`
   - `bab3-penutup.md`
3. Gunakan GitHub Desktop untuk commit tiap bab yang selesai
4. Tulis dokumentasi pendukung di `docs/`
5. Hubungkan ke GitBook → tampil sebagai buku digital

🎉 Kamu kini memiliki buku yang:
- Bisa dibaca online
- Bisa dicetak PDF
- Bisa dikembangkan siapa pun secara kolaboratif

---

 🧠 Studi Kasus: Modul Pelatihan Berbasis Git

Bayu adalah seorang dosen yang menyusun modul pelatihan digital literasi.  
Alih-alih menyusun semuanya di Word, Bayu:
- Menulis tiap sesi pelatihan di `.md` → `sesi1.md`, `sesi2.md`, dll.
- Menyimpan semua versi perubahan dengan commit
- Mengundang rekan dosen untuk mereview via GitHub Pull Request
- Mengubahnya menjadi buku pelatihan online via GitBook

Hasilnya? Materi yang dulunya berantakan sekarang tampil profesional, bisa dibaca siapa pun, dan terus diperbarui.

---

 📖 Menulis Itu Coding Juga—Dalam Narasi

Menulis bukan hanya merangkai kata, tapi membangun struktur berpikir.  
Sama seperti coding:
- Ada logika
- Ada perubahan versi
- Ada kesalahan dan revisi

Git menghadirkan _superpower_ yang dulu hanya dimiliki oleh software developer, kini bisa dimanfaatkan oleh siapa saja yang suka menulis.

---

 💡 Tips Menulis Proyek Non-Koding dengan Git

- Gunakan Markdown: ringan, mudah dipahami, bisa dikonversi ke PDF, HTML, dll.
- Pisahkan file per bab agar mudah dikelola
- Gunakan commit message seperti jurnal kerja: `Tambah ringkasan bab 2`, `Revisi paragraf pembuka`
- Manfaatkan `.gitignore` untuk mengecualikan file `.docx`, `.pdf`, atau cache
- Sinkronkan dengan GitBook untuk versi publik

---

 ✅ Checklist Bab Ini

- [ ] Saya tahu bahwa Git bisa digunakan untuk proyek non-koding
- [ ] Saya bisa menulis bab atau artikel dalam format Markdown
- [ ] Saya bisa menyimpan jejak perubahan tulisan lewat Git
- [ ] Saya siap mencoba menulis buku digital menggunakan GitBook

---

 🚀 Bab Selanjutnya: Peran Git dalam Reproducible Research

Di Bab 20, kita akan membahas konsep besar yang menjadi landasan gerakan ilmiah modern:  
riset yang dapat diulang, ditelusuri, dan dipercaya—dan bagaimana Git memainkan peran sentral di dalamnya.

