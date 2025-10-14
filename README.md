# 🕵️‍♀️ Operasi Bayangan — Lokasi Rahasia

📍 *Confidential Branch: ops-location*

Jika kamu berhasil sampai ke sini, berarti kamu sudah menembus lapisan pertama operasi ini.  
Namun perjalananmu belum selesai.

---

# 📜 Petunjuk:
- File `map_hint.txt` berisi **potongan kedua (part2)** dari passphrase.
- Gambar `shadow_ops.jpg` memiliki payload yang disembunyikan dengan enkripsi berbasis *steganography*.
- Gabungkan `part1` dari metadata artefak dengan `part2` dari map ini.

🧩 Gunakan passphrase hasil gabungan untuk mengekstrak data:
```bash
steghide extract -sf shadow_ops.jpg

"The shadow never hides forever — only those who dare to look deeper will find the truth."


Kemudian:
```bash
git checkout ops-location
nano README.md
