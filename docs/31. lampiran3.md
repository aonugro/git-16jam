

 📘 Lampiran 3 – Mengapa Menggunakan Zenodo

---

 ❓ Apa Itu Zenodo?

Zenodo adalah layanan arsip ilmiah milik CERN & OpenAIRE, yang memungkinkan kamu:

- Menyimpan dan membagikan kode, dataset, dan dokumen
- Menerbitkan versi resmi proyek GitHub
- Mendapatkan DOI (Digital Object Identifier) seperti jurnal ilmiah
- Menjadi bagian dari Open Science

💡 Zenodo sangat cocok untuk proyek riset, pendidikan, dokumentasi publik, dan open source.

---

 ✅ 1. Mengapa Menggunakan Zenodo?

 Alasan utama:

| Alasan                            | Penjelasan                                                                 |
|----------------------------------|---------------------------------------------------------------------------|
| 📌 Penerbitan Ilmiah         | Dapatkan DOI resmi untuk proyek GitHub kamu (seperti publikasi jurnal)   |
| 💾 Penyimpanan Jangka Panjang| Disimpan oleh CERN, cocok untuk arsip riset digital                      |
| ♻️ Versi dan Reproduksibilitas| Setiap rilis GitHub bisa diarsipkan dengan versi dan metadata jelas      |
| 🌍 Open Access               | Semua orang bisa akses dan gunakan                                        |
| 🔗 Terhubung dengan GitHub   | Otomatis arsip setiap release GitHub                                   |

---

 👣 2. Cara Membuat Akun Zenodo

1. Buka [https://zenodo.org](https://zenodo.org)
2. Klik Sign Up
3. Bisa daftar pakai:
   - GitHub
   - ORCiD
   - Email biasa
4. Verifikasi email

---

 🔗 3. Integrasi Zenodo dengan GitHub

1. Login ke [Zenodo](https://zenodo.org)
2. Klik ikon profil kanan atas → GitHub
3. Zenodo akan minta izin → izinkan
4. Kamu akan lihat daftar repo GitHub
5. Aktifkan toggle (✔️) untuk repo yang ingin diarsipkan  
   Contoh: aktifkan `riset-ku`

---

 🧪 4. Cara Dapat DOI dari GitHub

Setelah repo terhubung ke Zenodo:

1. Buka halaman GitHub repo kamu
2. Klik "Releases" → Draft a new release
3. Isi:
   - Tag: `v1.0`, `v1.1`, dst.
   - Deskripsi: misalnya "Versi pertama hasil riset"
4. Klik Publish Release

📬 Setelah itu, Zenodo akan:
- Menarik versi rilis dari GitHub
- Menyimpan salinannya di server CERN
- Mengeluarkan DOI unik versi itu

---

 🧭 5. DOI Per Versi vs DOI Induk

Setiap kali kamu buat release, Zenodo akan:

- Buat DOI unik untuk versi itu, misal:  
  ```
  https://doi.org/10.5281/zenodo.1234567
  ```

- Buat juga DOI induk untuk seluruh proyek:  
  ```
  https://doi.org/10.5281/zenodo.1234560
  ```

💡 Kamu bisa:
- Pakai DOI versi kalau ingin kutip versi tertentu (misal v1.0)
- Pakai DOI induk kalau ingin kutip proyek secara umum

---

 📌 Tips Tambahan:

- Setiap file Markdown yang kamu dokumentasikan bisa cantumkan DOI Zenodo di akhir
- Tambahkan badge DOI ke README repo GitHub kamu:

```markdown
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1234567.svg)](https://doi.org/10.5281/zenodo.1234567)
```

---

 🧪 Tugas Mandiri:
1. Sudah punya akun Zenodo?
2. Sudah hubungkan repo GitHub kamu?
3. Sudah buat release dan dapat DOI?
4. Sudah cantumkan DOI di README atau GitBook?

