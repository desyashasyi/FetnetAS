FETNET - Sistem Penjadwalan Perkuliahan Otomatis
FETNET adalah aplikasi web full-stack yang dibangun untuk mengotomatisasi proses penjadwalan mata kuliah di lingkungan universitas yang kompleks. Aplikasi ini memanfaatkan engine FET (Free Educational Timetabling), sebuah algoritma open-source, untuk menghasilkan jadwal yang optimal dan bebas konflik.

Tentang Proyek
Penjadwalan perkuliahan secara manual adalah proses yang sangat memakan waktu, rumit, dan rentan terhadap kesalahan manusia (human error). Proyek ini lahir dari kebutuhan untuk menciptakan solusi yang efisien, cepat, dan akurat.

FETNET berfungsi sebagai antarmuka manajemen data yang komprehensif. Aplikasi ini memungkinkan administrator untuk mengelola semua komponen penjadwalan seperti data dosen, mata kuliah, ruang kelas, dan batasan waktu. Data yang terstruktur ini kemudian diekspor menjadi file XML dengan format spesifik yang dapat langsung diproses oleh engine algoritma FET untuk menghasilkan jadwal terbaik.

Dibangun Dengan Teknologi:
Backend: PHP & Laravel Framework

Frontend: Livewire, Merry UI & Tailwind CSS

Database: MySQL

Algoritma: FET (engine eksternal)

Fitur Utama
Manajemen Data: CRUD (Create, Read, Update, Delete) untuk data dosen, mata kuliah, kelas, dan batasan waktu.

Otomatisasi Jadwal: Menghasilkan jadwal perkuliahan yang optimal dengan satu kali klik.

Ekspor ke XML: Database dirancang secara spesifik untuk menghasilkan file XML yang sesuai dengan format input yang dibutuhkan oleh engine FET.

Antarmuka Intuitif: Dibangun dengan Merry UI dan Tailwind CSS untuk pengalaman pengguna yang bersih dan mudah digunakan.

Instalasi & Persiapan (Getting Started)
Untuk menjalankan proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

Clone repositori:

Bash

git clone https://github.com/Ashart20/FETNET.git

Masuk ke direktori proyek:

Bash

cd FETNET

Install dependencies PHP (Composer):

Bash

composer install

Salin file environment:

Bash

cp .env.example .env

Generate application key:

Bash

php artisan key:generate

Konfigurasi database Anda di file .env:

Cuplikan kode

DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=nama_database_anda

DB_USERNAME=root

DB_PASSWORD=password_anda

Jalankan migrasi database:

Bash

php artisan migrate

Jalankan server pengembangan:

Bash

php artisan serve

Tangkapan Layar (Screenshots)
<img width="1920" height="1028" alt="image" src="https://github.com/user-attachments/assets/791bbb33-dd99-4902-9037-718d690df5a1" />
<img width="1913" height="913" alt="image" src="https://github.com/user-attachments/assets/a13262e5-cbd4-4d97-80fa-68cb038eb944" />
<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/27b08698-bb21-439a-b27b-898fa40ec3e5" />

Kontak
Asep Sugiharto - asepsugiharto3@gmail.com

Link Proyek: https://github.com/Ashart20/FETNET
# FetnetAS
# FetnetAS
