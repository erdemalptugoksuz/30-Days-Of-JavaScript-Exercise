<div align="center">
  <h1> 30 Günde JavaScript: Egzersiz Cevapları | Gün 4</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Oluşturucu:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> Ocak, 2020</small>
</sub>

<a class="header-badge" target="_blank" href="https://www.linkedin.com/in/erdemalptugoksuz/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/heyahtuput">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/Erdem Alptuğ?style=social">
  </a><br>
<sub>Düzenleyen:
<a href="https://www.linkedin.com/in/erdemalptugoksuz/" target="_blank">Erdem Alptuğ Öksüz</a><br>
<small> Şubat, 2023</small>
</sub>

</div>

## Desteklenen Diller
| Bayrak |                                                                       Dil                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| 🇬🇧   |                                                             [İngilizce](/English/04_Day_Conditionals/04_Day_Conditionals.md)                                                             |
| 🇹🇷   |                                                             [Türkçe](/Turkish/04_Day_Conditionals/04_Day_Conditionals.md)                                                             |

## Düzenleyiciyi Destekle
| Link Adı |                                                                       Link                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| Link 1   |                                                            [Ad Link](https://ay.live/Dn9gUE)

## 💻 Gün 4: Egzersizler

### Egzersizler: Seviye 1

1. Prompt'u kullanarak kullanıcı girişi alın ("Yaşınızı giriniz:"). Eğer kullanıcı 18 yaşından büyükse, "You are old enough to drive" yazdırın. Aksi takdirde, "You are left with x years to drive." yazdırın. (x, kullanıcının 18 yaşına kalan yıl sayısıdır.)
```js
let age = prompt('Enter your age: ')
if (age >= 18) {
  console.log('You are old enough to drive')
} else {
  console.log(`You are left with ${18 - age} years to drive.`)
}
```
2. if else kullanarak myAge ve yourAge değişkenlerini karşılaştırın. Eğer myAge büyükse, "I am x years older than you" yazdırın. Aksi takdirde, "You are x years older than me" yazdırın.
```js
let myAge = 25
let yourAge = prompt('Enter your age: ')
if (myAge > yourAge) {
  console.log(`I am ${myAge - yourAge} years older than you.`)
} else {
  console.log(`You are ${yourAge - myAge} years older than me.`)
}
```
3. a, b'den büyükse, "a is greater than b" yazdırın. Aksi takdirde, "a is less than b" yazdırın.
* if else kullanın.
* ternary operator kullanın.
```js
let a = 4
let b = 3
if (a > b) {
  console.log('a is greater than b')
} else {
  console.log('a is less than b')
}
```
```js
let a = 4
let b = 3
let result = a > b ? 'a is greater than b' : 'a is less than b'
console.log(result)
```
4. Çift sayılar 2 ile bölünür ve kalanı 0'dır. Kullanıcıdan bir sayı alın ve sayının çift olup olmadığını kontrol edin. Eğer sayı çift ise, "x is an even number" yazdırın. Aksi takdirde, "x is an odd number" yazdırın.
```js
let number = 8
if (number % 2 == 0) {
  console.log(`${number} is an even number`)
} else {
  console.log(`${number} is an odd number`)
}
```

### Egzersizler: Seviye 2

1. Öğrencinin notunu hesaplayın ve öğrencinin aldığı harfi yazdırın.
* 80-100, A
* 70-89, B
* 60-69, C
* 50-59, D
* 0-49, F
```js
let score = 45
if (score >= 80 && score <= 100) {
  console.log('A')
} else if (score >= 70 && score <= 89) {
  console.log('B')
} else if (score >= 60 && score <= 69) {
  console.log('C')
} else if (score >= 50 && score <= 59) {
  console.log('D')
} else if (score >= 0 && score <= 49) {
  console.log('F')
} else {
  console.log('Invalid score')
}
```
2. Mevsimin Sonbahar, Kış, İlkbahar veya Yaz olup olmadığını kontrol edin. Kullanıcıdan bir ay alın ve mevsimi yazdırın.
* September, October or November, the season is Autumn.
* December, January or February, the season is Winter.
* March, April or May, the season is Spring
* June, July or August, the season is Summer
```js
let month = 'September'
if (month == 'September' || month == 'October' || month == 'November') {
  console.log('Autumn')
} else if (month == 'December' || month == 'January' || month == 'February') {
  console.log('Winter')
} else if (month == 'March' || month == 'April' || month == 'May') {
  console.log('Spring')
} else if (month == 'June' || month == 'July' || month == 'August') {
  console.log('Summer')
} else {
  console.log('Invalid month')
}
```
3. Bir günün hafta sonu veya hafta içi olup olmadığını kontrol edin. Kullanıcıdan bir gün alın ve hafta sonu veya hafta içi olduğunu yazdırın.
```js
let day = prompt('What is the day  today? ')
if (day == 'Saturday' || day == 'Sunday') {
  console.log(`${day} is a weekend`)
} else if (
  day == 'Monday' ||
  day == 'Tuesday' ||
  day == 'Wednesday' ||
  day == 'Thursday' ||
  day == 'Friday'
) {
  console.log(`${day} is a working day`)
} else {
  console.log('Invalid day')
}
```

### Egzersizler: Seviye 3

1. Bir aydaki gün sayısını hesaplayın. Kullanıcıdan bir ay alın ve bu aydaki gün sayısını yazdırın.
```js
let month = prompt('Enter a month: ')
let days = 0
switch (month) {
  case 'January':
    days = 31
    break
  case 'February':
    days = 28
    break
  case 'March':
    days = 31
    break
  case 'April':
    days = 30
    break
  case 'May':
    days = 31
    break
  case 'June':
    days = 30
    break
  case 'July':
    days = 31
    break
  case 'August':
    days = 31
    break
  case 'September':
    days = 30
    break
  case 'October':
    days = 31
    break
  case 'November':
    days = 30
    break
  case 'December':
    days = 31
    break
  default:
    console.log('Invalid month')
}
console.log(`${month} has ${days} days`)
```

[<< Gün 3](/Turkish/03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md) | [Gün 5 >>](/Turkish/05_Day_Arrays/05_Day_Arrays.md)