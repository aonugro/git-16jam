

 ❓ Bab 17  
 Tanya Jawab Seputar Git: Kesalahan Umum dan Solusinya

---

 🧠 Karena Setiap Pemula Pasti Pernah Bingung

Git adalah alat yang sangat kuat—dan seperti alat yang kuat lainnya, ia juga bisa terasa rumit, menakutkan, dan bahkan membingungkan, terutama di awal. Bahkan pengguna Git yang sudah cukup berpengalaman pun masih bisa bingung saat menemui konflik, kehilangan commit, atau merasa “salah tekan tombol”.

Bab ini hadir sebagai panduan ringan namun praktis untuk menjawab pertanyaan dan masalah umum yang sering dihadapi oleh pengguna baru Git, terutama yang menggunakan GitHub Desktop.

Harapannya, kamu akan merasa lebih tenang, lebih siap, dan lebih percaya diri saat menghadapi “error kecil yang bikin panik besar”.

---

 🙋‍♂️ Pertanyaan 1:  
"Saya salah edit file dan sudah commit. Gimana cara balik ke versi sebelumnya?"

Tenang. Git menyimpan semua commit sebelumnya.  
Kamu bisa:

1. Buka GitHub Desktop
2. Klik tab History
3. Temukan commit sebelum kesalahan
4. Klik kanan commit tersebut → Revert this commit

💡 Ini akan membuat commit baru yang membatalkan perubahan.  
Jadi kamu tetap punya histori lengkap.

---

 🙋‍♀️ Pertanyaan 2:  
"Kenapa file saya nggak muncul di GitHub setelah saya edit?"

Kemungkinan besar kamu:
- Belum commit perubahan  
- Atau sudah commit, tapi belum push ke GitHub

Solusi:
- Buka GitHub Desktop
- Lihat apakah ada file yang berubah (terdeteksi)
- Klik Commit to main
- Lalu klik Push origin

Setelah itu, buka GitHub lewat browser → file akan muncul di sana.

---

 🙋 Pertanyaan 3:  
"Apa bedanya Commit dan Push?"

Analoginya begini:
- Commit: menyimpan perubahan ke "draft lokal" di laptop
- Push: mengirim semua commit ke "cloud" di GitHub

Jadi commit tanpa push = hanya kamu yang tahu  
Push tanpa commit = tidak bisa dilakukan

> Gunakan commit sesering mungkin, push setiap selesai satu bagian kerja besar.

---

 ❓ Pertanyaan 4:  
"Saya mau kembali ke kondisi proyek kemarin. Bisa nggak?"

Bisa banget. Caranya:

- Buka GitHub Desktop
- Klik tab History
- Klik kanan commit yang kamu inginkan → pilih Checkout this commit

Tapi ingat:
- Ini akan membuat kondisi repo seperti saat itu
- Kamu tidak bisa melakukan commit baru sampai kembali ke branch utama

Solusi lebih aman: buat branch dari commit tersebut, lalu eksplorasi di sana.

---

 🛑 Pertanyaan 5:  
"Saya mengalami konflik saat merge. Harus bagaimana?"

Konflik terjadi saat dua versi file berubah di bagian yang sama. Git bingung mana yang harus dipilih.

Solusi di GitHub Desktop:
1. Akan muncul tanda merah: Conflict
2. Klik kanan file → Open in Editor
3. Lihat bagian ini:

```text
<<<<<<< main
Versi A
=======
Versi B
>>>>>>> fitur-xyz
```

4. Pilih salah satu atau gabungkan
5. Hapus tanda `<<<<<<<`, `=======`, dan `>>>>>>>`
6. Simpan → kembali ke GitHub Desktop → Mark as resolved → Commit merge

---

 💡 Pertanyaan 6:  
"Apa yang harus dicommit, dan apa yang sebaiknya diabaikan?"

Simpan (commit):
- Kode `.py`, `.ipynb`, `.r`, `.md`
- File konfigurasi penting: `.gitignore`, `README.md`

Abaikan:
- File dataset besar (`.zip`, `.csv` mentah)
- File hasil (`.pdf`, `.html`, `.log`)
- File sistem (`.DS_Store`, `Thumbs.db`)

Gunakan `.gitignore` untuk mengatur ini.

---

 📂 Pertanyaan 7:  
"Boleh nggak saya hapus folder langsung dari Finder?"

Boleh, tapi sebaiknya:
- Setelah hapus, buka GitHub Desktop
- Commit perubahan itu

Kalau kamu menghapus file atau folder langsung dari komputer, Git tetap akan melacak bahwa file itu hilang, dan kamu bisa commit penghapusan itu sebagai bagian dari histori proyek.

---

 🧯 Pertanyaan 8:  
"Apakah mungkin kehilangan semua commit?"

Sangat jarang. Git sangat aman. Bahkan kalau kamu salah, biasanya histori masih bisa dikembalikan.

Kamu mungkin hanya:
- Berpindah ke branch yang berbeda
- Belum push commit ke GitHub

Tips:
- Sering push ke GitHub
- Jangan hapus repo lokal kecuali yakin
- Buat backup versi `.zip` jika ragu

---

 ✅ Checklist Bab Ini

- [ ] Saya tahu cara mengembalikan commit yang keliru
- [ ] Saya paham perbedaan commit dan push
- [ ] Saya mengerti cara menyelesaikan konflik merge
- [ ] Saya tahu kapan dan bagaimana menggunakan `.gitignore`
- [ ] Saya siap menghadapi error Git tanpa panik

---

 🚀 Bab Selanjutnya: Studi Kasus Mahasiswa  
Di Bab 18, kamu akan melihat bagaimana mahasiswa dari berbagai disiplin (sains, sosial, humaniora) menggunakan Git untuk:
- Menyusun skripsi
- Menganalisis data
- Dan menulis dokumentasi kolaboratif

Karena Git bukan hanya alat untuk programmer—tapi alat berpikir modern.

