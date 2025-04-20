
 📬 Bab 10  
 Pull Request: Mengusulkan Perubahan Secara Profesional

---

 🧠 Mengapa Pull Request Itu Penting?

Bayangkan kamu bekerja dalam tim riset. Kamu telah membuat perubahan penting—menambahkan grafik, memperbaiki kesalahan analisis, atau menyusun ulang dokumentasi. Tapi kamu tidak bisa langsung menempelkan perubahan itu ke proyek utama. Mengapa?

Karena dalam dunia kolaborasi, setiap perubahan perlu ditinjau, diperiksa, dan disetujui terlebih dahulu. Inilah tujuan dari Pull Request (PR)—cara profesional dan transparan untuk mengusulkan penggabungan perubahan dari satu branch ke branch utama (`main`).

Pull Request bukan hanya alat teknis, tapi juga alat komunikasi dan diskusi. Ia memungkinkan kamu:
- Menjelaskan apa yang kamu ubah
- Mendapat umpan balik dari tim
- Meningkatkan kualitas kolaborasi

---

 📌 Apa Itu Pull Request?

Pull Request (PR) adalah permintaan resmi untuk menggabungkan branch yang kamu kerjakan ke branch utama repositori (biasanya `main`).

PR bisa kamu kirim ke:
- Proyek milikmu sendiri (jika kamu kerja solo)
- Proyek tim internal (kolaborasi satu tim)
- Proyek publik open-source (kontribusi ke proyek orang lain)

---

 🧪 Ilustrasi Kasus

Kamu membuat branch baru `tambah-analisis-usia` dan menulis skrip baru di `code/analisis_usia.py`.

Setelah commit dan push branch ke GitHub, kamu ingin menyatukannya ke `main`. Tapi bukan dengan merge langsung, melainkan dengan PR, agar tim bisa melihat dulu, memberi saran, atau menyetujui perubahanmu.

---

 🔧 Langkah-Langkah Membuat Pull Request

 1. Push Branch ke GitHub

Setelah kamu selesai bekerja di branch dan commit, buka GitHub Desktop:

- Klik tombol Push origin untuk mengunggah branch ke GitHub

 2. Buka Repo di GitHub.com

Klik Repository → View on GitHub

GitHub akan otomatis menampilkan banner:
```
Compare & pull request
```
Klik tombol itu.

 3. Isi Detail Pull Request

Akan muncul form berisi:

- Title: Judul PR, contoh: `Tambah analisis distribusi usia`
- Description: Jelaskan perubahan yang kamu buat, misalnya:
  > “Menambahkan skrip analisis_usia.py, visualisasi distribusi umur berdasarkan data.”

Kamu juga bisa:
- Mention orang lain: `@nama-teman`
- Tautkan issue terkait: `Fixes 12`

 4. Klik “Create Pull Request”

🎉 PR kamu sekarang aktif dan siap ditinjau!

---

 🧵 Apa yang Terjadi Setelah PR Dibuat?

GitHub akan membuat halaman khusus untuk PR kamu. Di halaman ini, tim atau kolaborator bisa:

- Melihat perbedaan file (diff view)
- Memberi komentar baris per baris
- Menyetujui atau meminta revisi
- Menyelesaikan konflik jika perlu

Jika semua setuju, PR akan di-merge ke `main`.

---

 👀 Review & Diskusi di PR

PR bukan hanya untuk menggabungkan kode, tapi juga:
- Ajang diskusi ide
- Alat pelacak progres
- Tempat pembelajaran kolaboratif

Kolaborator bisa klik tombol:
- Approve: Menyetujui PR
- Request changes: Meminta perbaikan dulu
- Comment: Memberi masukan tanpa mengubah status

---

 🌿 Merge PR

Jika PR kamu sudah disetujui, GitHub akan menyediakan tombol:
Merge pull request

Kamu bisa:
- Langsung merge
- Pilih metode merge (merge biasa, squash, atau rebase)

Setelah merge selesai, kamu akan ditawari untuk:
- Hapus branch yang sudah tidak dibutuhkan

---

 🧠 Keuntungan Menggunakan Pull Request

| Manfaat                            | Penjelasan                                                           |
|------------------------------------|----------------------------------------------------------------------|
| ✅ Revisi terstruktur               | Semua perubahan tercatat dan bisa dibatalkan jika perlu              |
| ✅ Transparansi                    | Siapa pun di tim bisa melihat siapa mengubah apa dan kapan           |
| ✅ Review kolaboratif              | Dapat komentar, ide, atau koreksi sebelum perubahan diterima         |
| ✅ Sejarah proyek lebih rapi       | PR membentuk narasi perubahan proyek secara bertahap dan logis       |

---

 💡 Tips Pull Request Profesional

- Beri nama PR yang jelas dan deskriptif
- Jelaskan tujuan dan perubahan secara ringkas
- Buat PR per fitur, jangan campur banyak topik
- Balas komentar reviewer dengan sopan dan terbuka

---

 ✅ Checklist Bab Ini

- [ ] Membuat branch dan melakukan perubahan
- [ ] Commit dan push branch ke GitHub
- [ ] Mengisi detail PR dengan baik
- [ ] Mengikuti proses review dan diskusi
- [ ] Melakukan merge setelah disetujui

---

 🚀 Bab Selanjutnya: Review Pull Request dari Orang Lain

Di Bab 11, kamu akan berperan sebagai reviewer: meninjau Pull Request orang lain, memberi komentar, dan menyetujui atau meminta revisi.

Karena di dunia GitHub, semua orang bisa jadi kontributor—dan semua orang bisa jadi pengulas yang bijak.

