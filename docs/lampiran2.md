

 📘 Lampiran 2 – LICENSE

---

 ❓ Apa Itu LICENSE?

File `LICENSE` menjelaskan hak penggunaan atas kode, data, atau dokumentasi dalam repositori kamu.  
Tanpa lisensi, secara hukum orang lain tidak bisa menggunakan, menyalin, atau memodifikasi hasil kerjamu.

---

 📚 Jenis-Jenis Lisensi Open Source (Umum Digunakan)

| Nama Lisensi | Hak Pengguna    | Boleh Dipakai Komersial? | Wajib Mention Penulis? | Boleh Ubah Kode? | Catatan |
|--------------|-----------------|---------------------------|------------------------|------------------|---------|
| MIT          | Bebas pakai, ubah, distribusi | ✅ Ya | ✅ Ya | ✅ Ya | Sangat bebas, populer |
| Apache 2.0| Seperti MIT + perlindungan paten | ✅ Ya | ✅ Ya | ✅ Ya | Cocok untuk perusahaan |
| GPL 3.0  | Bebas tapi harus open-source jika dipakai ulang | ✅ Ya | ✅ Ya | ✅ Ya | Lebih ketat |
| BSD 3-Clause | Mirip MIT, tapi ada batasan nama | ✅ Ya | ✅ Ya | ✅ Ya | Digunakan banyak universitas |
| CC-BY 4.0| Cocok untuk dokumen/data | ✅ Ya | ✅ Ya | ✅ Ya | Cocok untuk dataset & dokumen |
| CC0      | Public domain, tanpa syarat | ✅ Ya | ❌ Tidak wajib | ✅ Ya | Sangat bebas |

---

 ⚙️ Cara Menyiapkan LICENSE

1. Tentukan tujuan kamu:
   - Mau kode bebas dipakai tanpa batas? → MIT
   - Mau orang wajib open-source juga? → GPL
   - Mau lisensi data saja? → CC-BY

2. Di GitHub:
   - Klik "Add file" → "Create new file"
   - Nama file: `LICENSE`
   - GitHub akan bantu pilih template lisensi

3. Atau tulis manual dari template di bawah

---

 📄 Contoh Template: MIT License (Sederhana)

```text
MIT License

Copyright (c) 2025 [Nama Kamu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND...
```

Ganti `[Nama Kamu]` dengan nama atau nama institusi.

---

 📘 Contoh Template: Creative Commons (CC-BY 4.0)

```text
Creative Commons Attribution 4.0 International (CC BY 4.0)

You are free to:
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material
for any purpose, even commercially.

You must give appropriate credit, provide a link to the license, and indicate if changes were made.
https://creativecommons.org/licenses/by/4.0/
```

---

 ✅ Tips
- Letakkan file LICENSE di root repositori
- Tambahkan penjelasan di `README.md` tentang lisensi yang digunakan
- Untuk proyek gabungan (data + kode), kamu bisa gunakan dua lisensi: misalnya MIT untuk kode, CC-BY untuk data

