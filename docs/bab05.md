

 📝 Bab 5  
 Memahami Commit dan .gitignore dalam Git

---

 🧠 Mengapa Commit Itu Penting?

Bayangkan kamu sedang menyusun laporan. Kamu menulis bab demi bab, lalu simpan file setiap malam. Tapi kamu menyimpannya di atas versi lama, tanpa tahu apa yang berubah. Tiba-tiba kamu ingin kembali ke versi minggu lalu, tapi file-nya sudah ditimpa. Panik, ya?

Dengan Git, kamu tidak perlu mengalami hal itu.  
Karena Git menyimpan riwayat versi setiap kali kamu membuat commit.  
Dan commit bukan hanya "simpan biasa", tapi "simpan dengan catatan".

---

 📌 Apa Itu Commit?

Commit adalah proses menyimpan snapshot (cuplikan) kondisi proyek kamu saat itu.  
Setiap commit menyimpan:
- Perubahan file
- Waktu perubahan
- Nama pembuat
- Dan pesan penjelas (commit message)

Git bekerja seperti buku harian proyekmu. Kamu bisa:
- Menelusuri siapa melakukan apa
- Kembali ke versi sebelumnya
- Menganalisis perkembangan proyek

---

 🔄 Proses Commit Langkah demi Langkah

Mari kita pahami alurnya secara praktis:

 1. Kamu mengubah file  
Misalnya, menambahkan grafik baru ke `analisis.py`.

 2. Git mendeteksi perubahan  
GitHub Desktop akan menunjukkan file mana yang berubah.

 3. Kamu menulis pesan commit  
Pesan singkat seperti:  
`Tambah visualisasi data usia`

 4. Kamu klik Commit to main  
Git menyimpan perubahan dan menandainya dengan ID unik.

---

 ✏️ Tips Menulis Commit Message yang Baik

Commit message sebaiknya:
- Spesifik: Hindari "update" atau "fix"
- Ringkas tapi jelas: "Perbaiki bug visualisasi di bar chart"
- Gunakan kata kerja aktif

> 🌟 Ingat: commit adalah catatan historis. Tulis seolah-olah orang lain akan membaca dan menilai proyekmu!

---

 🧽 Memahami .gitignore

Git itu rajin. Terlalu rajin, malah. Ia akan melacak semua file dalam foldermu, termasuk file sementara, file sistem, dan data mentah besar—kecuali kamu bilang “jangan ikutkan”.  
Dan di sinilah `.gitignore` berperan.

---

 📁 Apa Itu `.gitignore`?

`.gitignore` adalah file teks sederhana yang memberi tahu Git:  
“Jangan lacak file ini atau folder ini.”

Contoh kasus:
- Kamu punya file `.DS_Store` (file sistem macOS)? Masukkan ke `.gitignore`
- Kamu simpan dataset besar `.zip`? Abaikan juga!
- Folder `__pycache__/` dari Python? Jelas, harus diabaikan.

---

 🧪 Contoh Isi `.gitignore`

```bash
 File sistem
.DS_Store

 Python
__pycache__/
.pyc

 Dataset besar
data/.zip
data/.tar.gz

 Log
.log
```

---

 📄 Cara Membuat `.gitignore`

1. Buka folder proyek `riset-ku`
2. Buat file baru bernama `.gitignore` (perhatikan titik di awal!)
3. Tambahkan daftar file atau pola yang ingin kamu abaikan
4. Simpan, lalu commit via GitHub Desktop

> Catatan: Git hanya akan mengabaikan file yang belum terlanjur dicatat. Jadi, kalau kamu ingin mengabaikan `data/besar.zip`, pastikan file itu belum pernah kamu commit sebelumnya.

---

 🔎 Bagaimana Mengetahui File Diabaikan?

GitHub Desktop akan otomatis menyembunyikan file yang termasuk daftar `.gitignore`.  
Kalau kamu ingin melihat file yang diabaikan secara manual (di Terminal):

```bash
git status --ignored
```

---

 🧠 Analogi Sederhana

- Commit itu seperti memotret kondisi kamar kerjamu.
- .gitignore itu seperti menutup tirai untuk sudut-sudut kamar yang berantakan. Git tetap memotret, tapi hanya bagian yang kamu izinkan.

---

 ✅ Checklist Bab Ini

- [ ] Menambahkan atau mengubah file dalam proyek
- [ ] Menulis pesan commit yang informatif
- [ ] Membuat file `.gitignore` dengan pola file yang tepat
- [ ] Commit `.gitignore` untuk menjaga kebersihan repo

---

 🚀 Bab Selanjutnya: Sinkronisasi ke GitHub

Di Bab 6, kamu akan membawa proyekmu dari laptop ke cloud:  
melakukan push ke GitHub. Artinya, kamu menyimpan salinan proyek ke internet—aman, bisa diakses dari mana saja, dan siap untuk kolaborasi.

Git akan membantumu menyimpan. Tapi GitHub membantumu berbagi.

