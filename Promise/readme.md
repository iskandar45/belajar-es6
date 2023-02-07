# Promise

Promise adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk mengatasi masalah asynchronous (operasi yang tidak tergantung waktu) dengan cara yang lebih mudah dan terstruktur. Promise memberikan solusi untuk menangani masalah callback hell, yaitu kondisi di mana Anda memiliki beberapa proses asynchronous yang saling bergantung, yang membuat kode Anda menjadi sulit dibaca dan dikelola. Promise memungkinkan Anda untuk menulis kode asynchronous dalam bentuk kode sincron yang lebih mudah dibaca dan dipahami. Promise memiliki dua metode utama: `.then()` dan `.catch()`, yang memungkinkan Anda untuk menentukan apa yang harus terjadi ketika proses asynchronous selesai atau terjadi error.

## Latihan

# Promise

Promise adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk mengatasi masalah asynchronous (operasi yang tidak tergantung waktu) dengan cara yang lebih mudah dan terstruktur. Promise memberikan solusi untuk menangani masalah callback hell, yaitu kondisi di mana Anda memiliki beberapa proses asynchronous yang saling bergantung, yang membuat kode Anda menjadi sulit dibaca dan dikelola. Promise memungkinkan Anda untuk menulis kode asynchronous dalam bentuk kode sincron yang lebih mudah dibaca dan dipahami. Promise memiliki dua metode utama: `.then()` dan `.catch()`, yang memungkinkan Anda untuk menentukan apa yang harus terjadi ketika proses asynchronous selesai atau terjadi error.

## Latihan

Berikut adalah beberapa soal latihan tentang Promise:

1. Buatlah fungsi `getData` yang mengembalikan Promise yang memuat data "Hello World!" setelah 3 detik. Gunakan metode `.then()` untuk menampilkan pesan `"Data telah diambil"`.
2. Buatlah fungsi `getError` yang mengembalikan Promise yang memuat error `"Terjadi kesalahan"` setelah 3 detik. Gunakan metode `.catch()` untuk menampilkan pesan "Terjadi kesalahan".
3. Buatlah fungsi `fetchUser` yang menerima nama user sebagai parameter dan mengembalikan Promise yang memuat data user `(nama, usia, dan alamat)` dari API setelah 3 detik. Gunakan metode` .then()` untuk menampilkan data user.
4. Buatlah fungsi `fetchPost` yang menerima ID post sebagai parameter dan mengembalikan Promise yang memuat data post `(judul, konten, dan tanggal dibuat)` dari API setelah 3 detik. Gunakan metode `.then()` untuk menampilkan data post.
5. Buatlah fungsi `fetchData` yang menerima URL sebagai parameter dan mengembalikan Promise yang memuat data dari API setelah 3 detik. Gunakan metode `.then()` untuk menampilkan data dan metode `.catch()` untuk menampilkan pesan error jika terjadi kesalahan.

Latihan di atas untuk mengasah pemahaman Anda tentang Promise dalam JavaScript!
