# Package & Module
# Module
# Pengertian Module
```
•Modul merupakan bagian dari program yang berisi fungsi-fungsi yang dibuat pada file terpisah.
•Dengan adanya modul-modul yang terpisah, dapat dikelompokkan sesuai dengan fungsinya dan memudahkan dalam mengelola kode program.
•Modul dapat dipanggil sesuai dengan kebutuhannya.
```
# Membuat Module

•Buat sebuah file kode program python (ekstensi .py) • Buat fungsi pada file tersebut. Contoh: Filename: example.py

# Python Module example

![72213801-d9112e80-3527-11ea-8940-c67b1345e55a](https://user-images.githubusercontent.com/56240851/72223476-c3d8e600-35a1-11ea-8ec4-2e10aca232df.png)

# Menggunakan Modul
•Untuk menggunakan modul yang telah dibuat cukup menggunakan perintah import Contoh:
![image](https://user-images.githubusercontent.com/56240851/72223515-406bc480-35a2-11ea-9122-64f28c6a54ae.png)


# Package
# Pengertian Package

    •Package merupakan namespace yang berisi banyak modul dan paket. • Package merupakan sebuah direktory yang berisi banyak file-file modul. • Setiap package pada Python, harus ada file khusus yang bernama init.py • File tersebut merupakan file kosong, atau bisa juga diisi dengan sesuatu.
# Membuat Package

Untuk membuat package pada Python cukup mudah. • Buat sebuah directory (folder), dan tambahkan file kosong dengan nama init.py • Buat sejumah file kode program python (ekstensi .py) pada folder tersebut yang berisi fungsi-fungsi (modul program) • Untuk menggunakan package yang telah dibuat cukup menggunakan perintah import

import nama_package.nama_module
atau
from nama_package import nama_module

# Tugas

Buat package dan modul berdasarkan tugas praktikum sebelumnya dengan struktur seperti berikut: • daftar_nilai.py berisi modul untuk: tambah_data, ubah_data, hapus_data, dan cari_data • view_nilai.py berisi modul untuk: cetak_daftar_nilai, cetak_hasil_pencarian • input_nilai.py berisi modul untuk: input_data yang meminta pengguna memasukkan data. • main.py berisi program utama (menu pilihan yang memanggil semua menu yang ada)
# Package Input Nilai

def input_nama():
    global nama
    nama = input("Masukkan Nama        : ")
    return nama

def input_nim():
    global nim
    nim = input("Masukkan NIM         : ")
    return nim

def input_nilaiTugas():
    global nilaiTugas
    nilaiTugas = int(input("Masukkan Nilai Tugas : "))
    return nilaiTugas

def input_nilaiUts():
    global nilaiUts
    nilaiUts = int(input("Masukkan Nilai UTS   : "))
    return nilaiUts

def input_nilaiUas():
    global nilaiUas
    nilaiUas = int(input("Masukkan Nilai UAS   : "))
    return nilaiUas
