# 🧠 Kaliber CTF 2025 – Internal Challenge Repository

Repositori ini berisi **seluruh soal dan aset internal** untuk event **Kaliber CTF 2025**, yang disusun oleh bidang kompetisi **LSO KALIBER Universitas Muhammadiyah Malang**.  
⚠️ **Repositori bersifat privat dan hanya untuk keperluan internal tim penyusun soal.**

---

## 📂 Struktur Folder

```
├── chall/                  # Folder utama untuk tiap kategori soal
│   ├── osint/                  # Soal OSINT (gambar, teks, tautan, dsb.)
│   │      └── Writeup              # Writeup semua soal OSINT  
│   ├── web/                    # Soal Web Exploitation
│   │      └── Writeup              # Writeup semua soal Web Exploitation
│   ├── crypto/                 # Soal Cryptography
│   │      └── Writeup              # Writeup semua soal Cryptography
│   ├── pwn/                    # Soal Binary Exploitation
│   │      └── Writeup              # Writeup semua soal Binary Exploitation
│   ├── forensics/              # Soal Forensics
│   │      └── Writeup              # Writeup semua soal Forensics
│   ├── misc/                   # Soal Miscellaneous
│   │      └── Writeup              # Writeup semua soal Miscellaneous
│   └── reverse/                # Soal Reverse Engineering
│   │      └── Writeup              # Writeup semua soal Reverse Engineering
│
└── README.md               # Dokumentasi utama (file ini)
```

---

## 🏗️ Format Penulisan Soal

Tiap soal disimpan dalam foldernya masing-masing di dalam `chall/<kategori>/`, dengan struktur seperti berikut:

```
chall/<kategori>/<nama_soal>/
│
├── soal.txt          # Deskripsi soal
├── image.jpg         # File yang diberikan ke peserta
```

**Contoh:**
```
chall/osint/twicetagram/
├── soal.txt
├── image.jpg
```

## 📝 Workflow Penambahan Soal

1. **Buat folder challenge** di `chall/<kategori>/<nama_soal>/`
2. **Isi file-file wajib**: 
   - `soal.txt` - Deskripsi soal, flag format, dan informasi challenge
   - File challenge (gambar, zip, script, dll) - File yang akan diberikan ke peserta
3. **Buat writeup** di `chall/<kategori>/Writeup/<kategori>.pdf`
4. **Testing**: Pastikan soal bisa diselesaikan sesuai writeup

---

## 🚀 Deploy ke CTFd

Untuk deploy challenge ke platform CTFd:

1. **Siapkan file challenge:**
   - Jika ada file untuk peserta, compress menjadi zip dengan nama `<nama_soal>.zip`
   - Jika tidak ada file, skip langkah ini
2. **Login ke CTFd admin panel**
3. **Buat challenge baru:**
   - Pilih kategori sesuai folder (OSINT, Web, Crypto, dll)
   - Isi nama challenge
   - Copy-paste deskripsi dari `soal.txt`
   - Set poin sesuai kesulitan
4. **Input flag** sesuai yang ada di `writeup.pdf`
5. **Publish challenge** dan test dari akun peserta

---

## 👥 Tim Penyusun

- **Project Lead:** @ricoagista   
- **Kategori OSINT:** @ricoagista @mrobi27   
- **Kategori Web:** -  
- **Kategori Crypto:** - 
- **Kategori Forensics:** -  
- **Kategori Reverse & Pwn:** -

---

## 🧾 Lisensi

📘 **Private Repository — Internal Use Only**  
Seluruh konten dalam repo ini merupakan hak cipta LSO KALIBER UMM dan **tidak boleh dipublikasikan, disalin, atau digunakan ulang** di luar kepanitiaan Kaliber CTF 2025.

---
