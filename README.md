Tugas Membuat Program Sederhana Untuk Menentukan Bilangan Terbesar Dari Input 3 Bilangan
Algoritmanya
Langkah pertama yaitu menginput bilangan pertama sampai ketiga, berikut contoh syntaxnya:

a = int(input("Masukkan bilangan A: ")
b = int(input("Masukkan bilangan B: ")
c = int(input("Masukkan bilangan C: ")
Lalu kita akan menggunakan statement if untuk menentukan bilangan terbesarnya.

if a>b and a>c:
print(a, "adalah bilangan terbesar")
elif b>a and b>c
print(b, "adalah bilangan terbesar")
elif c>a and c>b
print(c, "adalah bilangan terbesar")
Keterangan : Jika bilangan a lebih besar dari b dan c, maka bilangan a akan di print sebagai bilangan terbesar.Jika
bilangan a bukan bilangan terbesar maka proses akan dilanjutkan ke bilangan b dan seterusnya.
