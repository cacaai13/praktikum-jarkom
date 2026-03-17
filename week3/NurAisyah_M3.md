# LAPORAN PRAKTIKUM JARKOM MODUL 3 HTTP

Nama: Nur Aisyah Luhur Pambudi
Kelas: IF-04-02
NIM: 103072430015

## 3.2 Basic HTTP GET/response interaction
**A. Langkah-langkah:**
1. Jalankan Wireshark terlebih dahulu.
2. Mulai capture paket
3. Gunakan filter "http" supaya yang ditampilkan hanya http saja.
4. Buka URL *http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file1.html*.
5. Jika sudah dibuka URL nya, lalu beralih lagi ke Wireshark dan stop capturing packets (logo stop bewarna merah).
6. Terlihat pada jendela daftar paket menunjukkan ada 2 pesan HTTP yang tertangkap: pesan GET dan pesan respons dari server ke browser.

**B. Hasil:**


### 3.2.1 HTTP CONDITIONAL GET/response interaction
**A. Langkah-langkah:**
1. Bersihkan cache browser terlebih dahulu.
2. Mulai capture paket.
3. Buka URL *http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file2.html*, akan ditampilkan 5 baris sederhana.
4. Refresh halaman browser.
5. Jika sudah direfresh, lalu beralih lagi ke Wireshark dan stop capturing packets (logo stop bewarna merah).
6. Gunakan filter "http" untuk menampilkan http saja di jendela daftar paket.

**B. Hasil:**


## 3.3 Retrieving Long Documents
**A. Langkah-langkah:**
1. Bersihkan cache browser terlebih dahulu.
2. Mulai capture paket.
3. Buka URL *http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file3.html*, akan ditampilkan Bill of Rights AS.
4. Jika sudah dibuka URL-nya, lalu beralih lagi ke Wireshark dan stop capturing packets (logo stop bewarna merah).
5. Gunakan filter "http" untuk menampilkan http saja di jendela daftar paket.

**B. Hasil:**


## 3.4 HTML Documents dengan Embedded Objects
**A. Langkah-langkah:**
1. Bersihkan cache browser terlebih dahulu.
2. Mulai capture paket.
3. Buka URL *http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file4.html*.
4. Jika sudah dibuka URL-nya, lalu beralih lagi ke Wireshark dan stop capturing packets (logo stop bewarna merah).
5. Gunakan filter "http" untuk menampilkan http saja di jendela daftar paket.

**B. Hasil:**

## 3.5 HTT Authentication
**A. Langkah-langkah:**
1. Bersihkan cache browser terlebih dahulu.
2. Mulai capture paket.
3. Buka URL *http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file4.html*.
4. Ketikkan username: "wireshark-students" dan passwordnya: network pada pop up yang muncul saat membuka URL.
4. Jika sudah, lalu beralih lagi ke Wireshark dan stop capturing packets (logo stop bewarna merah).
5. Gunakan filter "http" untuk menampilkan http saja di jendela daftar paket.