# Lab8
Tugas Praktikum 8 Mata Kuliah Program Komputer dan Praktek (Lab8)
Deskripsi Program ini merupakan aplikasi berbasis teks untuk mengelola data mahasiswa menggunakan pendekatan Object-Oriented Programming (OOP).

Program ini memiliki kemampuan untuk menambahkan, menampilkan, menghapus, dan mengubah data mahasiswa.

Fitur Program

Menambahkan Data Mahasiswa

Pengguna dapat memasukkan nama dan nilai mahasiswa untuk disimpan.

Menampilkan Data Mahasiswa

Program akan mencetak daftar semua mahasiswa beserta nilainya.

Menghapus Data Mahasiswa

Pengguna dapat menghapus data mahasiswa berdasarkan nama.

Mengubah Data Mahasiswa

Pengguna dapat memperbarui nilai mahasiswa berdasarkan nama.

Menu Interaktif

Program menggunakan menu interaktif untuk memudahkan navigasi pengguna.

Struktur Kelas Class Mahasiswa

Class ini bertanggung jawab untuk mengelola data mahasiswa.

Atribut:

__data_mahasiswa: List privat untuk menyimpan data mahasiswa.

Metode: tambah(nama, nilai): Menambahkan data mahasiswa baru.

tampilkan(): Menampilkan semua data mahasiswa.

hapus(nama): Menghapus data mahasiswa berdasarkan nama.

ubah(nama, nilai_baru) : Mengubah nilai mahasiswa berdasarkan nama.

__find_by_name(nama): Metode privat untuk mencari data mahasiswa berdasarkan nama.

Class Menu

Class ini bertanggung jawab untuk menyediakan antarmuka pengguna.

Atribut:

mahasiswa: Objek dari kelas Mahasiswa.

Metode:

tampilkan_menu(): Menampilkan menu utama dan menangani input pengguna.

__menu_tambah(): Menangani input untuk menambahkan data mahasiswa.

__menu_hapus(): Menangani input untuk menghapus data mahasiswa.

__menu_ubah(): Menangani input untuk mengubah data mahasiswa.

Cara Menjalankan Program

Pastikan Python sudah terinstall pada sistem Anda.

Simpan kode dalam file Python (misalnya main.py).

Jalankan file menggunakan perintah: Tugas Lab 8.py

Pilih opsi pada menu utama sesuai kebutuhan Anda:

1: Tambah Data

2: Tampilkan Data

3: Hapus Data

4: Ubah Data

5: Keluar

Diagram Class
![Flowchart](https://github.com/user-attachments/assets/7f90f2aa-51ac-4872-a766-c9b0f6d2ab1d)

Kode Program
![KodeLab8_1](https://github.com/user-attachments/assets/e636aebc-7289-49c8-9a5c-eb3bbecb60e1)
![KodeLab8_2](https://github.com/user-attachments/assets/2dafd1e4-8a15-4f57-a4c7-a32e04e1b0fd)
![KodeLab8_3](https://github.com/user-attachments/assets/dcde9282-3a4f-4f7f-a69d-83608c1fbf3b)

Hasil Program
![HasilLab8_1](https://github.com/user-attachments/assets/f485c220-dedc-45f6-8939-f37bf61c61c7)
![HasilLab8_2](https://github.com/user-attachments/assets/b9741bc9-dca4-4ce8-a4c9-805ed318bea2)


