# Spread Operator

Spread Operator adalah fitur baru dalam JavaScript yang memperkenalkan cara baru untuk mengopikan elemen dari array atau membentuk objek baru. Spread Operator memperkenalkan tiga titik `(...)` sebagai operator untuk mengopikan elemen. Spread Operator juga bisa digunakan untuk mengopikan objek dan membentuk objek baru dengan mengkombinasikan properti dari beberapa objek.

## Contoh

Berikut adalah contoh sintaks dasar spread operator:

1. Menyebarkan elemen dari array:

```
const colors = ['red', 'green', 'blue'];
const newColors = [...colors, 'yellow', 'purple'];

console.log(newColors); // Output: [ 'red', 'green', 'blue', 'yellow', 'purple' ]
```

2. Menyebarkan objek dan membentuk objek baru:

```
const person = {
  name: 'John Doe',
  age: 30
};
const location = {
  city: 'New York',
  country: 'USA'
};
const newPerson = { ...person, ...location };

console.log(newPerson);
// Output: { name: 'John Doe', age: 30, city: 'New York', country: 'USA' }
```

Spread Operator membuat pemrograman lebih efisien dan mudah, terutama saat membutuhkan operasi pengopian atau penggabungan data.
