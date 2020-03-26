## Operator Arimatika

Operator Arimatika di Javascript berfungsi sebagai pengurangan penjumlahan dsb. Sama seperti Matematika
Contoh bentuk operator Arimatika yaitu:

| Nama                  | Simbol |
| -----------           | ------ |
| Penjumlahan           | +      |
| Pengurangan           | -      |
| Perkalian             | *      |
| Pembagian             | /      |
| Sisa Bagi(Modulus)    | %      |

Contoh penggunaan operator arimatika di Javascript:

```javascript
 var i;
//  Penjumlahan
    i = 10 + 10;
    console.log(i); // output = 10

//  Pengurangan
    i = 10 - 10;
    console.log(i); // output = 0

//  Perkalian
    i = 10 * 10;
    console.log(i); // output = 100

//  Penjumlahan
    i = 10 / 10;
    console.log(i); // output = 1

//  Penjumlahan
    i = 10 % 7;
    console.log(i); // output = 3
    // Alasan 3 hasilnya adalah 10 / 7 cuma bisa sekali menghasilkan bilangan tanpa koma 
    // dibelakagnya
```
Kita Juga bisa menggabungkan string dengan operator **+**
Berikut contohnya:

```javascript
  var love;
  love = "Aku" + " " + "Dan" + " " + "Kamu";
  console.log(love);
```