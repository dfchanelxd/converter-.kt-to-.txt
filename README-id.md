# Kotlin to Text Converter (.kt -> .txt)

Web app sederhana buat convert file `.kt` jadi `.txt` tanpa ribet. Tampilannya dibikin modern (Glassmorphism) biar enak dipandang.

## "Kenapa gak di-rename manual aja?"

Mungkin banyak yang mikir, *"Kan tinggal ganti nama file dari .kt jadi .txt beres?"*

Bener, tapi tools ini dibuat karena beberapa alasan praktis:

1.  **Ribet kalau di HP:** Ganti ekstensi file di Android/iOS itu step-nya lumayan panjang. Harus buka file manager, cari setting, rename, hapus `.kt`, ketik `.txt`. Pake web ini tinggal upload -> download.
2.  **File Asli Tetap Aman:** Kalau rename manual, file `.kt` nya berubah. Kalau pake ini, kita dapet file `.txt` baru tanpa ngerusak source code aslinya.
3.  **Masalah Windows:** Di PC kadang ekstensi file suka ke-hide. Niatnya rename, eh malah jadinya `Main.txt.kt`. Tools ini mastiin formatnya bener-bener berubah.
4.  **Privasi Aman (Client-Side Only):** Ini yang paling penting. Web ini jalan 100% di browser kamu pake JavaScript. Gak ada upload-upload file ke server. Jadi kodingan kamu aman, gak bakal bocor kemana-mana.

## Fitur
- **UI Kaca (Glassmorphism):** Tampilan estetik dengan animasi background.
- **Drag & Drop:** Tinggal geser file, gak perlu klik-klik menu.
- **Offline Ready:** Bisa dipake pas gak ada internet (karena gak butuh server).

## Cara Pakai
Cukup buka file `index.html` di browser (Chrome, Firefox, dll), masukin file `.kt`, terus klik convert. Beres.
