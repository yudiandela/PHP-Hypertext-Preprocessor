# String PHP

String adalah kumpulan - kumpulan dari beberapa karakter, contoh nya seperti "Hello World!".

## Fungsi bawaan untuk manipulasi String di PHP

Dalam bab ini kita akan melihat beberapa fungsi yang biasa digunakan untuk memanipulasi string, antara lain :

### strlen() - Menghitung Jumlah Karakter dalam String

**strlen()** sendiri memiliki fungsi untuk mengembalikan jumlah / panjang dari string tersebut.

contoh :

file strlen_example.php

```
<?php

echo strlen("Hello world!"); // hasilnya 12

?>
```

### str_word_count() - Menghitung Jumlah Kata dalam String

**str_word_count()** akan menghitung jumlah kata dalam sebuah string.

contoh :

str_word_count_example.php

```
<?php

echo str_word_count("Hello world!"); // hasilnya 2

?>
```

### strrev() - Membalikkan teks dari sebuah String

strrev() akan membalikkan teks dari sebuah string.

contoh :

strrev_example.php

```
<?php

echo strrev("Hello world!"); // hasilnya !dlrow olleH

?>
```

### strpos() - Cari Teks Dalam String

**strpos()** mencari teks tertentu dalam sebuah string. Jika teks tersebut ditemukan, maka akan dikembalikan posisi dari karakter kecocokan pertama. Jika tidak ditemukan kecocokan, itu akan mengembalikan **FALSE**.

contoh :

strpos_example.php

Cari teks "world" di string "Hello world!":

```
<?php

echo strpos("Hello world!", "world"); // hasilnya 6

?>
```

Catatan Penting : Posisi karakter pertama dalam string adalah 0 (bukan 1).

## str_replace() - Mengganti Teks Dalam String

str_replace() akan menggantikan beberapa karakter dengan beberapa karakter lain dalam sebuah string.

contoh

str_replace_example.php

Ganti teks "world" dengan "PHP":

```
<?php

echo str_replace("world", "PHP", "Hello world!"); // hasilnya Hello PHP!

?>
```

## Referensi

Untuk referensi lengkap dari semua fungsi string, buka [Referensi String PHP](https://www.w3schools.com/php/php_ref_string.asp) di situs [w3schools.com](https://www.w3schools.com).

Referensi string PHP berisi deskripsi dan contoh penggunaan, untuk setiap fungsi!
