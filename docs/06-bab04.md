

 📂 Bab 4  
 Menyusun Struktur Folder Proyek Riset dengan Git

---

 🧩 Mengapa Struktur Folder Itu Penting?

Pernah membuka folder lama dan bingung sendiri dengan isinya?  
Misalnya, file bernama `datafix_baru.csv`, lalu `code_final_rev2.py`, dan `tugas_update_FINAL.docx`. Kamu tidak ingat lagi file mana yang seharusnya digunakan.  
Itulah kenapa struktur folder yang rapi dan konsisten sangat penting dalam proyek riset.

Dalam dunia Git, struktur folder bukan sekadar estetika—ia adalah fondasi keteraturan. Git mencatat perubahan berdasarkan file dan folder. Jadi, jika kamu menata proyek sejak awal, Git akan menjadi lebih mudah digunakan, dokumentasi lebih jelas, dan kolaborasi lebih lancar.

Bab ini akan membimbingmu menyusun folder proyek yang profesional, rapi, dan siap untuk dokumentasi GitBook maupun publikasi ke Zenodo.

---

 🗂️ Struktur Dasar Proyek Riset

Mari kita mulai dari struktur paling umum yang bisa digunakan untuk hampir semua jenis riset digital.

```
riset-ku/
├── data/
│   └── dataset.csv
├── code/
│   └── analisis.py
├── docs/
│   └── latar-belakang.md
├── .gitignore
└── README.md
```

Mari kita jelaskan satu per satu:

- `data/`: Menyimpan semua dataset, baik mentah maupun bersih.
- `code/`: Tempat menyimpan skrip pemrosesan data, analisis, atau visualisasi.
- `docs/`: Folder dokumentasi dalam format Markdown—ini yang akan dihubungkan ke GitBook.
- `.gitignore`: File konfigurasi agar Git tidak melacak file tertentu.
- `README.md`: Penjelasan umum isi proyek. Wajah depan repositori kamu.

---

 🧭 Langkah Menyusun Folder

 1. Buka Folder Proyek Kamu

Gunakan Finder (atau File Explorer) dan buka folder tempat kamu membuat repositori Git sebelumnya, misalnya `riset-ku`.

 2. Buat Tiga Folder Utama

Buat tiga folder dengan nama:

- `data`
- `code`
- `docs`

Pastikan semua huruf kecil dan tanpa spasi untuk konsistensi.

 3. Tambahkan File Contoh (Opsional)

Agar lebih jelas dan bisa langsung dicoba, kamu bisa membuat beberapa file dummy di dalamnya:

- `data/sample.csv`
- `code/analisis.py`
- `docs/latar-belakang.md`

Cukup isi dengan beberapa baris teks, misalnya:

sample.csv
```
id,nama,usia
1,Ani,21
2,Budi,22
```

analisis.py
```python
print("Analisis sederhana dimulai...")
```

latar-belakang.md
```markdown
 Latar Belakang

Proyek ini bertujuan untuk memahami pola data sosial melalui analisis sederhana.
```

---

 📦 Apa Manfaat Folder Terpisah?

- Keterbacaan tinggi: Tim bisa langsung tahu di mana letak kode atau data.
- Reproducibility: Publikasi ilmiah yang terbuka butuh struktur proyek yang jelas.
- Integrasi mudah ke GitBook: Folder `docs/` akan langsung terbaca sebagai halaman buku.
- Manajemen konflik Git lebih mudah: Saat file tersebar acak, risiko tabrakan lebih tinggi.

---

 🧽 Tambahkan File `.gitignore`

Git mencatat semua file, termasuk file sementara atau besar—kecuali kamu minta Git mengabaikannya.  
Gunakan file `.gitignore` untuk menjaga kebersihan repositori.

 Contoh isi `.gitignore`

```
 File sistem
.DS_Store

 Folder cache Python
__pycache__/

 Dataset besar
data/.zip
data/.tar.gz

 Log dan file sementara
.log
.tmp
```

Kamu bisa membuat file `.gitignore` langsung dari GitHub Desktop:  
Repository → Open in Terminal → `touch .gitignore`, atau buat secara manual lewat TextEdit.

---

 📝 Lakukan Commit Perubahan

Setelah kamu membuat folder dan file dummy:

1. Buka GitHub Desktop
2. Kamu akan melihat perubahan terdeteksi otomatis
3. Di kolom summary, isi misalnya:  
   `Buat struktur folder awal dan file dummy`
4. Klik Commit to main

Repositorimu sekarang memiliki bentuk yang rapi dan siap berkembang!

---

 ✅ Checklist Bab Ini

- [ ] Membuat folder `data/`, `code/`, dan `docs/`
- [ ] Menambahkan file dummy sebagai contoh
- [ ] Membuat file `.gitignore`
- [ ] Melakukan commit perubahan via GitHub Desktop

---

 🚀 Bab Selanjutnya: Commit & .gitignore

Di Bab 5, kamu akan mempelajari lebih dalam tentang apa yang sebenarnya terjadi saat kamu commit, dan bagaimana Git memperlakukan file-file berbeda tergantung isi `.gitignore`.

Kita akan bahas bagaimana Git “mengingat” dan “melupakan” hal-hal tertentu—dengan elegan.

---

