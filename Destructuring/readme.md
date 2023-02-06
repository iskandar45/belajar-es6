# Destructuring

Destructuring adalah fitur baru dalam JavaScript yang memungkinkan Anda untuk memecahkan objek atau array menjadi variabel-variabel yang lebih mudah diterima. Ini membuat penulisan kode menjadi lebih ringkas dan mudah dibaca, dan mempermudah akses ke nilai-nilai tertentu dalam objek atau array. Destructuring bisa dilakukan pada `objek`, `array`, dan `parameter function`.

Pada script ini terdapat destructuring:

```
const person = {
  name: 'John Doe',
  age: 30,
  email: 'johndoe@example.com'
};

const { name, age, email } = person;

console.log(name); // Output: John Doe
console.log(age); // Output: 30
console.log(email); // Output: johndoe@example.com
```

destructuring terletak pada baris :

```
const { name, age, email } = person;
```

silahkan kembangkan sesuka kalian.

## Latihan

Berikut adalah beberapa soal latihan mengenai destructuring:

1. Destructuring sebuah objek dan mengambil nilai-nilai tertentu:

```
const car = {
  brand: 'Toyota',
  model: 'Camry',
  year: 2020
};

// Ubah objek car menjadi tiga variabel brand, model, dan year
// Code disini, jangan ubah script lainnya

console.log(brand); // Output: Toyota
console.log(model); // Output: Camry
console.log(year); // Output: 2020
```

2. Destructuring sebuah array dan mengambil nilai-nilai tertentu:

```
const colors = ['red', 'green', 'blue'];

// Ubah array colors menjadi tiga variabel red, green, dan blue
// ...

console.log(red); // Output: red
console.log(green); // Output: green
console.log(blue); // Output: blue
```

3. Menggabungkan destructuring dengan parameter function:

```
const user = {
  name: 'John Doe',
  age: 30,
  email: 'johndoe@example.com'
};

function displayUser({ name, age, email }) {
  console.log(`Name: ${name}, Age: ${age}, Email: ${email}`);
}

// Panggil function displayUser dan berikan objek user sebagai argumen
// ...

// Output: Name: John Doe, Age: 30, Email: johndoe@example.com
```

4. Destructuring nested object:

```
const person = {
  name: 'John Doe',
  age: 30,
  address: {
    street: '123 Main St',
    city: 'New York',
    state: 'NY'
  }
};

// Ubah objek person menjadi variabel name, age, street, city, dan state
// ...

console.log(name); // Output: John Doe
console.log(age); // Output: 30
console.log(street); // Output: 123 Main St
console.log(city); // Output: New York
console.log(state); // Output: NY
```

5. Menggunakan destructuring dalam for-of loop:

```
const words = ['apple', 'banana', 'cherry'];

for (const [index, word] of words.entries()) {
  console.log(`${index}: ${word}`);
}

// Output:
// 0: apple
// 1: banana
// 2: cherry
```

Semoga latihan ini membantu memperkuat pemahaman Anda mengenai destructuring dalam JavaScript. Terus berlatih dan mencoba fitur-fitur baru untuk memperluas pemahaman Anda.
