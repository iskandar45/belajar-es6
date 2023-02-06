# Default parameters

Default parameters adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk memberikan nilai default untuk parameter suatu fungsi. Nilai default ini akan digunakan jika tidak ada nilai yang diteruskan ketika fungsi tersebut dipanggil. Ini membuat pemrograman lebih efisien dan mudah karena Anda tidak perlu lagi mengecek apakah nilai telah diteruskan atau tidak sebelum memprosesnya.

Berikut adalah contoh penggunaan default parameters:

```
function greet(name = 'John Doe') {
  console.log(`Hello, ${name}!`);
}

greet(); // Output: Hello, John Doe!
greet('Jane Doe'); // Output: Hello, Jane Doe!
```

Dalam contoh di atas, jika tidak ada nilai yang diteruskan ke fungsi greet, maka nilai default John Doe akan digunakan. Namun, jika nilai Jane Doe diteruskan, maka nilai tersebut akan digunakan. Default parameters membuat pemrograman lebih efisien dan mudah karena Anda tidak perlu lagi mengecek apakah nilai telah diteruskan atau tidak sebelum memprosesnya.

## Latihan

Berikut adalah beberapa soal latihan tentang default parameters:

1. Buatlah sebuah fungsi bernama `multiply` yang menerima 2 parameter, `a` dan `b`, dan menghitung perkalian `a` dan `b`. Jika `b` tidak diteruskan, gunakan nilai `default` 2.
2. Buatlah sebuah fungsi bernama `greet` yang menerima 1 parameter, `name`, dan mengeluarkan pesan `"Hello, [nama]!"`. Jika name tidak diteruskan, gunakan nilai `default` "John Doe".
3. Buatlah sebuah fungsi bernama `areaOfCircle` yang menerima 1 parameter, `radius`, dan mengeluarkan luas lingkaran. Jika `radius` tidak diteruskan, gunakan nilai `default` 10.
4. Buatlah sebuah fungsi bernama `power` yang menerima 2 parameter, `base` dan `exponent`. Fungsi ini harus menghitung dan mengembalikan hasil base pangkat `exponent`. Jika `exponent` tidak diteruskan, gunakan nilai `default` 2.
5. Buatlah sebuah fungsi bernama `joinWords` yang menerima 2 parameter, `word1` dan `word2`. Fungsi ini harus menggabungkan kedua kata dan mengeluarkan hasilnya. Jika word2 tidak diteruskan, gunakan nilai `default` "world".
