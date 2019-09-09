# Variabel PHP

## Definisi

Secara fungsi variabel adalah sebuah `wadah` untuk menetapkan sesuatu informasi awal yang kita inginkan.

Didalam PHP untuk menuliskan sebuah Variabel kita tidak perlu atau tidak diharuskan menuliskan tipe data yang akan digunakan, PHP akan dengan otomatis mengenal tipe data apa yang kita input.

## Cara Membuat / Mendeklarasikan Variabel PHP

Di PHP, variabel dimulai dengan tanda `$`, lalu diikuti dengan nama variabel :

contoh :
`basic-variable.php`

```
<?php
$text = "Hello world!";
$angka = 5;
$koma = 10.5;
?>
```

Apabila kita eksekusi / jalankan code diatas maka `$text` (Variabel Text) meyimpan sebuah nilai dengan isian string `Hello World!` serta `$angka` menyimpan sebuah nilai dengan isian angka dengan nilai `5` dan `$koma` akan menyimpan sebuah nilai dengan isian angka dengan koma `10.5`.

## Aturan Penamaan variabel PHP

- Variabel dimulai dengan tanda `$`,lalu diikuti nama variabel
- Nama variabel harus dimulai dengan `huruf` atau `garis bawah`
- Nama variabel tidak boleh dimulai dengan `angka`
- Nama variabel hanya boleh berisi karakter `alfanumerik` dan `garis bawah` (A-Z, a-z, 0-9, dan \_)
- Nama variabel peka huruf besar-kecil ( `$nama` dan `$NAMA` dua variabel berbeda)

## Output / Keluaran Variabel

Sebuah fungsi yang paling sering di gunakan untuk menampilkan hasil (Output / Keluaran) di PHP adalah `echo` dan `print`

contoh :
`output-variable-php-1.php`

```
<?php

$text = "Saya sedang belajar basic dari PHP";
echo $text;

?>
```

atau kita juga bisa menggabungkan sebuah variabel dengan text yang lain
contoh :
`output-variable-php-2.php`

```
<?php

$text = "Saya sedang belajar basic dari PHP";
echo "Saya sangat senang, Karena " . $text . "!";

?>
```

coba jalankan kedua kode diatas dan lihat yang dihasilkan di browser.

## Lingkup / Cakupan Variabel PHP

Didalam PHP, variabel dapat dideklarasikan di mana saja dalam kode.

Lingkup suatu variabel adalah bagian dari kode tempat variabel dapat digunakan.

PHP memiliki tiga lingkup variabel yang berbeda yaitu :

- lokal
- global
- statis

Lebih lanjut tentang ketiga cakupan / Lingkup variabel akan kita bahas di kesempatan mendatang.
