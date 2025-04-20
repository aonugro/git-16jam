

 🧾 Bab 15  
 Sinkronisasi Proyek Riset ke Zenodo untuk Publikasi Final dan DOI

---

 📢 Saatnya Memublikasikan Karyamu

Setelah berjam-jam menyusun struktur repositori, menulis kode, menata dokumentasi, dan menghubungkannya ke GitBook—kamu kini berada di tahap akhir: mempublikasikan risetmu secara terbuka dan profesional.

Bayangkan kamu menulis laporan luar biasa, tapi disimpan di laci meja. Tidak ada yang membacanya. Tidak ada yang bisa mengutipnya. Tidak ada dampaknya.

Tapi jika kamu menerbitkannya secara terbuka, memberikan DOI (Digital Object Identifier), dan mencantumkannya dalam jurnal atau CV, maka kamu mengubah proyek pribadi menjadi kontribusi nyata untuk ilmu pengetahuan.

Inilah misi utama bab ini: menghubungkan GitHub ke Zenodo dan membuat versi final risetmu dapat diakses dunia.

---

 🌐 Apa Itu Zenodo?

Zenodo adalah layanan repositori ilmiah gratis dan terbuka yang dibuat oleh CERN dan OpenAIRE. Tujuannya:
- Menyimpan proyek, dataset, dokumen, dan kode ilmiah
- Memberikan DOI untuk setiap versi rilis
- Memfasilitasi _open access_ bagi peneliti dan pengembang di seluruh dunia

Zenodo cocok untuk:
- Menyimpan repositori GitHub versi akhir
- Menyediakan DOI untuk digunakan dalam jurnal atau laporan
- Menjaga transparansi dan reproducibility riset

---

 🧭 Langkah-Langkah Sinkronisasi GitHub ke Zenodo

 1. Buat Akun Zenodo

- Buka [https://zenodo.org](https://zenodo.org)
- Klik Sign up
- Gunakan akun GitHub, ORCiD, atau email

 2. Hubungkan Zenodo ke GitHub

- Setelah login, klik ikon profil kanan atas → GitHub
- Beri izin akses ke akun GitHub kamu
- Zenodo akan menampilkan daftar repositori kamu

 3. Aktifkan Sinkronisasi Repo

- Temukan repo `riset-ku`  
- Aktifkan toggle di sampingnya (`✔️ Enable`)
- Zenodo sekarang akan memantau repo tersebut

---

 🔖 4. Buat Release di GitHub

Agar Zenodo mengarsipkan repo, kamu perlu membuat Release.

Caranya:
1. Buka halaman GitHub → klik tab Releases
2. Klik Draft a new release
3. Isi:
   - Tag version: misalnya `v1.0`
   - Release title: “Versi Final Proyek Riset”
   - Deskripsi: ringkasan isi proyek
4. Klik Publish release

🎉 Zenodo akan otomatis:
- Menyalin isi repositori pada saat itu
- Menyimpan file `.zip` dari semua kode dan dokumen
- Menghasilkan DOI unik

---

 🔗 DOI: Kode Akses ke Ilmu Pengetahuan

DOI (Digital Object Identifier) adalah identitas permanen untuk sebuah objek digital.  
Contoh DOI dari Zenodo:

```
10.5281/zenodo.1234567
```

Dengan DOI ini, kamu bisa:
- Menyisipkan kutipan ilmiah
- Menautkan GitBook ke arsip Zenodo
- Menyediakan rujukan di jurnal atau laporan

Kamu juga mendapatkan:
- DOI per versi (misalnya `v1.0`, `v1.1`)
- DOI induk yang merepresentasikan proyek secara keseluruhan

---

 🧬 Menyusun Metadata di Zenodo

Setelah rilis pertama, kamu bisa masuk ke Zenodo dan:
- Menambahkan deskripsi panjang
- Memasukkan penulis (dengan ORCiD jika ada)
- Menyusun kata kunci (keywords)
- Menentukan lisensi (MIT, CC-BY, dll)
- Menyematkan link ke GitBook

Semua ini membuat proyek kamu:
- Lebih mudah ditemukan di Google Scholar
- Terlihat kredibel di mata pembaca akademik

---

 🧠 Tips: Kapan Sebaiknya Rilis?

- Setelah kamu menyusun dokumentasi final
- Setelah file sudah ditinjau ulang (tidak ada typo besar)
- Saat kamu siap membagikannya ke dosen, reviewer, atau publik

Ingat: kamu bisa membuat versi baru (v1.1, v2.0) kapan saja jika ada perubahan. Zenodo akan menyimpan semuanya, lengkap dengan DOI baru.

---

 📋 Contoh Kutipan Proyek

Jika kamu ingin orang lain mengutip proyekmu, gunakan format seperti ini:

```text
Nama, A. (2025). Riset XYZ (v1.0) [Dataset dan Kode]. Zenodo. https://doi.org/10.5281/zenodo.1234567
```

Tambahkan kutipan ini di:
- GitBook (`README.md`)
- Proposal riset
- Skripsi atau artikel ilmiah

---

 ✅ Checklist Bab Ini

- [ ] Sudah punya akun Zenodo
- [ ] Sudah menghubungkan ke GitHub
- [ ] Sudah mengaktifkan repo `riset-ku`
- [ ] Sudah membuat release di GitHub
- [ ] Sudah mendapatkan DOI
- [ ] Sudah menambahkan metadata dan lisensi

---

 🚀 Bab Selanjutnya: Finalisasi & Presentasi Proyek

Di Bab 16, kita akan menutup sesi ini dengan membuat dokumentasi akhir proyek, menyusun versi siap tampil untuk publik, dan merangkum seluruh proses belajar Git dalam 24 jam.

Karena proyek yang baik bukan hanya selesai, tapi siap dibagikan dengan percaya diri.

