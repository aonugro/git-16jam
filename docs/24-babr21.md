

 🔗 Bab 21  
 Integrasi Git dengan Alat-Akat Akademik Lain

---

 🧠 Git Tidak Sendiri di Dunia Ilmiah

Selama 20 bab sebelumnya, kita telah mengenal Git sebagai alat pengelola versi, catatan kerja digital, dan penyusun dokumentasi proyek riset. Namun dalam dunia nyata, pekerjaan akademik tidak hanya melibatkan Git. Kita juga bergantung pada:

- Alat sitasi seperti Zotero
- Editor LaTeX seperti Overleaf
- Editor daring kolaboratif seperti Google Docs
- Perangkat spreadsheet dan cloud seperti Google Sheets dan Excel

Kabar baiknya? Git tidak berdiri sendiri.  
Ia dapat berteman baik dan berintegrasi dengan semua alat ini, menjadikannya semakin fleksibel dan kuat dalam menunjang kerja riset, penulisan, dan kolaborasi.

---

 📚 Git + Zotero = Sitasi yang Tersinkronisasi

Zotero adalah aplikasi manajemen referensi yang membantu kamu:
- Menyimpan dan mengelola pustaka
- Menyisipkan sitasi otomatis ke dokumen
- Menyusun daftar pustaka sesuai gaya APA, MLA, dll.

 📌 Integrasi Praktis

1. Gunakan Zotero + BetterBibTeX untuk menghasilkan file `.bib`
2. Simpan file `.bib` ke folder `refs/` dalam proyek Git
3. Gunakan file itu di dokumen `.tex`, Markdown, atau RMarkdown
4. Lacak perubahan pustaka dengan Git

🎯 Git akan mencatat kapan referensi ditambahkan, diubah, atau diperbarui.

---

 📄 Git + Overleaf = LaTeX yang Aman

Overleaf adalah editor LaTeX berbasis web yang sangat populer di kalangan peneliti.  
Ia memiliki fitur version control, tapi masih dasar.

Git memungkinkan kamu untuk:
- Menyimpan salinan lokal proyek Overleaf
- Melakukan editing offline
- Menyinkronkan ulang ke Overleaf dengan GitHub

 🔧 Cara Menghubungkan:
1. Hubungkan akun Overleaf ke GitHub
2. Di Overleaf, buka proyek → Menu → GitHub Sync
3. Set repo GitHub sebagai asal/sinkronisasi

Sekarang kamu bisa menulis paper ilmiah di Overleaf dan tetap menyimpan semua versinya di GitHub!

---

 👥 Git + Google Docs/Sheets = Kolaborasi Hybrid

Google Docs dan Google Sheets memang tidak berbasis Git, tapi kamu tetap bisa mengintegrasikan bagian-bagian tertentu dari proses kerja kamu:

 ✅ Praktik Terbaik:
- Ekspor data dari Google Sheets ke `.csv` → simpan ke `data/`
- Tulis ringkasan diskusi dari Google Docs ke `log-revisi.md`
- Gunakan Git untuk menyimpan hasil akhir atau versi yang ingin diarsipkan

🎯 Git cocok untuk menyimpan hasil tetap dan jejak perubahan utama, bukan untuk menyimpan proses diskusi informal.

---

 🖼️ Git + Canva atau Figma

Jika kamu mendesain visual seperti infografik, diagram, atau layout buku:
- Ekspor hasilnya sebagai `.png` atau `.svg`
- Simpan ke folder `assets/` atau `figures/` dalam repositori
- Gunakan commit message yang menjelaskan perubahan visual

> Git tidak bisa melacak isi gambar, tapi bisa mencatat kapan gambar berubah—dan kamu bisa menelusuri versi sebelumnya.

---

 📌 Ringkasan Integrasi

| Alat                   | Apa yang Diintegrasikan                      | Cara Git Membantu                          |
|------------------------|----------------------------------------------|--------------------------------------------|
| Zotero + BetterBibTeX  | File `.bib` dan referensi                   | Melacak perubahan pustaka secara otomatis  |
| Overleaf               | Dokumen `.tex`, grafik, dan rujukan         | Sinkronisasi dan backup versi paper        |
| Google Docs/Sheets     | Data `.csv`, log `.md`                      | Menyimpan ringkasan & hasil final          |
| Canva, Figma           | Gambar ekspor (`.png`, `.svg`)              | Riwayat perubahan visualisasi              |
| Obsidian / Notion      | Teks Markdown dan catatan riset pribadi     | Backup dan histori catatan                 |

---

 🧠 Kenapa Ini Penting?

Dalam dunia riset modern, kamu jarang bekerja dengan satu alat saja.  
Git bukan solusi tunggal—ia adalah penghubung lintas alat. Dengan pendekatan ini:

- Kamu tetap bisa pakai alat favoritmu
- Tapi kamu juga mendapatkan histori dan backup yang terstruktur
- Dan kamu bisa membagikan hasil kerja dalam format standar terbuka

---

 ✅ Checklist Bab Ini

- [ ] Saya memahami peran Git sebagai pengelola versi lintas alat
- [ ] Saya tahu cara menyimpan file `.bib` dari Zotero ke Git
- [ ] Saya bisa menyinkronkan proyek Overleaf ke GitHub
- [ ] Saya tahu batas dan manfaat integrasi Google Docs ke Git
- [ ] Saya yakin bisa mengatur proyek akademik saya dengan lebih terpadu

---

 🚀 Bab Selanjutnya: Kolaborasi Menulis Buku Digital bersama Tim

Di Bab 22, kita akan menyelami praktik nyata menulis buku digital secara kolaboratif, menggunakan Git dan GitBook—dari pembagian bab, review, sampai publikasi.

Karena buku tidak selalu ditulis sendiri—dan Git menjadikan menulis bersama lebih mudah, rapi, dan menyenangkan.

