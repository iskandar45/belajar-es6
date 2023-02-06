# Classes

Classes adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk membuat blueprint atau pola untuk membuat objek. Classes memudahkan pemrograman dengan memungkinkan Anda untuk membuat objek dengan atribut dan metode yang sama. Seperti objek lain, Anda dapat membuat beberapa objek dari kelas yang sama, masing-masing dengan nilai atribut yang berbeda.

Berikut adalah contoh penggunaan classes:

```
class Animal {
  constructor(name, sound) {
    this.name = name;
    this.sound = sound;
  }

  speak() {
    console.log(`${this.name} says ${this.sound}`);
  }
}

const dog = new Animal('Dog', 'Woof!');
const cat = new Animal('Cat', 'Meow!');

dog.speak(); // Output: Dog says Woof!
cat.speak(); // Output: Cat says Meow!
```

Dalam contoh di atas, kita membuat kelas Animal yang memiliki atribut name dan sound, serta metode speak yang mengeluarkan pesan suara dari objek. Kemudian, kita membuat dua objek dog dan cat dari kelas Animal dengan nilai atribut yang berbeda. Classes membuat pemrograman lebih efisien dan mudah dengan memungkinkan Anda untuk membuat blueprint atau pola untuk membuat objek.

## Latihan

Berikut adalah 5 soal latihan tentang Classes:

1. Buatlah kelas `Book` dengan atribut `title` dan `author`, serta metode `displayInfo` yang mengeluarkan pesan `"Judul buku: [title], Penulis: [author]"`.
2. Buatlah kelas `Person` dengan atribut `firstName`, `lastName`, dan `age`, serta metode `getFullName` yang mengeluarkan pesan `"Nama lengkap: [firstName] [lastName]"`.
3. Buatlah kelas `Movie` dengan atribut `title`, `director`, dan `releaseYear`, serta metode `displayInfo` yang mengeluarkan pesan `"Judul film: [title], Sutradara: [director], Tahun rilis: [releaseYear]"`.
4. Buatlah kelas `Car` dengan atribut `make`, `model`, dan `year`, serta metode `getInfo` yang mengeluarkan pesan `"Merk: [make], Model: [model], Tahun: [year]"`.
5. Buatlah kelas `Student` dengan atribut `name`, `age`, dan `grade`, serta metode `displayInfo` yang mengeluarkan pesan `"Nama: [name], Umur: [age], Nilai: [grade]"`.

Kerjakan soal-soal di atas untuk mengasah pemahaman Anda tentang Classes dalam JavaScript!
