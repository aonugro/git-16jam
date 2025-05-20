

 🌍 Bab 12  
 Kontribusi ke Proyek Open Source dengan Fork dan Pull Request

---

 ✨ Dari Belajar ke Berkontribusi

Selama sebelas bab sebelumnya, kamu telah belajar cara mengelola proyek Git sendiri: membuat repo, menulis dokumentasi, melakukan commit, branch, merge, dan review.

Tapi kini waktunya untuk melangkah keluar dari proyek pribadi dan memasuki dunia yang lebih besar:  
open source.

Open source bukan hanya soal berbagi kode, tapi soal berbagi pengetahuan, membangun komunitas, dan belajar dari proyek nyata.  
Dalam bab ini, kamu akan belajar cara berkontribusi ke proyek GitHub milik orang lain melalui dua langkah utama: fork dan pull request.

---

 🔍 Apa Itu Fork?

Fork adalah tindakan menyalin sebuah repository dari akun orang lain ke akun GitHub kamu sendiri.

Mengapa perlu fork?
Karena kamu tidak punya akses langsung untuk mengubah repo orang lain.  
Dengan fork, kamu bisa:
- Membuat salinan repo
- Mengedit tanpa memengaruhi repo asli
- Lalu mengirim pull request (PR) agar pemilik repo bisa meninjau kontribusimu

---

 🧪 Ilustrasi Nyata

Misalnya kamu menemukan repositori GitHub berisi materi pembelajaran statistika. Kamu melihat ada salah ketik di README atau ingin menambahkan contoh penggunaan.

Kamu tidak bisa langsung mengubah file tersebut. Tapi kamu bisa:
1. Fork repo ke akunmu
2. Edit dan commit perubahan
3. Kirim PR ke repo asli agar pemiliknya bisa mempertimbangkan kontribusimu

---

 🔧 Langkah-Langkah Fork dan Kontribusi

 1. Temukan Repo Publik di GitHub

Coba buka contoh ini:  
🔗 [https://github.com/kodekoding/belajar-gitbook](https://github.com/kodekoding/belajar-gitbook)

Ini adalah repo publik yang bisa kamu fork.

 2. Klik Tombol “Fork”

Di kanan atas halaman repo, klik Fork.  
GitHub akan membuat salinan proyek ke akun kamu, misalnya:  
`https://github.com/akun-kamu/belajar-gitbook`

🎉 Sekarang kamu punya repo pribadi yang identik dengan aslinya.

---

 💻 3. Clone Repo Fork ke GitHub Desktop

1. Buka GitHub Desktop
2. Klik File → Clone Repository
3. Pilih tab GitHub.com
4. Pilih repo hasil fork (`belajar-gitbook`) → klik Clone

Sekarang repo tersebut sudah ada di laptop kamu.

---

 🧱 4. Buat Branch untuk Perubahanmu

Jangan langsung edit di `main`. Buat branch baru agar rapi.

1. Klik Branch → New Branch
2. Misalnya beri nama `perbaiki-readme`
3. Klik Create Branch

---

 📝 5. Lakukan Perubahan

Buka file yang ingin kamu perbaiki. Misalnya, edit `README.md` dan ganti:

```markdown
Belajaar Git dengan GitBook
```

Menjadi:

```markdown
Belajar Git dengan GitBook
```

Simpan perubahan dan commit seperti biasa di GitHub Desktop.

---

 ⬆️ 6. Push dan Kirim Pull Request ke Repo Asli

1. Klik Push origin di GitHub Desktop
2. Kembali ke browser → buka repo fork kamu
3. Klik tombol “Contribute” → “Open pull request”

GitHub akan otomatis mendeteksi bahwa kamu ingin menggabungkan:
- Dari: `akun-kamu/perbaiki-readme`
- Ke: `kodekoding/main`

Isi judul dan deskripsi, lalu klik Create Pull Request

🎉 Kamu baru saja mengirim kontribusi ke proyek open source!

---

 👀 Apa yang Terjadi Selanjutnya?

Pemilik repo akan menerima notifikasi PR.  
Mereka bisa:
- Memberi komentar
- Meminta perbaikan
- Atau langsung menggabungkan perubahan kamu

Jika diterima, nama kamu akan muncul di daftar kontributor.  
Kecil? Mungkin. Tapi itulah langkah awal dalam kontribusi dunia nyata.

---

 🧠 Kontribusi Tidak Harus Besar

Kontribusi open source bisa berupa:
- Memperbaiki typo
- Menambahkan penjelasan yang lebih baik
- Menulis tutorial
- Menambahkan contoh penggunaan kode

Tidak perlu langsung jadi master!  
Yang penting: niat berbagi dan belajar bersama.

---

 ✅ Checklist Bab Ini

- [ ] Fork repo publik ke akun sendiri
- [ ] Clone hasil fork ke GitHub Desktop
- [ ] Membuat branch dan melakukan perubahan
- [ ] Commit dan push perubahan
- [ ] Mengirim Pull Request ke repo asli

---

 🚀 Bab Selanjutnya: Menyusun Dokumentasi di GitBook

Setelah kamu terbiasa berbagi di GitHub, saatnya menyusun dokumentasi yang bisa dibaca seperti buku digital.

Di Bab 13, kamu akan mengenal GitBook—alat yang mengubah folder `docs/` kamu menjadi buku interaktif.

