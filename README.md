# OSINT Sample Script

Repository ini berisi script sederhana untuk melakukan pengumpulan informasi menggunakan metode OSINT (Open-Source Intelligence). Script ini mencakup pencarian terhadap:

- **IP Address**  
- **Nomor Telepon**  
- **NIK (Nomor Induk Kependudukan)**  
- **Pencarian di Google**  

---

## Screenshot
Berikut adalah tampilan saat script dijalankan:

![Screenshot](Screenshot_2024-10-24-05-41-38-221_com.termux.jpg)

---

## Prerequisites
Pastikan lingkungan kamu memiliki beberapa package berikut:
- `bash`  
- `git`  
- `wget`  
- `ruby`  
- `cowsay`  
- **lolcat** (instal menggunakan `gem`)

### Cara Install Dependensi (di Termux)
```bash
pkg update && pkg upgrade
pkg install bash git wget ruby cowsay
gem install lolcat
git clone https://github.com/GALIRUS404/Osint
cd Osint
bash osint.sh
