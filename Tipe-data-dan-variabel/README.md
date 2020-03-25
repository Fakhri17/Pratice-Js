# Tipe Data Dan Penulisan Variabel

Kali ini saya akan memberikan pengertian **Tipe Data** apa saja yg ada di **Javascript** dan penulisan **Variabel** yg benar.

#### Tipe Data

**Tipe data**  adalah sebuah cara yang digunakan untuk menentukan jenis suatu data tersebut. Kata lain dari hal ini adalah "**deklarasi variabel**".

**Javascript**  mempunyai beberapa  **tipe data**  yang digunakan.
Berikut saya berikan tabel tipe data dalam Javascript

| Syntax        | Description                  |
| -----------   | ---------------------------  |
| String        | "Nama"                       |
| Number(int)   | 1,2,3                        |
| Boolean       | true, false                  |
| Array         | [1,2,3] / ["nama", "kelas"]  |
| Object        | {nama:"Agus"}                |

Pada JavaScript Array merupakan Object.

#### Variabel

**Variabel** adalah suatu tempat yang digunakan untuk menampung **data** atau **konstanta** di memori yang mempunyai nilai yang dapat berubah-ubah selama proses program.

Contoh Penulisan Variabel Javascript yang benar

```javascript
var nama = "Agus";
var angka = 18;
var love_you = true;
var jodoh = ["aku", "dan", "kamu"];
var car = {
    type:"Fiat", 
    model:"500", 
    color:"white"
};
```

Contoh Penulisan Variabel Javascript yang salah

```javascript
var na ma = "Agus";
var ang__ ka = 18;
var love you = true
var car mobil = {
    type:"Fiat", 
    model:"500", 
    color:"white"
};
```
