

 📊 Bab 23  
 Analisis Aktivitas Repositori dan Jejak Kolaborasi

---

 🧠 Git Sebagai Catatan Jejak Kolaboratif

Salah satu kekuatan tersembunyi dari Git adalah kemampuannya merekam setiap langkah kerja secara otomatis. Tak hanya menyimpan file, Git juga mencatat:
- Siapa mengubah apa
- Kapan perubahan dilakukan
- Apa isi perubahan
- Dan bagaimana alurnya saling terhubung

Data ini bukan sekadar jejak teknis. Bila dianalisis dengan cermat, ia bisa memberikan wawasan reflektif tentang:
- Bagaimana sebuah tim bekerja
- Siapa berkontribusi di bagian mana
- Pola kerja yang muncul dari waktu ke waktu

Di bab ini, kita akan memanfaatkan fitur analitik GitHub dan log Git untuk mengevaluasi proses kolaborasi dan kerja tim secara transparan, ilmiah, dan bermanfaat.

---

 📈 Mengapa Perlu Menganalisis Repositori?

Beberapa alasan kuat:
- Evaluasi kontribusi secara adil dalam proyek bersama
- Refleksi proses belajar pada proyek riset atau kelas
- Menunjukkan hasil kerja dalam seminar atau laporan akhir
- Membuktikan keterlibatan dalam proyek publik atau open-source

Alih-alih berkata, “Saya ikut bantu kok,” kamu bisa menunjukkan:  
“Saya menyumbang 30 commit dan menulis dua bab penuh.”

---

 🧭 Fitur Analisis GitHub: Insight

GitHub menyediakan tab Insights di setiap repositori publik:

 📌 Buka Tab → `Insights > Contributors`

Di sana, kamu akan melihat:
- Grafik kontribusi tiap kontributor
- Jumlah commit per minggu
- Kapan dan seberapa aktif tiap anggota berkontribusi
- Statistik baris kode ditambah atau dihapus

Contoh tampilan:

```
+----------------+--------+------------+-----------+
| Nama           | Commit | Baris +    | Baris -   |
+----------------+--------+------------+-----------+
| Rafi           | 52     | 2.134      | 1.021     |
| Hana           | 31     | 1.409      | 899       |
| Diah           | 26     | 1.012      | 478       |
+----------------+--------+------------+-----------+
```

---

 🔍 Melihat Riwayat Individu

Selain grafik umum, kamu juga bisa:
- Klik tab History di GitHub Desktop
- Lihat daftar commit, lengkap dengan:
  - Nama penulis
  - Waktu
  - File yang diubah
  - Isi perubahan

Cara ini efektif untuk:
- Menelusuri progres skripsi
- Menilai partisipasi proyek kolaboratif
- Menghitung kontribusi berdasarkan waktu

---

 🧪 Studi Kasus: Refleksi Kelompok Buku Digital

Sebuah tim mahasiswa menulis buku tentang Data dan Literasi Digital.  
Anggota tim:
- Menulis tiap bab di branch terpisah
- Melakukan commit harian
- Mengerjakan review via pull request

Setelah proyek selesai, mereka membuka tab Insights dan menyusun grafik kontribusi untuk laporan akhir.  
Ternyata:
- Salah satu anggota yang tampak pasif justru banyak bekerja pada penggabungan dan revisi
- Waktu puncak kontribusi terjadi 5 hari menjelang deadline
- Bab yang paling sering direvisi adalah bab ke-3

> Hasilnya? Diskusi yang lebih jujur, pembagian nilai yang lebih adil, dan proses pembelajaran yang lebih terbuka.

---

 📊 Tools Ekstra untuk Visualisasi

Kamu bisa menggunakan tools tambahan:

| Tool              | Fungsi                                               |
|-------------------|------------------------------------------------------|
| GitHub Insights   | Statistik dasar kontributor dan timeline             |
| GitHub GraphQL API| Query lanjutan untuk analisis mendalam               |
| `git log` + Python| Analisis kustom dan visualisasi dengan matplotlib    |
| GitStats / GitHub CLI| Menyusun laporan HTML dari data Git               |
| WakaTime          | Plugin untuk waktu kerja dan aktivitas penulisan     |

---

 💬 Dari Data ke Refleksi

Statistik Git bukan untuk saling menuduh:  
“Kamu hanya commit 3 kali!”

Melainkan untuk refleksi seperti:
- “Kapan kami paling produktif?”
- “Siapa yang sering merge PR?”
- “Apakah semua tim memiliki beban kerja seimbang?”
- “Bagaimana alur kerja bisa ditingkatkan di proyek berikutnya?”

---

 🧠 Etika dan Transparansi

Gunakan data Git untuk membangun:
- Budaya kolaborasi sehat
- Transparansi proses
- Apresiasi kontribusi kecil

Ingat, bukan semua kontribusi bisa diukur lewat commit—komunikasi, ide, dan dukungan juga penting.

---

 ✅ Checklist Bab Ini

- [ ] Saya tahu cara mengakses statistik kontribusi di GitHub
- [ ] Saya bisa membaca data kontribusi dari log Git
- [ ] Saya memahami cara menggunakan data itu untuk refleksi tim
- [ ] Saya ingin membangun budaya kerja yang terbuka dan adil

---

 🚀 Bab Selanjutnya: Penutup – Git untuk Hidup Belajar Sepanjang Hayat

Di Bab 24, kita akan menutup buku ini dengan menyatukan semua pelajaran:  
Bagaimana Git bukan hanya alat teknis, tapi juga cara berpikir, bekerja, dan belajar sepanjang hayat.

Karena belajar Git bukan akhir dari perjalanan—tapi awal dari kebiasaan kerja yang lebih baik.

