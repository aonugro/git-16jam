

 🧩 Bab 9  
 Menggabungkan Branch dan Menyelesaikan Konflik

---

 🧠 Mengapa Merge Itu Penting?

Dalam bab sebelumnya, kamu telah membuat branch untuk mencoba ide baru, mengedit kode, atau menulis dokumentasi tambahan.  
Namun semua perubahan di branch belum memengaruhi branch utama (`main`).  
Untuk menjadikan hasil kerjamu bagian dari versi resmi proyek, kamu perlu menggabungkan branch—itulah proses yang disebut merge.

Merge adalah tindakan penting dalam Git karena:
- Ia menyatukan kerja tim tanpa saling menimpa
- Ia memperkuat semangat “coba dulu, gabung nanti”
- Ia memastikan proyek tetap rapi, terstruktur, dan berkembang

Namun merge bisa menimbulkan konflik—dan itu normal. Justru di sinilah kekuatan Git terlihat: ia membantu kamu menyelesaikannya dengan cara yang adil dan transparan.

---

 🔄 Apa Itu Merge?

Merge berarti mengambil semua perubahan dari satu branch (misalnya `fitur-analisis`) dan menggabungkannya ke branch lain (biasanya `main`).

Merge bisa dilakukan:
- Setelah selesai edit di branch eksperimental
- Setelah review Pull Request dari tim
- Atau saat ingin menggabungkan hasil kerja kolaboratif

---

 📚 Contoh Kasus

Misalnya kamu punya dua branch:
- `main`: berisi laporan final
- `fitur-kesimpulan`: kamu sedang menulis bagian kesimpulan

Setelah kamu puas dengan isi `fitur-kesimpulan`, kamu ingin menggabungkannya ke `main`.

---

 🔧 Langkah-Langkah Merge di GitHub Desktop

1. Pastikan Semua Commit Sudah Dilakukan  
   Tidak boleh ada perubahan belum tersimpan di branch mana pun.

2. Pindah ke Branch `main`  
   Di kiri atas GitHub Desktop, pilih branch `main`.

3. Klik Menu Branch → Merge into Current Branch  
   Akan muncul daftar branch lain.

4. Pilih Branch yang Ingin Digabungkan  
   Misalnya: `fitur-kesimpulan`

5. Klik Merge

🎉 Sekarang branch `main` memiliki semua isi dari `fitur-kesimpulan`.

---

 ⚔️ Bagaimana Jika Terjadi Konflik?

Konflik terjadi saat:
- Dua branch mengubah bagian yang sama dalam satu file
- Git tidak tahu perubahan mana yang harus dipertahankan

Contoh sederhana:
- Di branch `main`, kamu tulis:  
  `Hasil analisis menunjukkan tren menurun`
- Di branch `fitur-kesimpulan`, kamu ubah jadi:  
  `Hasil analisis menunjukkan tren meningkat`

Saat kamu merge, Git bingung dan akan menampilkan pesan conflict.

---

 🧩 Menyelesaikan Konflik di GitHub Desktop

Saat terjadi konflik:
1. GitHub Desktop akan memberi tanda `Conflicted` di file yang bentrok.
2. Klik kanan file → Open in editor
3. Kamu akan melihat isi file seperti ini:

```text
<<<<<<< main
Hasil analisis menunjukkan tren menurun
=======
Hasil analisis menunjukkan tren meningkat
>>>>>>> fitur-kesimpulan
```

4. Tugasmu adalah memilih versi mana yang ingin dipertahankan, atau menggabungkan keduanya.
   Misalnya:

```text
Hasil analisis menunjukkan tren menurun di awal, namun meningkat setelah intervensi.
```

5. Setelah selesai edit, hapus semua tanda konflik: `<<<<<<<`, `=======`, `>>>>>>>`

6. Kembali ke GitHub Desktop → klik Mark as resolved
7. Klik Commit merge

🎉 Konflik selesai dengan damai!

---

 🧠 Apa yang Terjadi Setelah Merge?

Setelah merge berhasil:
- Branch `main` akan memuat semua perubahan dari branch yang digabung
- Kamu bisa menghapus branch lama jika tidak diperlukan lagi

Jika kamu melakukan merge di GitHub (bukan di Desktop), biasanya melalui Pull Request dan juga menyediakan tombol “Merge Pull Request”.

---

 💬 Tips Menghindari Konflik

- Pull dulu sebelum edit, terutama saat kerja tim
- Gunakan branch terpisah per fitur
- Hindari edit file yang sama di dua branch
- Komunikasikan siapa mengerjakan apa

---

 🔁 Merge vs Rebase (opsional)

Untuk pemula, merge sudah cukup. Tapi Git juga punya teknik lain: rebase, yaitu menyusun ulang histori commit agar lebih bersih.

Dalam buku ini kita fokus pada merge karena:
- Lebih mudah dipahami
- Riwayat commit tetap lengkap
- Cocok untuk dokumentasi riset yang transparan

---

 ✅ Checklist Bab Ini

- [ ] Sudah melakukan merge dari branch ke `main`
- [ ] Sudah melihat dan memahami contoh konflik
- [ ] Sudah menyelesaikan konflik dengan editor
- [ ] Sudah commit hasil merge

---

 🚀 Bab Selanjutnya: Pull Request dan Review

Di Bab 10, kamu akan belajar cara melakukan Pull Request (PR): metode resmi untuk mengusulkan perubahan di proyek GitHub, terutama saat bekerja dalam tim atau kontribusi ke proyek orang lain.

PR adalah dasar dari kolaborasi profesional berbasis Git.  
Dan kamu akan bisa melakukannya dengan percaya diri.

