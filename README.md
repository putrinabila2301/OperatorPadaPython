## Lab 1

# Penggunaan end
Fungsi print() berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
contoh kode:
print('A', end="")  
print('B', end="")  
print('C', end="")  
print()  
print('X')  
print('Y')  
print('Z')
output yang di dapat:

![gambar web git-scm](https://github.com/putrinabila2301/latihan-2/blob/master/img/img_1.png)

#Penggunaan Separator
"sep" pada python di gunakan sebagai pembatas antara output yang di hasilkan.
contoh kode:
 w, x, y, z = 10, 15, 20, 25  
print(w, x, y, z, sep=',')  
print(w, x, y, z, sep='')  
print(w, x, y, z, sep=':')  
print(w, x, y, z, sep='- - - - -')
output yang didapat:

![gambar web git-scm](https://github.com/putrinabila2301/latihan-2/blob/master/img/img_2.png)

# Penggunaan String Format
string format di gunakan ketika kita ingin mengatur print output menjadi apa yang kita mau.
contoh kode:
# String yang belum di format
print(0, 10 ** 0)  
print(1, 10 ** 1)  
print(2, 10 ** 2)  
print(3, 10 ** 3)  
print(4, 10 ** 4)  
print(5, 10 ** 5)  
print(6, 10 ** 6)  
print(7, 10 ** 7)  
print(8, 10 ** 8)  
print(9, 10 ** 9)  
print(10, 10 ** 10)
output:

![gambar web git-scm](https://github.com/putrinabila2301/latihan-2/blob/master/img/img_3.png)


## Lab 2
Lab 2 membahas tentang bagaimana cara memasukan input, menghitung dan mengubah tipe data serta membuat format print yang akan di cetak ke output.
contoh kode:
a = input("masukan nilai a:")
b = input("masukan nilau b:")
print("variabel a =", a)
print("variabel b =", b)
print('hasil penggabungan {1} & {0} = %d'.format(a, b))

a = int(a)
b = int(b)

print('hasil penjumlahan {1} & {0} = %d'.format(a, b)%(a + b))
print('hasil pembagian {} & {} = %d'.format(a, b) % (a / b))
output yang didapat:

![gambar web git-scm](https://github.com/putrinabila2301/latihan-2/blob/master/img/img_4.png)

