

 🎓 Bab 18  
 Studi Kasus Mahasiswa: Mengelola Skripsi dan Tugas Akhir dengan Git

---

 📘 Kenapa Mahasiswa Perlu Git?

Git sering dianggap alat khusus programmer. Tapi kenyataannya, Git sangat relevan untuk semua mahasiswa—terutama saat menyusun karya tulis seperti:
- Skripsi
- Tesis
- Proyek akhir
- Laporan penelitian

Git membantu mengelola file, melacak perubahan, dan menyimpan versi kerja secara sistematis. Tidak ada lagi file dengan nama `skripsi_final_fix_benar_revisi_dosen2_baru_lagi.docx`.

Pada bab ini, kita akan menjelajahi cerita nyata dan studi kasus mahasiswa dari berbagai disiplin yang memanfaatkan Git dan GitHub untuk proyek akademiknya.

---

 🎓 Kasus 1: Diah (Sosiologi) – Dokumentasi Skripsi dan Wawancara

Diah sedang menulis skripsi berjudul “Representasi Media terhadap Pekerja Migran”. Ia menggunakan Word untuk menulis, tetapi menggunakan Markdown dan GitHub untuk:
- Menyimpan catatan wawancara
- Menulis outline dan log revisi
- Menyusun daftar pustaka secara terpisah

 🔍 Tantangan:
- Sering revisi dengan dua pembimbing berbeda
- Satu laptop, takut hilang

 💡 Solusi:
- Buat folder `data/wawancara/` untuk transkrip
- Simpan catatan revisi per tanggal di `docs/log.md`
- Gunakan GitHub Desktop untuk commit tiap perubahan

> Hasilnya? Semua revisi terdokumentasi, dan saat laptopnya rusak, file tetap aman di GitHub.

---

 🎓 Kasus 2: Rafi (Teknik Informatika) – Skripsi dengan Jupyter Notebook

Rafi menganalisis citra satelit dengan Python. Semua analisis ia tulis dalam Jupyter Notebook. Awalnya, Rafi sering mengalami:
- Kehilangan versi kode
- File rusak setelah eksperimen gagal

 🔧 Langkah yang Ia Lakukan:
- Buat repositori GitHub bernama `skripsi-rafi`
- Pisahkan folder: `notebooks/`, `data/`, `figures/`
- Gunakan `.gitignore` untuk mengecualikan data besar
- Push ke GitHub setiap hari

Rafi juga menulis dokumentasi metode di GitBook, yang ia berikan ke dosen pembimbing.  
> Dosen: “Saya lebih mudah meninjau lewat GitBook daripada Word.”

---

 🎓 Kasus 3: Hana (Kesehatan Masyarakat) – Penelitian Lapangan

Hana meneliti pengaruh intervensi gizi terhadap remaja di desa X. Ia menggunakan Excel, SPSS, dan Google Docs.

Karena Git tidak bisa langsung melacak file `.sav` atau Google Docs, Hana:
- Menyimpan metadata analisis di file `.md`
- Menulis log harian riset lapangan: `docs/log-penelitian.md`
- Membuat template kuesioner di repo `instrument-gizi`

Git membantu Hana menjaga catatan lapangan tetap tertata, dan ia bisa menunjukkan versi kuesioner ke pembimbing dengan link GitHub.

---

 🎓 Pelajaran dari Ketiga Kasus

| Masalah Umum Mahasiswa                  | Solusi via Git & GitHub                                |
|----------------------------------------|--------------------------------------------------------|
| Bingung revisi dari banyak pembimbing  | Gunakan commit log untuk lacak perubahan per sesi      |
| Takut kehilangan file                  | Simpan di GitHub, bisa diakses dari mana saja          |
| Data dan dokumentasi bercampur         | Pisahkan dengan struktur folder dan `.gitignore`       |
| Sulit melacak perkembangan skripsi     | Gunakan log revisi di file Markdown                   |
| Kesulitan kolaborasi                   | Manfaatkan branch, pull request, dan GitBook           |

---

 💬 Apa Kata Mereka?

> “Git bikin saya merasa proyek saya benar-benar ‘tumbuh’, bukan cuma satu file yang ditimpa terus.” — Diah

> “Saya gak tahu harus pakai Git untuk skripsi, tapi sekarang saya malah ngerasa aneh kalau gak pakai.” — Rafi

> “Yang awalnya takut, sekarang saya malah ngajarin teman kelompok saya pakai GitHub!” — Hana

---

 🧠 Git untuk Semua Disiplin

Git bukan hanya soal kode. Git adalah:
- Cara berpikir sistematis
- Cara kerja kolaboratif
- Cara menjaga transparansi

Baik kamu menulis puisi, menganalisis data statistik, atau membuat aplikasi, Git bisa membantu kamu bekerja lebih rapi, lebih aman, dan lebih profesional.

---

 ✅ Checklist Bab Ini

- [ ] Saya memahami manfaat Git untuk skripsi atau proyek akhir
- [ ] Saya tahu cara menyusun folder riset secara terstruktur
- [ ] Saya siap mencatat progres kerja dengan Git
- [ ] Saya percaya bahwa Git bisa digunakan oleh siapa pun, bukan hanya programmer

---

 🚀 Bab Selanjutnya: Menulis Proyek Non-Koding dengan Git

Di Bab 19, kita akan bahas cara menggunakan Git untuk proyek-proyek non-programming, seperti penulisan artikel ilmiah, modul pelatihan, atau bahkan buku puisi digital.

Karena tidak semua proyek butuh baris kode—tapi semua proyek butuh keteraturan.

