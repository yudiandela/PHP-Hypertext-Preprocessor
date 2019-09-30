# Tipe Data PHP

Variabel di dalam PHP dapat menyimpan data dari tipe yang berbeda, dan tipe data yang berbeda dapat melakukan hal yang berbeda pula.

PHP mendukung beberapa tipe data antara lain :

-   String
-   Integer
-   Float
-   Boolean
-   Array
-   Object
-   NULL
-   Resource

## String

String adalah urutan karakter, contoh "Hello World!".

Sebuah string dapat berupa teks atau apa pun yang diapit oleh tanda kutip. Kita dapat menggunakan tanda kutip tunggal ( ' ) atau ganda ( " ):

contoh :

string_example.php

```
<?php

$x = "Hello world!";
$y = 'Hello world!';

echo $x;
echo "<br>";
echo $y;

?>
```

## Integer

Tipe data integer adalah bilangan bulat tanpa desimal antara -2,147.483.648 dan 2.147.483.647.

Aturan untuk Integer :

-   Integer harus memiliki setidaknya satu digit angka.
-   Integer tidak boleh memiliki angka desimal.
-   Integer dapat berupa positif atau negatif.

Perhatikan contoh berikut :

integer_example.php

variabel x adalah Integer. Fungsi var_dump() mengembalikan tipe data dan nilai :

```
<?php

$x = 5985;
var_dump($x);

?>
```

## Float

Float adalah angka dengan titik desimal atau angka dalam bentuk eksponensial.

Perhatikan contoh berikut :

float_example.php

variabel x adalah float. Fungsi var_dump() mengembalikan tipe data dan nilai:

```
<?php

$x = 10.365;
var_dump($x);

?>
```

## Boolean

Boolean mewakili dua kemungkinan keadaan: **BENAR(TRUE)** atau **SALAH(FALSE)**.

contoh :

```
$x = true;
$y = false;
```

Boolean sering digunakan dalam pengujian bersyarat. Kita akan belajar lebih banyak tentang pengujian bersyarat di bab selanjutnya.

## Array

Array menyimpan banyak nilai dalam satu variabel tunggal.

Perhatikan contoh berikut :

array_example.php

variabel cars adalah sebuah array. Fungsi PHP var_dump() mengembalikan tipe data dan nilai:

```
<?php

$cars = array("Avanza","Fortuner","Yaris");
var_dump($cars);

?>
```

Kita akan belajar lebih banyak tentang array di bab selanjutnya.

## Object

Object adalah tipe data yang menyimpan data dan informasi tentang cara memproses data itu.

Dalam PHP, suatu object harus dinyatakan secara eksplisit.

Pertama kita harus mendeklarasikan class object. Untuk ini, kita menggunakan kata kunci class. class adalah struktur yang dapat berisi properti dan metode:

Contoh :

object_example.php

```
<?php
class Car {
    function Car() {
        $this->model = "VW";
    }
}

// create an object
$herbie = new Car();

// show object properties
echo $herbie->model;
?>
```

## Null

Null adalah tipe data khusus yang hanya dapat memiliki satu nilai: **NULL**.

Variabel dengan tipe data **NULL** adalah variabel yang tidak memiliki nilai yang ditetapkan padanya.

```
Tip: Jika suatu variabel dibuat tanpa nilai, variabel itu secara otomatis akan diberi nilai NULL.
```

Variabel juga dapat dikosongkan dengan menetapkan nilai ke NULL:

Contoh :

null_example.php

```
<?php

$x = "Hello world!";
$x = null;

var_dump($x);

?>
```

## Resource

Resource bukan tipe data khusus aktual. Ini adalah penyimpanan referensi ke fungsi dan resource eksternal ke PHP.

Contoh umum menggunakan tipe data resource adalah panggilan data dari database.

Kita tidak akan belajar tentang jenis data resource di sini, karena ini adalah topik lanjutan.
