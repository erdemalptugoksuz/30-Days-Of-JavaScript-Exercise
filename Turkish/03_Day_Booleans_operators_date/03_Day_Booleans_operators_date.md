<div align="center">
  <h1> 30 Günde JavaScript: Egzersiz Cevapları | Gün 3</h1>
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
| 🇬🇧   |                                                             [İngilizce](/03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md)                                                             |
| 🇹🇷   |                                                             [Türkçe](./03_Day_Booleans_operators_date.md)                                                             |

## Düzenleyiciyi Destekle
| Link Adı |                                                                       Link                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| Link 1   |                                                             [Reklamlı Link](https://ay.live/k3IVN)

## 💻 Gün 3: Alıştırmalar

### Egzersiz: Seviye 1

1. firstName, lastName, country, city, age, isMarried, year değişkenlerini tanımlayın ve değerlerini atayın. Türlerini kontrol edin.
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
2. 10 sayısı "10"a eşit midir kontrol edin.
```js
console.log(typeof '10') // string
console.log(typeof 10) // number
console.log(typeof '10' == typeof 10) // false
```
3. parseInt('9.8') işlemini yapın ve 10'a eşit midir kontrol edin.
```js
console.log(parseInt('9.8')) // 9
console.log(parseInt('9.8') == 10) // false
```
4. Boolean değeri true ya da false'dir.
   1. 3 adet true değeri döndüren JavaScript ifadesi yazın.
   2. 3 adet false değeri döndüren JavaScript ifadesi yazın.
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

5. Aşağıdaki karşılaştırma ifadesinin sonucunu öncelikle console.log() kullanmadan bulun. Sonuca karar verdikten sonra bunu console.log() kullanarak onaylayın.
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
   12. Python ve jargonun uzunluğunu bulun ve false bir karşılaştırma ifadesi yapın.
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
6. Aşağıdaki karşılaştırma ifadesinin sonucunu öncelikle console.log() kullanmadan bulun. Sonuca karar verdikten sonra bunu console.log() kullanarak onaylayın.
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
   11. Hem dragon ifadesinde hem de python ifadesinde "on" yoktur.
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

7. Aşağıdaki soruları cevaplamak için Date objesini kullanın.
   1. Hangi yıldayız?
   2. Bulunduğumuz ayın sayı karşılığı nedir?
   3. Bugünün tarihi nedir?
   4. Bugün sayı olarak kaçıncı gün?
   5. Şu an saat kaç?
   6. Şu an dakika kaç?
   7. 1 Ocak 1970'ten bugüne kadar geçen saniye sayısını bulun.
```js
console.log(new Date().getFullYear())
console.log(new Date().getMonth())
console.log(new Date().getDate())
console.log(new Date().getDay())
console.log(new Date().getHours())
console.log(new Date().getMinutes())
console.log(new Date().getTime())
```

### Egzersiz: Seviye 2

1. Kullanıcıdan üçgenin tabanını ve yüksekliğini girmesini isteyin. Girilen değerler ile üçgenin alanını hesaplayın. (alan = 0.5 x b x h).
```js
let base = prompt('Enter base of the triangle')
let height = prompt('Enter height of the triangle')
let area = 0.5 * base * height
console.log(`The area of the triangle is ${area}`)
```
2. Kullanıcıdan üçgenin a, b ve c kenarlarını girmesini isteyin. Girilen değerler ile üçgenin çevresini hesaplayın.(çevre = a + b + c)
```js
let a = prompt('Enter side a of the triangle')
let b = prompt('Enter side b of the triangle')
let c = prompt('Enter side c of the triangle')
let perimeter = a + b + c
console.log(`The perimeter of the triangle is ${perimeter}`)
```
3. Kullanıcıdan uzunluk ve genişlik değerlerini alarak bir dikdörtgenin alanını hesaplayın. (alan = uzunluk x genişlik ve dikdörtgenin çevresi (çevre = 2 x (uzunluk + genişlik))
```js
let length = prompt('Enter length of the rectangle')
let width = prompt('Enter width of the rectangle')
let area = length * width
let perimeter = 2 * (length + width)
console.log(`The area of the rectangle is ${area}`)
console.log(`The perimeter of the rectangle is ${perimeter}`)
```
4. Kullanıcıdan yarıçap değerini alarak bir dairenin alanını hesaplayın. (alan = pi x r x r) ve dairenin çevresi (c = 2 x pi x r) burada pi = 3.14.
```js
let radius = prompt('Enter radius of the circle')
let area = Math.PI * radius * radius
let circumference = 2 * Math.PI * radius
console.log(`The area of the circle is ${area}`)
console.log(`The circumference of the circle is ${circumference}`)
```
5. y = 2x -2'nin eğimini, x kesme noktasını ve y kesme noktasını hesaplayın.
```js
let slope = 2
let xIntercept = 0
let yIntercept = -2
console.log(`The slope is ${slope}`)
console.log(`The x-intercept is ${xIntercept}`)
console.log(`The y-intercept is ${yIntercept}`)
```
6. Eğim (m = y2-y1/x2-x1). Nokta (2, 2) ile nokta (6,10) arasındaki eğimi bulun.
```js
let slope = (10 - 2) / (6 - 2)
console.log(`The slope is ${slope}`)
```
7. Yukarıdaki iki sorunun eğimini karşılaştırın.
```js
let slope1 = 2
let slope2 = (10 - 2) / (6 - 2)
console.log(`The slope of question 5 is ${slope1}`)
console.log(`The slope of question 6 is ${slope2}`)
```
8. y'nin değerini hesaplayın (y = x^2 + 6x + 9). Farklı x değerleri kullanmayı deneyin ve hangi x değerinde y'nin 0 olduğunu bulun.
```js
let x = 2
let y = x * x + 6 * x + 9
console.log(`The value of y is ${y}`)
```
9. Kullanıcıdan çalışma saati ve saat başına aldığı ücreti girmesini isteyin. Maaşını hesaplayın.
```js
let hours = prompt('Enter hours')
let rate = prompt('Enter rate per hour')
let pay = hours * rate
console.log(`The pay is ${pay}`)
```
10. Adınızın uzunluğu 7'den büyükse, adınız uzun, aksi takdirde adınızın kısa olduğunu söyleyin.
```js
let name = prompt('Enter your name')
if (name.length > 7) {
  console.log('Your name is long')
} else {
  console.log('Your name is short')
}
```
11. Adınızın uzunluğunu ve soyadınızın uzunluğunu karşılaştırın ve bu çıktıyı almalısınız. "Adınız uzun, soyadınız kısa" veya "Adınız kısa, soyadınız uzun".
```js
let firstName = prompt('Enter your first name')
let lastName = prompt('Enter your last name')
if (firstName.length > lastName.length) {
  console.log(`Your first name, ${firstName}, is longer than your family name, ${lastName}`)
} else {
  console.log(`Your first name, ${firstName}, is shorter than your family name, ${lastName}`)
}
```
12. myAge ve yourAge adında iki değişken tanımlayın ve myAge değerinin yourAge değerinden kaç fazla olduğunu gösteren bir cümle yazdırın.
```js
let myAge = 25
let yourAge = prompt('Enter your age')
console.log(`I am ${myAge - yourAge} years older than you`)
``` 
13. prompt ile kullanıcının yaşını alın ve yaşının 18'den büyük olup olmadığını kontrol edin. Eğer 18'den büyükse, "You are old enough to drive" değilse, "You are left with x years to drive" yazdırın. (x = 18 - yaşınız)
```js
let year = prompt('Enter birth year')
let age = new Date().getFullYear() - year
if (age >= 18) {
  console.log('You are ${age}. You are old enough to drive')
} else {
  console.log(`You are left with ${18 - age} years to drive`)
}
```
14. Kullanıcınn doğum yılını alın ve kaç saniye daha yaşayacağını hesaplayın. Bir insanın 100 yıl yaşayabileceğini varsayın.
```js
let years = prompt('Enter number of years')
let seconds = years * 365 * 24 * 60 * 60
console.log(`A person can live ${seconds} seconds`)
```
15. Tarih saat nesnesini kullanarak okunabilir bir saat biçimi oluşturun
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

### Egzersiz: Seviye 3

1. Tarih saat nesnesini kullanarak insan tarafından okunabilen bir saat biçimi oluşturun. Saat ve dakika her zaman iki haneli olmalıdır (7 saat 07 ve 5 dakika 05 olmalıdır)
   1. YYY-MM-DD HH:mm örn. 20120-01-02 07:05
```js
let date = new Date()
let year = date.getFullYear()
let month = date.getMonth() + 1
let day = date.getDate()
let hour = date.getHours()
let minute = date.getMinutes()
console.log(`${year}-${month}-${day} ${hour.toString().padStart(2, '0')}:${minute.toString().padStart(2, '0')}`)
```

[<< Gün 2](../02_Day_Data_types/02_Day_Data_types.md) | [Gün 4 >>](../04_Day_Conditionals/04_Day_Conditionals.md)