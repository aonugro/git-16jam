

 👀 Bab 11  
 Meninjau Pull Request dan Berkolaborasi dengan Bijak

---

 🤝 Kolaborasi Itu Lebih dari Sekadar Kode

Jika Bab 10 membahas cara mengajukan perubahan lewat Pull Request (PR), maka Bab 11 ini akan membahas sisi sebaliknya: bagaimana meninjau dan memberi tanggapan atas perubahan yang diajukan oleh orang lain.

Meninjau PR bukan sekadar mencari kesalahan. Ini adalah proses:
- Belajar bersama
- Memperbaiki kualitas proyek
- Dan yang tak kalah penting: membangun budaya kolaborasi yang sehat

Di dunia GitHub, kode bisa berubah setiap hari, tapi budaya kerja yang baik akan bertahan lebih lama dari commit mana pun.

---

 🧠 Apa Peran Reviewer?

Sebagai reviewer, kamu adalah orang yang:
- Menilai apakah perubahan yang diajukan masuk akal
- Mengecek apakah tidak merusak bagian lain
- Memberikan masukan yang membangun

Kamu bukan bos yang menghakimi. Kamu adalah rekan yang membantu menjaga arah dan mutu proyek.

---

 🧭 Menemukan dan Membuka Pull Request

1. Buka halaman proyek GitHub  
2. Klik tab Pull requests  
   Di sini akan ditampilkan semua PR terbuka.

3. Klik salah satu PR untuk membukanya  
   Kamu akan masuk ke halaman detail PR tersebut.

---

 🔍 Meninjau Perubahan

Di halaman PR, ada beberapa bagian penting:

 📄 “Conversation”
- Tempat penjelasan PR dan komentar umum
- Di sinilah diskusi utama terjadi

 🧵 “Commits”
- Menampilkan commit yang termasuk dalam PR

 🧬 “Files changed”
- Menampilkan semua perbedaan file (diff)  
  Bagian ini yang paling penting untuk review teknis

---

 ✏️ Memberi Komentar Baris demi Baris

Saat meninjau kode di tab Files changed, kamu bisa:
- Klik ikon ➕ di samping baris kode
- Menuliskan komentar, pertanyaan, atau saran

Contoh:
> "Mungkin variabel ini bisa diberi nama yang lebih deskriptif?"

Setelah selesai menulis komentar, klik Start a review atau Add single comment.

---

 🧭 Menyelesaikan Review

Setelah meninjau semua perubahan, klik tombol Review changes (kanan atas).  
Kamu akan diberi tiga opsi:

| Opsi                  | Fungsi                                                                 |
|------------------------|------------------------------------------------------------------------|
| Comment            | Memberi masukan tanpa menyetujui atau menolak                          |
| Approve            | Menyetujui perubahan dan siap untuk di-merge                           |
| Request changes    | Meminta pengajuan untuk diperbaiki dulu sebelum di-merge               |

Pilih salah satu dan klik Submit review.

---

 💡 Etika Saat Review

Meninjau PR itu seperti berdiskusi di ruang kelas: sopan, jujur, dan saling menghargai.

Berikut beberapa pedoman:
- Hindari komentar bersifat pribadi (“kenapa kamu begini sih?”)
- Fokus pada solusi, bukan menyalahkan
- Beri apresiasi jika ada hal baik yang dilakukan
- Tawarkan saran, bukan perintah

Contoh komentar baik:
- “Keren! Logika ini bisa disederhanakan, coba pakai list comprehension?”
- “Kalau boleh saran, bagian ini bisa dipindah ke fungsi terpisah agar lebih rapi.”

---

 🛠️ Setelah Revisi: Menyetujui dan Merge

Jika pengaju PR sudah melakukan revisi, kamu bisa:
1. Cek kembali perubahannya
2. Submit Approve
3. Klik Merge pull request

Setelah merge selesai:
- Branch PR bisa dihapus
- Perubahan akan muncul di `main`

Kamu juga bisa menandai PR sebagai “merged” secara manual jika kamu punya akses.

---

 💬 Kenapa Review Itu Krusial dalam Riset?

Dalam konteks riset:
- PR adalah tempat menyempurnakan metode
- Review menjaga ketelitian dan kejelasan dokumentasi
- Komentar bisa menjadi rekam jejak argumentasi analisis

Dengan kata lain, review di PR membantu menjaga integritas ilmiah.

---

 ✅ Checklist Bab Ini

- [ ] Sudah membuka halaman PR orang lain
- [ ] Meninjau perbedaan file di tab “Files changed”
- [ ] Menulis komentar dengan bahasa yang sopan dan jelas
- [ ] Menyelesaikan review dengan `Approve` atau `Request changes`
- [ ] Merge PR jika sudah siap

---

 🚀 Bab Selanjutnya: Berkontribusi ke Proyek Open-Source

Di Bab 12, kamu akan mencoba sesuatu yang lebih besar:  
kontribusi ke proyek publik di luar milikmu sendiri, lewat fitur fork dan PR lintas repositori.

Ini adalah awal dari peran kamu sebagai kontributor open-source dunia nyata.

