# Employees Payroll Management System

Employees Payroll Management System adalah aplikasi berbasis web yang dibangun menggunakan CodeIgniter 4. Aplikasi ini digunakan untuk mengelola data karyawan dan menghitung gaji mereka secara otomatis.

## Fitur Utama

1. **Departments**: Kelola data departemen dalam perusahaan.
2. **Designations**: Kelola data jabatan karyawan.
3. **Employees**: Tambah, edit, dan hapus data karyawan.
4. **Payrolls**: Hitung gaji karyawan berdasarkan berbagai parameter seperti jam kerja, potongan, dan tunjangan.
5. **Payslips**: Buat dan cetak slip gaji untuk karyawan.
6. **Auth**: Sistem login untuk keamanan akses.

## Prasyarat

Sebelum memulai, pastikan Anda memiliki hal-hal berikut:

- PHP versi 7.3 atau lebih tinggi
- Composer
- Server web seperti Apache atau Nginx
- Database MySQL/MariaDB
- XAMPP (opsional)

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal proyek ini di lingkungan lokal Anda:

1. **Clone Repository**

    ```bash
    git clone https://github.com/mioscape/kelompok-web-programming.git
    cd kelompok-web-programming
    ```

2. **Instal Dependensi**

    ```bash
    composer install
    ```

3. **Salin File .env**

    Salin file `.env.example` menjadi `.env` dan sesuaikan konfigurasi database Anda.

    ```bash
    cp .env.example .env
    ```

4. **Migrasi Database**

    Jalankan migrasi untuk membuat tabel yang diperlukan di database.

    ```bash
    php spark migrate
    ```

5. **Jalankan Server Pengembangan**

    ```bash
    php spark serve
    ```

    Aplikasi sekarang dapat diakses melalui `http://localhost:8080`.  

    Jika menggunakan XAMPP, salin folder proyek ke dalam direktori `htdocs` XAMPP dan akses melalui `http://localhost/kelompok-web-programming/Main`.


## Struktur Direktori

Beberapa direktori penting dalam proyek ini:

- **app/Controllers**: Berisi controller aplikasi.
- **app/Models**: Berisi model aplikasi.
- **app/Views**: Berisi view aplikasi.

## Penggunaan

1. **Login**: Masuk ke aplikasi menggunakan kredensial yang sudah ditentukan.
2. **Manajemen Departments**: Tambah, edit, atau hapus data departemen.
3. **Manajemen Designations**: Tambah, edit, atau hapus data jabatan.
4. **Manajemen Employees**: Tambah, edit, atau hapus data karyawan.
5. **Hitung Payrolls**: Masukkan data yang diperlukan untuk menghitung gaji karyawan.
6. **Buat Payslips**: Buat dan cetak slip gaji untuk karyawan.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori ini dan buat pull request dengan perubahan Anda. Kami sangat menghargai kontribusi Anda!

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT. Lihat file `LICENSE` untuk informasi lebih lanjut.

## Admin Access

- **Email:** me@ihya.dev
- **Password:** admin123