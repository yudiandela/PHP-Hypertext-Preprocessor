# Echo dan Print

Didalam sintaks PHP ada dua output yang bisa digunakan untuk menampilkan hasil dari sintaks - sintaks PHP yaitu `echo` dan `print`.

Disini kita akan membahas lebih dalam tentang bagaimana cara menggunakan `echo` dan `print` tersebut.

## Statement Echo dan Print

Secara kegunaan keduanya merupakan fungsi yang sama - sama untuk menampilkan output dari data ke layar melalui browser.

Sedikit Perbedaannya dari kedua fungsi ini :

- `echo` tidak memiliki nilai balik sementara `print` memiliki nilai balik 1 sehingga dapat digunakan dalam ekspresi.
- `echo` dapat mengambil banyak parameter (walaupun jarang digunakan) sementara `print` hanya dapat mengambil satu argumen.
- `echo` sedikit lebih cepat dari print.

### Statement Echo

- `echo` dapat digunakan dengan atau tanpa tanda kurung

contoh :

```
echo 'Output yang dihasilkan';
```

atau

```
echo ('Output yang dihasilkan');
```

```
Catatan :

Jika menggunakan echo dengan tanda kurung maka anda tidak dapat mengambil banyak parameter.
```

### Statement Print

- `print` dapat digunakan dengan atau tanpa tanda kurung

contoh :

```
print 'Output yang dihasilkan';
```

atau

```
print ('Output yang dihasilkan');
```
