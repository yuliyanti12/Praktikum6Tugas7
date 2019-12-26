# Praktikum6Tugas7



Package & Module

Module
• Modul merupakan bagian dari program yang berisi fungsi-fungsi yang
dibuat pada file terpisah.
• Dengan adanya modul-modul yang terpisah, dapat dikelompokkan
sesuai dengan fungsinya dan memudahkan dalam mengelola kode
program.
• Modul dapat dipanggil sesuai dengan kebutuhannya.

Membuat Module
Untuk membuat modul pada Python cukup mudah.
• Buat sebuah file kode program python (ekstensi .py)
• Buat fungsi pada file tersebut.
Contoh:
Filename: example.py
# Python Module example
def add(a, b):
"""This program adds two
numbers and return the result"""
result = a + b
return result

Menggunakan Module
• Untuk menggunakan modul yang telah dibuat cukup menggunakan
perintah import
Contoh:
>>> import example
>>> example.add(4,5.5)
9.5

Import with renaming
# import module by renaming it
import math as m
print("The value of pi is", m.pi)

Package
• Package merupakan namespace yang berisi banyak modul dan paket.
• Package merupakan sebuah direktory yang berisi banyak file-file
modul.
• Setiap package pada Python, harus ada file khusus yang bernama
__init__.py
• File tersebut merupakan file kosong, atau bisa juga diisi dengan
sesuatu.

Membuat Package
Untuk membuat package pada Python cukup mudah.
• Buat sebuah directory (folder), dan tambahkan file kosong dengan
nama __init__.py
• Buat sejumah file kode program python (ekstensi .py) pada folder
tersebut yang berisi fungsi-fungsi (modul program)
