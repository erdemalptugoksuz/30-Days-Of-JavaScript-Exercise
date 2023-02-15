<div align="center">
  <h1> 30 Days Of JavaScript: Exercises Answers | Day 4</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Author:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> January, 2020</small>
</sub>

<a class="header-badge" target="_blank" href="https://www.linkedin.com/in/erdemalptugoksuz/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/heyahtuput">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/Erdem Alptuğ?style=social">
  </a><br>
<sub>Organizer:
<a href="https://www.linkedin.com/in/erdemalptugoksuz/" target="_blank">Erdem Alptuğ Öksüz</a><br>
<small> February, 2023</small>
</sub>

</div>

## Supported Languages
| Flag |                                                                       Language                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| 🇬🇧   |                                                             [English](/English/04_Day_Conditionals/04_Day_Conditionals.md)                                                             |
| 🇹🇷   |                                                             [Turkish](/Turkish/04_Day_Conditionals/04_Day_Conditionals.md)                                                             |

## Support to Organizer
| Link Name |                                                                       Link                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| Link 1   |                                                             [Ad Link](https://ay.live/MnW8)

## 💻 Day 4: Exercises

### Exercises: Level 1

1. Get user input using `prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.
```js
let age = prompt('Enter your age: ')
if (age >= 18) {
  console.log('You are old enough to drive')
} else {
  console.log(`You are left with ${18 - age} years to drive.`)
}
```
2. Compare the values of myAge and yourAge using if … else. Based on the comparison log to console who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.
```js
let myAge = 25
let yourAge = prompt('Enter your age: ')
if (myAge > yourAge) {
  console.log(`I am ${myAge - yourAge} years older than you.`)
} else {
  console.log(`You are ${yourAge - myAge} years older than me.`)
}
```
3. If a is greater than b return 'a is greater than b' else 'a is less than b'. Try to implement it in to ways
* using if else
* ternary operator
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
4. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?
```js
let number = 8
if (number % 2 == 0) {
  console.log(`${number} is an even number`)
} else {
  console.log(`${number} is an odd number`)
}
```

### Exercises: Level 2

1. Write a code which can give grades to students according to theirs scores:
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
2. Check if the season is Autumn, Winter, Spring or Summer. If the user input is:
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
3. Check if a day is weekend day or a working day. Your script will take day as an input.
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

### Exercises: Level 3

1. Write a program which tells the number of days in a month.
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

[<< Day 3](/English/03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md) | [Day 5 >>](/English/05_Day_Arrays/05_Day_Arrays.md)