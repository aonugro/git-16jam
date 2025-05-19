

 🌿 Bab 8  
 Branching: Bekerja Paralel Tanpa Takut Merusak

---

 🌉 Mengapa Branch Itu Penting?

Bayangkan kamu sedang menulis laporan riset. Tiba-tiba kamu ingin mencoba pendekatan analisis baru. Kamu belum yakin apakah akan berhasil, dan tentu saja kamu tidak ingin merusak dokumen utama. Apa yang kamu lakukan?

Kalau kamu menggunakan Git, jawabannya adalah:  
Buat branch.

Branch atau cabang memungkinkan kamu membuat jalur kerja baru tanpa mengganggu versi utama. Layaknya menulis di salinan buku catatan yang bisa kamu gabungkan kembali ke salinan utama kapan saja.

Di bab ini, kita akan:
- Memahami konsep branching
- Membuat branch baru lewat GitHub Desktop
- Melakukan perubahan terpisah
- Kembali dan menggabungkan (merge) hasilnya ke versi utama

---

 🧠 Apa Itu Branch?

Secara sederhana:  
Branch adalah jalur paralel dari proyek utama yang bisa kamu utak-atik tanpa mengubah isi branch utama (`main`).

Setiap repositori Git secara default punya satu branch utama bernama `main`.  
Kalau kamu buat branch baru (misalnya `eksperimen-grafik`), Git akan menyalin kondisi terakhir dari `main`, dan kamu bisa bebas mengedit di sana.

---

 🧪 Contoh Nyata

Misalnya kamu sedang menganalisis data dan ingin mencoba:
- Mengganti grafik dari pie chart ke bar chart
- Menambahkan analisis baru

Kamu tidak ingin merusak versi `main` yang sudah stabil. Maka kamu bisa:

1. Buat branch baru: `grafik-baru`
2. Ubah kode sesuka hati
3. Coba dan evaluasi hasilnya
4. Jika sukses, kamu gabungkan kembali ke `main`
5. Jika gagal, cukup hapus branch → `main` tetap aman

---

 📥 Membuat Branch di GitHub Desktop

1. Buka GitHub Desktop
2. Pastikan proyek `riset-ku` terbuka
3. Klik menu Branch → New Branch...
4. Nama branch: misalnya `uji-korelasi`
5. Klik Create Branch

Secara otomatis, kamu akan berpindah ke branch tersebut.  
Statusnya akan terlihat di kiri atas:  
`Current branch: uji-korelasi`

---

 ✍️ Lakukan Perubahan di Branch

Misalnya kamu:
- Edit `code/analisis.py`
- Tambahkan satu metode baru

Setelah selesai:
1. Commit perubahan seperti biasa
2. (Opsional) Push ke GitHub agar branch juga tersimpan online

---

 📁 Melihat Semua Branch

Di GitHub Desktop:
- Klik dropdown nama branch (pojok kiri atas)
- Kamu bisa berpindah ke branch lain (misalnya kembali ke `main`)
- Git akan memuat ulang file sesuai isi branch yang aktif

> Catatan penting: File yang kamu lihat tergantung dari branch aktif. Jadi hati-hati saat membuka dan menyimpan file.

---

 🔄 Kembali ke Main & Merge

Setelah kamu puas dengan isi branch `uji-korelasi`, kamu bisa menggabungkannya kembali ke branch utama.

Langkah-langkah:
1. Pindah ke branch `main` di GitHub Desktop
2. Klik Branch → Merge into current branch
3. Pilih `uji-korelasi`
4. Klik Merge

🎉 Selesai! Perubahan dari `uji-korelasi` sekarang ada di `main`.

---

 ⚔️ Apa yang Terjadi Jika Ada Konflik?

Kalau kamu dan tim mengedit file yang sama di dua branch berbeda, Git akan memberi tahu bahwa terjadi konflik saat merge.

GitHub Desktop akan menampilkan tanda konflik dan memintamu memilih:  
- Bagian dari branch `main`  
- Bagian dari branch `uji-korelasi`  
- Atau menggabungkan secara manual

Kita akan bahas lebih dalam soal konflik di Bab 12.

---

 🔁 Ringkasan Alur Branch

1. Buat branch baru → `fitur-x`
2. Pindah ke branch itu
3. Lakukan perubahan dan commit
4. Kembali ke `main`
5. Merge `fitur-x` ke `main`

---

 💡 Tips Praktis

| Tips                                      | Penjelasan                                                                 |
|-------------------------------------------|-----------------------------------------------------------------------------|
| Gunakan nama branch yang deskriptif      | Misalnya: `tambah-bab-metodologi`, `analisis-korelasi`                     |
| Satu branch untuk satu fitur / percobaan | Jangan kerjakan banyak hal dalam satu branch                               |
| Hapus branch yang tidak dibutuhkan lagi  | Supaya proyek tetap bersih                                                 |
| Push branch ke GitHub                    | Agar tim bisa melihat atau membantu                                         |

---

 ✅ Checklist Bab Ini

- [ ] Membuat branch baru di GitHub Desktop
- [ ] Melakukan perubahan dalam branch
- [ ] Commit dan (opsional) push ke GitHub
- [ ] Pindah ke `main` dan melakukan merge

---

 🚀 Bab Selanjutnya: Penggabungan dan Penyelesaian Konflik

Di Bab 9, kamu akan belajar lebih dalam tentang merge dan menyelesaikan konflik antar branch.  
Karena kadang saat dua ide bagus bertemu… mereka butuh sedikit kompromi 😄

