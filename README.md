print('hasil penjumlahan {1} & {0} = %d'.format(a, b)%(a + b))
print('hasil pembagian {} & {} = %d'.format(a, b) % (a / b))
output yang didapat:
(pct4)
Input dimasukan dengan cara menjalankan program terlebih dahulu, kemudian data dimasukan oleh user (Lihat angka 10 & 6 hijau) dengan diikuti keterangan berupa string "masukan nilai a:". Lalu input di cetak menggunakan fungsi "print()", disertai keterangan "hasil penggabungan" seperti berikut. Kode :
print('hasil penggabungan {1} & {0} = %d'.format(a, b))
Input dicetak kembali disertai dengan format baru menggunakan fungsi "format". Output dari print ini berbentuk tipe data string. Jadi bila kita menjumlahkan input "a" dan "b" dengan operator "+" maka output dari penjumlahan tersebut akan menghasilkan "106" (10 dan 6). Sedangkan "%d" yang seharusnya hanya dilakukan proses dan tidak di cetak ke output, menjadi tercetak kedalam bentuk string atau text (lihat hasil output di atas). Tetapi jika kita menggunakan tipe data, misalnya "/" maka akan terjadi error. Ini disebabkan karena tipe data yang berbentuk string atau text tidak bisa di jumlahkan dengan operator tersebut. Maka dari itu kita perlu mengkonversikan atau mengubah tipe data tersebut menjadi tipe data bersifat bilangan atau angka, misalnya integer atau float.
a = int(a)
b = int(b)
Perintah di atas akan mengkonversikan tipe data sebelumnya ke bentuk tipe data integer. Dengan ini kita bisa menjumlahkan input sebagai angka.
print('hasil penjumlahan {1} & {0} = %d'.format(a, b)%(a + b))
Perintah di atas digunakan untuk mencetak, menghitung dan memformat kembali output yang akan dihasilkan. "{1}" dan "{0}" adalah placeholder dan "%d" adalah perintah untuk mencetak output ke dalam bentuk desimal. Kita bisa mengubah "%d" menjadi, misalnya "%f", dan output yang akan di hasilkan akan dicetak dalam bentuk float.
