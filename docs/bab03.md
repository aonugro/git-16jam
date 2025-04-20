

 💼 Bab 3  
 Mengenal GitHub Desktop dan Membuat Repositori Lokal Pertama

---

 🌱 Awal dari Segalanya

Kini, Git sudah terpasang di MacBook kamu, baik melalui Terminal maupun GitHub Desktop.  
Pertanyaan selanjutnya adalah: Sekarang aku harus ngapain?

Bab ini akan menjadi titik tolak nyata dari petualanganmu bersama Git. Kita tidak akan membahas teori lagi. Kita akan langsung membuat repositori Git pertamamu, dan kamu akan melihat sendiri bagaimana Git mulai bekerja—dengan cara yang ramah pemula: klik-klik, bukan ketik-ketik.

---

 🧭 Sekilas Tentang GitHub Desktop

GitHub Desktop adalah aplikasi resmi dari GitHub yang membantu kamu:
- Membuat repositori Git tanpa Terminal
- Melihat perubahan file dalam bentuk visual
- Commit, push, pull hanya dengan klik
- Mengelola branch tanpa stres

Antarmukanya bersih, minimalis, dan intuitif. Bahkan untuk yang baru pertama kali menggunakan Git, GitHub Desktop terasa seperti pintu masuk yang hangat ke dunia version control.

---

 🏗️ Langkah-Langkah Membuat Repositori Baru

Setelah kamu membuka GitHub Desktop, ikuti langkah-langkah berikut untuk membuat repositori (repo) lokal:

 1. Klik “File” → “New Repository…”

Langkah pertama adalah membuat tempat penyimpanan proyek kamu.  
Bayangkan repositori sebagai laci khusus yang akan mencatat semua perubahan yang kamu lakukan.

 2. Isi Informasi Repo

Akan muncul form isian. Kamu hanya perlu mengisi beberapa hal:

- Name: Nama proyek kamu, misalnya `riset-ku`
- Description (opsional): Misalnya, “Repo untuk dokumentasi dan analisis riset sosial”
- Local Path: Folder di laptop kamu tempat repo disimpan
- Centang “Initialize this repository with a README” supaya ada file awal

Klik tombol Create Repository, dan... 🎉 selesai!  
Kamu sekarang punya repositori Git pertama kamu sendiri.

---

 📁 Apa yang Terjadi di Balik Layar?

Ketika kamu membuat repo, GitHub Desktop otomatis:
- Menambahkan file `.git` tersembunyi yang menyimpan semua histori perubahan
- Membuat file `README.md` sebagai penanda awal proyek
- Menginisialisasi proyek agar siap dicatat oleh Git

Kamu mungkin belum melihat hasil besar, tapi struktur dasar sudah siap. Layaknya menanam benih, ini adalah awal dari segalanya.

---

 ✏️ Coba Edit README.md

Sekarang mari kita buat perubahan kecil agar kamu bisa coba commit pertamamu.

1. Buka folder `riset-ku` di Finder
2. Buka file `README.md` dengan editor teks apa pun (bisa Notes, TextEdit, atau Visual Studio Code)
3. Tambahkan satu baris:  
   ```
   Ini adalah proyek riset pertama saya menggunakan Git!
   ```
4. Simpan file

---

 ✅ Lakukan Commit Pertama

Kembali ke GitHub Desktop. Kamu akan melihat Git secara otomatis mendeteksi perubahan di file `README.md`. Di bagian bawah, ada kolom untuk mengisi:

- Summary: Wajib. Misalnya: `Edit awal README`
- Description: Opsional. Jelaskan lebih detail kalau perlu.

Klik tombol Commit to main, dan… boom! 🎯  
Kamu baru saja mencatat perubahan pertama dalam riwayat proyekmu.

---

 🤔 Apa Itu Commit?

Commit adalah cara Git “memotret” kondisi proyek pada satu waktu.  
Kamu bisa menganggapnya seperti menekan tombol Save As Version. Setiap commit:
- Mencatat perubahan
- Menyimpan catatan waktu
- Menyimpan nama pembuatnya

Dengan commit, kamu bisa kembali ke masa lalu kapan saja.

---

 📌 Tips Tambahan

- Buat commit setiap kali kamu menyelesaikan bagian logis dari kerja kamu (misalnya setelah analisis selesai, atau dokumen diperbarui)
- Beri nama commit yang jelas, misalnya `Tambah penjelasan metode` atau `Import dataset awal`

---

 📋 Checklist Bab Ini

- [ ] Membuka GitHub Desktop
- [ ] Membuat repo lokal bernama `riset-ku`
- [ ] Menulis isi pertama README.md
- [ ] Melakukan commit pertama melalui GitHub Desktop

Kalau semua sudah dicoba, selamat!  
Kamu bukan hanya membaca tentang Git—kamu sudah menggunakannya secara nyata.

---

 🚀 Siap ke Bab Selanjutnya?

Di Bab 4, kamu akan belajar menyusun folder proyek secara rapi:
- Memisahkan antara data, kode, dan dokumen
- Menyiapkan struktur folder yang siap diintegrasikan ke GitBook dan Zenodo

Karena seperti rumah, repositori yang rapi akan lebih nyaman ditempati.

---

