

 🔍 Bab 7  
 Menjelajahi GitHub dan Melakukan Pull dari Cloud

---

 🌐 GitHub: Lebih dari Sekadar Penyimpanan

Setelah kamu berhasil melakukan push pertama ke GitHub, proyekmu sekarang sudah berada di awan. Tapi GitHub bukan hanya tempat menyimpan kode—ia adalah platform kolaborasi, sistem pelacak perubahan, tempat diskusi, dan bahkan ruang publikasi terbuka untuk proyek-proyek terbuka.

Bab ini akan memandumu menjelajahi halaman GitHub dari proyekmu, memahami fitur-fiturnya, dan mencoba melakukan pull—yaitu proses mengambil perubahan dari GitHub ke laptopmu.

---

 🧭 Mengenal Tampilan Halaman GitHub

Buka GitHub, lalu kunjungi halaman repositorimu:  
📎 `https://github.com/username-kamu/riset-ku`

Kamu akan melihat beberapa bagian utama:

---

 📄 1. File Explorer

Halaman utama menampilkan daftar file dalam repositori kamu.  
Biasanya ditampilkan:
- README.md (terbuka otomatis)
- Folder `data/`, `code/`, `docs/`
- Riwayat commit terakhir

---

 🕒 2. Tab “Commits”

Klik pada tulisan `X commits` (misalnya `3 commits`)  
Kamu akan melihat daftar perubahan yang pernah kamu simpan:
- Siapa yang melakukan
- Kapan waktunya
- Apa pesannya

Klik pada commit tertentu, dan kamu bisa melihat perubahan detail, bahkan per baris!

---

 🧵 3. Tab “Pull Requests”

Ini adalah tempat semua diskusi integrasi perubahan terjadi.

- Jika kamu bekerja dengan tim, semua orang akan mengajukan perubahan lewat Pull Request (PR)
- Di sini kamu bisa melihat, meninjau, dan menyetujui atau menolak perubahan

---

 🗣️ 4. Tab “Issues”

Tempat mendiskusikan masalah:
- Misalnya ada bug, fitur yang diusulkan, atau diskusi topik
- Kamu (atau rekanmu) bisa membuka issue untuk melacak tugas-tugas tertentu

---

 ⚙️ 5. Tab “Actions” dan “Settings”

- “Actions” digunakan untuk otomatisasi (CI/CD) — kita belum butuh sekarang
- “Settings” adalah tempat mengganti nama repo, menambah kolaborator, atau menghapus repo

---

 🔄 Apa Itu Pull?

Pull artinya mengambil semua perubahan terbaru dari GitHub (online) ke laptop kamu (lokal).

Ini sangat penting saat:
- Kamu mengedit proyek dari dua perangkat (misalnya laptop & PC kampus)
- Bekerja dengan tim
- Ada perubahan di GitHub (misalnya edit README lewat browser)

Jika kamu tidak melakukan pull, kamu berisiko mengerjakan versi lama proyek!

---

 🧪 Praktik: Simulasi Perubahan Online

Mari kita coba:

 1. Edit README.md di GitHub
- Buka `README.md` dari browser
- Klik tombol ✏️ (ikon pensil) untuk mengedit
- Tambahkan baris:  
  ```
  Perubahan ini dilakukan langsung dari GitHub.
  ```
- Scroll ke bawah → beri commit message → klik “Commit changes”

GitHub kini menyimpan commit baru yang tidak ada di laptop kamu.

---

 📥 Melakukan Pull di GitHub Desktop

1. Buka GitHub Desktop
2. Pastikan kamu berada di repositori `riset-ku`
3. Klik tombol Fetch origin (pojok atas kanan)
4. Jika ada perubahan, tombol Pull akan muncul  
   Klik Pull

🎉 Sekarang file di laptop kamu sudah sinkron dengan versi GitHub!

---

 🧠 Apa Perbedaan Fetch vs Pull?

| Aksi           | Fungsi                                                                          |
|----------------|----------------------------------------------------------------------------------|
| Fetch      | Mengecek apakah ada perubahan baru di GitHub                                    |
| Pull       | Mengambil perubahan dan menggabungkannya ke folder lokal                    |

Kalau tidak ada perubahan, pull tidak akan mengubah apa pun.

---

 ⚠️ Waspadai Konflik saat Pull

Kalau kamu dan rekanmu mengubah file yang sama di waktu bersamaan, Git akan memberi peringatan konflik saat pull.  
Tenang, GitHub Desktop akan membantumu menyelesaikannya secara visual (lebih lengkap di Bab 12 nanti).

---

 📌 Tips Pull Aman

- Selalu lakukan pull sebelum kamu mulai kerja, agar file kamu terbaru
- Biasakan fetch dulu, baru push, agar tahu apakah aman untuk lanjut
- Kalau ragu, backup file dulu sebelum pull besar

---

 ✅ Checklist Bab Ini

- [ ] Sudah menjelajahi halaman GitHub repo
- [ ] Sudah mencoba mengedit file langsung di GitHub
- [ ] Sudah klik Fetch origin dan Pull di GitHub Desktop
- [ ] Sudah memahami risiko konflik

---

 🚀 Bab Selanjutnya: Branching dan Pengembangan Paralel

Di Bab 8, kamu akan mempelajari fitur andalan Git: branching.  
Dengan branch, kamu bisa membuat salinan proyek sementara untuk eksperimen, tanpa takut merusak versi utama.

Karena riset yang baik butuh ruang untuk gagal... dan Git membuat itu aman.

