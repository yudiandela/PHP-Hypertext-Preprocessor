# Sintaks Dasar PHP

Pada dasar nya sintaks PHP dapat kita tuliskan di mana saja di dalam file / dokumen baik file dengan ext `.html` maupun file dengan `.php`, dengan mengawali tanda PEMBUKA tag `<?php` dan PENUTUP tag `?>`

contoh :

`file-only-php.php`

```
<?php
// Kode PHP Disini
```

atau

`file-include-html.php`

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    <?php
    // Kode PHP disini
    ?>
</body>
</html>
```

## Kekhususan file ext .php

Apabila kita membuat sebuah file dengan ext `.php` dan didalam nya hanya terdapat script PHP saja, maka jika kita tidak menggunakan tag penutup `?>` di bagian akhir file maka hal tersebut di nyatakan valid.

## Contoh

Lihat file yang saya sertakan.
