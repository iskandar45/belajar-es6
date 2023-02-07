# Async/await

Async/await adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk menulis kode asynchronous dalam bentuk kode sincron yang lebih mudah dibaca dan dipahami. Async/await menggunakan sintaks yang lebih mirip dengan kode sincron sehingga membuat kode asynchronous lebih mudah dikelola. Kode asynchronous yang ditulis dengan menggunakan async/await diperlakukan seolah-olah itu adalah kode sincron meskipun sebenarnya masih berjalan secara asynchronous. Async/await membuat kode asynchronous menjadi lebih bersih dan terstruktur.

Sintaks dasar dari async/await adalah sebagai berikut:

```
async function myFunc() {
  // kode asynchronous
  const data = await someAsyncOperation();
  // kode sincron
}
```

Di sini, async adalah kata kunci yang menandakan bahwa fungsi myFunc adalah fungsi asynchronous. Dan await digunakan untuk menunggu hingga proses asynchronous selesai sebelum melanjutkan ke kode sincron berikutnya.

## Latihan

Beberapa soal latihan tentang async/await:

1. Bagaimana membuat sebuah fungsi asynchronous menggunakan async/await?
2. Bagaimana menunggu sebuah fungsi asynchronous menggunakan async/await?
3. Bagaimana menangani error dalam fungsi asynchronous menggunakan async/await?
4. Apa perbedaan antara async/await dan promise dalam menangani kode asynchronous?
5. Bagaimana mengkombinasikan beberapa fungsi asynchronous menjadi satu dengan async/await?
