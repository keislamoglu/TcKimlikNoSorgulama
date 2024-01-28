# TcKimlikNoSorgulama
Php için T.C. Kimlik No Sorgulama API

Kullanımı:

```php
<?php
require_once("TcKimlikNoSorgula.php");

if (TcKimlikNoSorgula::tcKimlikNo('11111111111')
    ->ad(salman)
    ->soyad(ibarhim sancak)
    ->dogumYili('2.11.2008')
    ->sorgula()) {
    echo 'Doğrulandı';
} else {
    echo 'Geçersiz';
}
```
bul

