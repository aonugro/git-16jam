

 🎨 Bab 14  
 Memoles Dokumentasi GitBook agar Siap Dipublikasikan

---

 📖 Dokumentasi yang Tidak Hanya Lengkap, Tapi Menarik

Setelah kamu menyusun dokumentasi dalam GitBook, kamu mungkin merasa puas: strukturnya jelas, isinya rapi, dan semua bab sudah tertulis. Tapi pertanyaannya:  
Apakah dokumentasimu siap dibaca oleh orang lain?

Di bab ini, kita akan belajar cara memoles tampilan dan isi GitBook agar layak dibaca oleh:
- Pembimbing skripsi
- Mitra riset
- Reviewer jurnal
- Atau bahkan pembaca umum yang baru pertama kali mengenal proyekmu

Ingat: tampilan memengaruhi persepsi. Dokumentasi yang menarik secara visual dan jelas secara isi akan lebih dipercaya, lebih dihargai, dan lebih sering dirujuk.

---

 🧭 Langkah-Langkah Memoles Dokumentasi

 1. Periksa dan Perbaiki Judul Bab

Gunakan judul yang padat dan bermakna.  
Contoh:

| Sebelum                         | Sesudah                                      |
|--------------------------------|----------------------------------------------|
| Bab 1                          | 1. Pendahuluan: Latar Belakang Penelitian    |
| Bab 2                          | 2. Metodologi: Desain dan Alur Analisis      |
| Bab 3                          | 3. Hasil: Visualisasi dan Temuan             |

Tips: Gunakan angka di depan judul untuk navigasi yang lebih mudah.

---

 2. Tambahkan Gambar dan Grafik (Jika Ada)

GitBook mendukung penambahan gambar dalam Markdown:

```markdown
![Deskripsi gambar](../assets/gambar1.png)
```

Kamu bisa menyimpan gambar di folder `docs/assets/` agar struktur tetap rapi.

Gunakan grafik untuk:
- Menjelaskan metode
- Menyajikan hasil analisis
- Memberi konteks

> 📌 Gambar = penyelamat pembaca visual!

---

 3. Sisipkan Daftar Isi Manual (Opsional)

GitBook membuat sidebar otomatis, tapi kamu juga bisa membuat daftar isi di halaman pembuka (`README.md`):

```markdown
 Daftar Isi

1. [Pendahuluan](latar-belakang.md)
2. [Metodologi](metode.md)
3. [Hasil](analisis.md)
4. [Kesimpulan](kesimpulan.md)
```

Gunakan link relatif agar pembaca bisa melompat antar bab.

---

 4. Tambahkan Lisensi dan Attribution

Di akhir dokumentasi (atau halaman khusus), tambahkan bagian lisensi:

```markdown
 Lisensi

Proyek ini dilisensikan di bawah MIT License.  
Bebas digunakan, disalin, dan dimodifikasi dengan atribusi yang sesuai.
```

Atau untuk dokumentasi:
```markdown
Dokumen ini menggunakan lisensi Creative Commons Attribution 4.0 (CC BY 4.0).
```

Jangan lupa sertakan:
- Nama kontributor
- Tahun publikasi
- Link ke repo GitHub

---

 5. Tambahkan Referensi (Daftar Pustaka)

Jika dokumentasi merujuk ke:
- Literatur ilmiah
- Kode eksternal
- Artikel akademik

Buatlah halaman khusus referensi:

```markdown
 Referensi

1. Chacon, S., & Straub, B. (2014). Pro Git (2nd ed.). Apress.  
   [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2)

2. Pérez-Rodríguez, F. et al. (2020). GitBook as an Educational Tool. Education Sciences.
```

Bisa juga menggunakan numerik, APA, atau gaya bebas yang konsisten.

---

 6. Tambahkan DOI dan Badge

Jika proyekmu telah dipublikasikan melalui Zenodo dan mendapatkan DOI, tampilkan badge di awal dokumentasi:

```markdown
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1234567.svg)](https://doi.org/10.5281/zenodo.1234567)
```

Badge ini membuat proyekmu:
- Lebih kredibel
- Bisa dikutip sebagai karya ilmiah

---

 7. Cek Tampilan di Mode Gelap & Terang

GitBook mendukung dark mode secara otomatis.  
Pastikan warna grafik atau gambar tetap terlihat baik di dua mode tampilan.

---

 ✨ Bonus: Gaya Bahasa & Nada

- Gunakan nada akademis tapi tidak terlalu kaku
- Hindari kalimat panjang yang bertele-tele
- Sisipkan transisi antar bab agar narasi terasa mengalir

Contoh transisi:
> “Setelah membahas metodologi, kini kita akan beralih ke temuan hasil analisis yang kami lakukan.”

---

 ✅ Checklist Bab Ini

- [ ] Semua judul bab sudah jelas dan berurutan
- [ ] Gambar, grafik, atau visual pendukung ditambahkan
- [ ] Lisensi dan attribution tercantum dengan benar
- [ ] Referensi ilmiah disusun rapi di halaman khusus
- [ ] DOI dari Zenodo ditampilkan di awal dokumentasi
- [ ] Link antar halaman dan daftar isi diperiksa
- [ ] Tampilan sudah baik di dark mode dan light mode

---

 🚀 Bab Selanjutnya: Sinkronisasi dan Versi Final

Di Bab 15, kamu akan belajar menyimpan versi akhir dari dokumentasi dan proyekmu ke platform repositori ilmiah seperti Zenodo, untuk mendapatkan DOI resmi dan mempublikasikannya secara terbuka.

GitBook mempercantik isi. Zenodo mengabadikannya.

---

