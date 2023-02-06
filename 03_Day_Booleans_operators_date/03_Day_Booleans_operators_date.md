<div align="center">
  <h1> 30 Days Of JavaScript: Exercises Answers | Day 3</h1>
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
| 🇬🇧   |                                                             [English](./03_Day_Booleans_operators_date.md)                                                             |
| 🇹🇷   |                                                             [Turkish](./Turkish/../../Turkish/03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md)                                                             |

## Support to Organizer
| Link Name |                                                                       Link                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| Link 1   |                                                             [Ad Link](https://ay.live/gOmq4a)

## 💻 Day 3: Exercises

### Exercise: Level 1

1. Declare firstName, lastName, country, city, age, isMarried, year variable and assign value to it and use the typeof operator to check different data types.
```js
let firstName = 'Asabeneh'
let lastName = 'Yetayeh'
let country = 'Finland'
let city = 'Helsinki'
let age = 250
let isMarried = true
let year = 2020
console.log(typeof firstName) // string
console.log(typeof lastName) // string
console.log(typeof country) // string
console.log(typeof city) // string
console.log(typeof age) // number
console.log(typeof isMarried) // boolean
console.log(typeof year) // number
````
2. Check if type of '10' is equal to 10
```js
console.log(typeof '10') // string
console.log(typeof 10) // number
console.log(typeof '10' == typeof 10) // false
```
3. Check if parseInt('9.8') is equal to 10
```js
console.log(parseInt('9.8')) // 9
console.log(parseInt('9.8') == 10) // false
```
4. Boolean value is either true or false.
   1. Write three JavaScript statement which provide truthy value.
   2. Write three JavaScript statement which provide falsy value.
```js
// truthy
console.log(3 == 3) // true
console.log(3 === 3) // true
console.log(4 > 3) // true

// falsy
console.log(3 == '3') // false
console.log(3 === '3') // false
console.log(4 < 3) // false
```

5. Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()
   1. 4 > 3
   2. 4 >= 3
   3. 4 < 3
   4. 4 <= 3
   5. 4 == 4
   6. 4 === 4
   7. 4 != 4
   8. 4 !== 4
   9. 4 != "4"
   10. 4 == "4"
   11. 4 === "4"
   12. Find the length of python and jargon and make a falsy comparison statement.
```js
console.log(4 > 3) // true
console.log(4 >= 3) // true
console.log(4 < 3) // false
console.log(4 <= 3) // false
console.log(4 == 4) // true
console.log(4 === 4) // true
console.log(4 != 4) // false
console.log(4 !== 4) // false
console.log(4 != "4") // false
console.log(4 == "4") // true
console.log(4 === "4") // false
console.log('python'.length = 'jargon'.length) // false
```
6. Figure out the result of the following expressions first without using console.log(). After you decide the result confirm it by using console.log
   1. 4 > 3 && 10 < 12
   2. 4 > 3 && 10 > 12
   3. 4 > 3 || 10 < 12
   4. 4 > 3 || 10 > 12
   5. !(4 > 3)
   6. !(4 < 3)
   7. !(false)
   8. !(4 > 3 && 10 < 12)
   9. !(4 > 3 && 10 > 12)
   10. !(4 === '4')
   11. There is no 'on' in both dragon and python
```js
console.log(4 > 3 && 10 < 12) // true
console.log(4 > 3 && 10 > 12) // false
console.log(4 > 3 || 10 < 12) // true
console.log(4 > 3 || 10 > 12) // true
console.log(!(4 > 3)) // false 
console.log(!(4 < 3)) // true
console.log(!(false)) // true
console.log(!(4 > 3 && 10 < 12)) // false
console.log(!(4 > 3 && 10 > 12)) // true
console.log(!(4 === '4')) // true
```

7. Use the Date object to do the following activities
   1. What is the year today?
   2. What is the month today as a number?
   3. What is the date today?
   4. What is the day today as a number?
   5. What is the hours now?
   6. What is the minutes now?
   7. Find out the numbers of seconds elapsed from January 1, 1970 to now.
```js
console.log(new Date().getFullYear())
console.log(new Date().getMonth())
console.log(new Date().getDate())
console.log(new Date().getDay())
console.log(new Date().getHours())
console.log(new Date().getMinutes())
console.log(new Date().getTime())
```

### Exercise: Level 2

1. Write a script that prompt the user to enter base and height of the triangle and calculate an area of a triangle (area = 0.5 x b x h).
```js
let base = prompt('Enter base of the triangle')
let height = prompt('Enter height of the triangle')
let area = 0.5 * base * height
console.log(`The area of the triangle is ${area}`)
```
2. Write a script that prompt the user to enter side a, side b, and side c of the triangle and and calculate the perimeter of triangle (perimeter = a + b + c)
```js
let a = prompt('Enter side a of the triangle')
let b = prompt('Enter side b of the triangle')
let c = prompt('Enter side c of the triangle')
let perimeter = a + b + c
console.log(`The perimeter of the triangle is ${perimeter}`)
```
3. Get length and width using prompt and calculate an area of rectangle (area = length x width and the perimeter of rectangle (perimeter = 2 x (length + width))
```js
let length = prompt('Enter length of the rectangle')
let width = prompt('Enter width of the rectangle')
let area = length * width
let perimeter = 2 * (length + width)
console.log(`The area of the rectangle is ${area}`)
console.log(`The perimeter of the rectangle is ${perimeter}`)
```
4. Get radius using prompt and calculate the area of a circle (area = pi x r x r) and circumference of a circle(c = 2 x pi x r) where pi = 3.14.
```js
let radius = prompt('Enter radius of the circle')
let area = Math.PI * radius * radius
let circumference = 2 * Math.PI * radius
console.log(`The area of the circle is ${area}`)
console.log(`The circumference of the circle is ${circumference}`)
```
5. Calculate the slope, x-intercept and y-intercept of y = 2x -2
```js
let slope = 2
let xIntercept = 0
let yIntercept = -2
console.log(`The slope is ${slope}`)
console.log(`The x-intercept is ${xIntercept}`)
console.log(`The y-intercept is ${yIntercept}`)
```
6. Slope is (m = y2-y1/x2-x1). Find the slope between point (2, 2) and point(6,10)
```js
let slope = (10 - 2) / (6 - 2)
console.log(`The slope is ${slope}`)
```
7. Compare the slope of above two questions.
```js
let slope1 = 2
let slope2 = (10 - 2) / (6 - 2)
console.log(`The slope of question 5 is ${slope1}`)
console.log(`The slope of question 6 is ${slope2}`)
```
8. Calculate the value of y (y = x^2 + 6x + 9). Try to use different x values and figure out at what x value y is 0.
```js
let x = 2
let y = x * x + 6 * x + 9
console.log(`The value of y is ${y}`)
```
9. Writ a script that prompt a user to enter hours and rate per hour. Calculate pay of the person?
```js
let hours = prompt('Enter hours')
let rate = prompt('Enter rate per hour')
let pay = hours * rate
console.log(`The pay is ${pay}`)
```
10. If the length of your name is greater than 7 say, your name is long else say your name is short.
```js
let name = prompt('Enter your name')
if (name.length > 7) {
  console.log('Your name is long')
} else {
  console.log('Your name is short')
}
```
11. Compare your first name length and your family name length and you should get this output.
```js
let firstName = prompt('Enter your first name')
let lastName = prompt('Enter your last name')
if (firstName.length > lastName.length) {
  console.log(`Your first name, ${firstName}, is longer than your family name, ${lastName}`)
} else {
  console.log(`Your first name, ${firstName}, is shorter than your family name, ${lastName}`)
}
```
12. Declare two variables myAge and yourAge and assign them initial values and myAge and yourAge.
```js
let myAge = 25
let yourAge = prompt('Enter your age')
console.log(`I am ${myAge - yourAge} years older than you`)
``` 
13. Using prompt get the year the user was born and if the user is 18 or above allow the user to drive if not tell the user to wait a certain amount of years.
```js
let year = prompt('Enter birth year')
let age = new Date().getFullYear() - year
if (age >= 18) {
  console.log('You are ${age}. You are old enough to drive')
} else {
  console.log(`You are left with ${18 - age} years to drive`)
}
```
14. Write a script that prompt the user to enter number of years. Calculate the number of seconds a person can live. Assume some one lives just hundred years
```js
let years = prompt('Enter number of years')
let seconds = years * 365 * 24 * 60 * 60
console.log(`A person can live ${seconds} seconds`)
```
15. Create a human readable time format using the Date time object
    1. YYYY-MM-DD HH:mm
    2. DD-MM-YYYY HH:mm
    3. DD/MM/YYYY HH:mm
```js
let date = new Date()
let year = date.getFullYear()
let month = date.getMonth() + 1
let day = date.getDate()
let hour = date.getHours()
let minute = date.getMinutes()
console.log(`${year}-${month}-${day} ${hour}:${minute}`)
console.log(`${day}-${month}-${year} ${hour}:${minute}`)
console.log(`${day}/${month}/${year} ${hour}:${minute}`)
```

### Exercise: Level 3

1. Create a human readable time format using the Date time object. The hour and the minute should be all the time two digits(7 hours should be 07 and 5 minutes should be 05 )
   1. YYY-MM-DD HH:mm eg. 20120-01-02 07:05
```js
let date = new Date()
let year = date.getFullYear()
let month = date.getMonth() + 1
let day = date.getDate()
let hour = date.getHours()
let minute = date.getMinutes()
console.log(`${year}-${month}-${day} ${hour.toString().padStart(2, '0')}:${minute.toString().padStart(2, '0')}`)
```

[<< Day 2](../02_Day_Data_types/02_Day_Data_types.md) | [Day 4 >>](../04_Day_Conditionals/04_Day_Conditionals.md)