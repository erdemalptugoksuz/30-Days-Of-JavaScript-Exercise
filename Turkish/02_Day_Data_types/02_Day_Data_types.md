<div align="center">
  <h1> 30 Günde JavaScript: Egzersiz Cevapları | Gün 2</h1>
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
| 🇬🇧   |                                                             [İngilizce](/02_Day_Data_types/02_Day_Data_types.md)                                                             |
| 🇹🇷   |                                                             [Türkçe](./02_Day_Data_types.md)                                                             |

## Düzenleyiciyi Destekle
| Link Adı |                                                                       Link                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| Link 1   |                                                             [Reklamlı Link](https://ay.live/4ZnC)


## 💻 Gün 2: Alıştırmalar

### Alıştırmalar: Seviye 1
1. challenge adında bir değişken tanımlayın ve başlangıç değerini **'30 Days Of JavaScript'** olarak atayın.
```js
let challenge = '30 Days Of JavaScript'
```
2. **console.log()** kullanarak tarayıcı konsolunda değişkeni yazdırın.
```js
console.log(challenge) // 30 Days Of JavaScript
```
3. **console.log()** kullanarak tarayıcı konsolunda değişkenin uzunluğunu yazdırın.
```js
console.log(challenge.length) // 21
```
4. **toUpperCase()** metodu kullanarak tüm karakterleri büyük harfe çevirin.
```js
console.log(challenge.toUpperCase()) // 30 DAYS OF JAVASCRIPT
```
5. **toLowerCase()** metodu kullanarak tüm karakterleri küçük harfe çevirin.
```js
console.log(challenge.toLowerCase()) // 30 days of javascript
```
6. **substr()** veya **substring()** metodu kullanarak değişkenin ilk kelimesini kesin (kırpın).
```js
console.log(challenge.substr(0, 2)) // 30
```
7. **'30 Days Of JavaScript'** ifadesinden **Days Of JavaScript** ifadesini kesin (kırpın).
```js
console.log(challenge.substr(3)) // Days Of JavaScript
```
8. **includes()** metodu kullanarak değişkenin içinde **Script** kelimesinin olup olmadığını kontrol edin.
```js
console.log(challenge.includes('Script')) // true
```
9. **split()** metodu kullanarak değişkeni bir diziye ayırın.
```js
console.log(challenge.split()) // ["30 Days Of JavaScript"]
```
10. **split()** metodu kullanarak değişkeni boşluk karakterine göre bir diziye ayırın.
```js
console.log(challenge.split(' ')) // ["30", "Days", "Of", "JavaScript"]
```
11. **'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'** ifadesini virgül karakterine göre bir diziye ayırın.
```js
console.log('Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'.split(',')) // ["Facebook", " Google", " Microsoft", " Apple", " IBM", " Oracle", " Amazon"]
```
12. **replace()** metodu kullanarak **30 Days Of JavaScript** ifadesini **30 Days Of Python** ifadesi ile değiştirin.
```js
console.log(challenge.replace('JavaScript', 'Python')) // 30 Days Of Python
```
13. **charAt()** metodu kullanarak **'30 Days Of JavaScript'** ifadesindeki 15. indeksteki karakteri bulun.
```js
console.log(challenge.charAt(15)) // a
```
14. **charCodeAt()** metodu kullanarak **'J'** karakterinin karakter kodunu bulun.
```js
console.log(challenge.charCodeAt('J')) // 74
```
15. **indexOf()** metodu kullanarak **'30 Days Of JavaScript'** ifadesindeki ilk **a** karakterinin indeksini bulun.
```js
console.log(challenge.indexOf('a')) // 1
```
16. **lastIndexOf()** metodu kullanarak **'30 Days Of JavaScript'** ifadesindeki son **a** karakterinin indeksini bulun.
```js
console.log(challenge.lastIndexOf('a')) // 14
```
17. **indexOf()** metodu kullanarak **'You cannot end a sentence with because because because is a conjunction'** ifadesindeki ilk **because** kelimesinin indeksini bulun.
```js
console.log('You cannot end a sentence with because because because is a conjunction'.indexOf('because')) // 31
```
18. **lastIndexOf()** metodu kullanarak **'You cannot end a sentence with because because because is a conjunction'** ifadesindeki son **because** kelimesinin indeksini bulun.
```js
console.log('You cannot end a sentence with because because because is a conjunction'.lastIndexOf('because')) // 47
```
19. **search()** metodu kullanarak **'You cannot end a sentence with because because because is a conjunction'** ifadesindeki ilk **because** kelimesinin indeksini bulun.
```js
console.log('You cannot end a sentence with because because because is a conjunction'.search('because')) // 31
```
20. **trim()** metodu kullanarak **' 30 Days Of JavaScript '** ifadesindeki boşluk karakterlerini silin.
```js
console.log(' 30 Days Of JavaScript '.trim()) // 30 Days Of JavaScript
```
21. **startsWith()** metodu kullanarak **'30 Days Of JavaScript'** ifadesi **30 Days** ile başlayıp başlamadığını kontrol edin.
```js
console.log(challenge.startsWith('30')) // true
```
22. **endsWith()** metodu kullanarak **'30 Days Of JavaScript'** ifadesi **JavaScript** ile bitip bitmediğini kontrol edin.
```js
console.log(challenge.endsWith('JavaScript')) // true
```
23. **match()** metodu kullanarak **'30 Days Of JavaScript'** ifadesindeki bütün  **a** ifadelerini arayın.
```js
console.log(challenge.match(/a/gi)) // ["a", "a", "a", "a"]
```
24.  **concat()** metodu kullanarak **'30 Days Of'** ve **'JavaScript'** ifadelerini birleştirin.
```js
let first = '30 Days of'
let second = 'JavaScript'
console.log(first.concat(' ', second)) // 30 Days of JavaScript
```
25.  **repeat()** metodu kullanarak **'30 Days Of JavaScript'** ifadesini 2 kez tekrarlayın.
```js
console.log(challenge.repeat(2)) // 30 Days Of JavaScript30 Days Of JavaScript
```

### Alıştırmalar: Seviye 2

1. **console.log()** ile aşağıdaki ifadeyi yazdırın:
```sh
The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another
```
```js
console.log('The quote \'There is no exercise better for the heart than reaching down and lifting people up.\' by John Holmes teaches us to help one another') // The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another
```
2. **console.log()** ile aşağıdaki ifadeyi yazdırın:
```sh
Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.
```
```js
console.log('Love is not patronizing and charity isn\'t about pity, it is about love. Charity and love are the same -- with charity you give love, so don\'t just give money but reach out your hand instead.') // Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.
```
3. **typeof** operatörü kullanarak **'10'** ifadesinin tam olarak **10** ile eşit olup olmadığını kontrol edin. Eşit değilse tam olarak **10** ile eşitleyin.
```js
console.log(typeof '10' === 10) // false
```
4. **parseFloat()** metodu kullanarak **'9.8'** ifadesinin tam olarak **10** ile eşit olup olmadığını kontrol edin. Eşit değilse tam olarak **10** ile eşitleyin.
```js
console.log(parseFloat('9.8') === 10) // false
```
5. **'python'** ve **'jargon'** ifadelerinde **'on'** ifadesinin bulunup bulunmadığını kontrol edin.
```js
console.log('python'.includes('on')) // true
console.log('jargon'.includes('on')) // true
```
6. **'I hope this course is not full of jargon'** ifadesinde **'jargon'** ifadesinin bulunup bulunmadığını kontrol edin.
```js
console.log('I hope this course is not full of jargon'.includes('jargon')) // false
```
7. **0** ile **100** arasında rastgele bir sayı üretin.
```js
console.log(Math.floor(Math.random() * 101)) // 0-100
```
8. **50** ile **100** arasında rastgele bir sayı üretin.
```js
console.log(Math.floor(Math.random() * 51) + 50) // 50-100
```
9. **0** ile **255** arasında rastgele bir sayı üretin.
```js
console.log(Math.floor(Math.random() * 256)) // 0-255
```
10. **'JavaScript'** ifadesindeki karakterleri rastgele bir sayı kullanarak erişin.
```js
let str = 'JavaScript'
let random = Math.floor(Math.random() * str.length)
console.log(str[random]) // J
```
11. **console.log()** ve kaçış karakterlerini kullanarak aşağıdaki deseni yazdırın.
```sh
1 1 1 1 1
2 1 2 4 8
3 1 3 9 27
4 1 4 16 64
5 1 5 25 125
```
```js
let str = '1 1 1 1 1\n2 1 2 4 8\n3 1 3 9 27\n4 1 4 16 64\n5 1 5 25 125' 
// 1 1 1 1 1
// 2 1 2 4 8
// 3 1 3 9 27
// 4 1 4 16 64
// 5 1 5 25 125
```
12. **substr** metodu kullanarak aşağıdaki cümleden **'because because because'** ifadesini kesin:
```sh
You cannot end a sentence with because because because is a conjunction
```
```js
let str = 'You cannot end a sentence with because because because is a conjunction'
console.log(str.substr(31, 23)) // because because because
```

1- 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word love in this sentence.

2- Use match() to count the number of all because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

3- Clean the following text and find the most frequent word(hint, use replace and regular express).

4- Calculate the person's total annual income by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'


### Alıştırmalar: Seviye 3

1. 'Love is the best thing in this world. Some found their love and some are still looking for their love.' ifadesindeki **love** ifadesinin kaç kez geçtiğini bulun.
```js
let sentence = 'Love is the best thing in this world. Some found their love and some are still looking for their love.'
console.log(sentence.match(/love/gi).length) // 4
```
2. Aşağıdaki cümledeki **because** ifadesinin kaç kez geçtiğini bulun:
```sh
You cannot end a sentence with because because because is a conjunction
```
```js
let sentence = 'You cannot end a sentence with because because because is a conjunction'
console.log(sentence.match(/because/gi).length) // 3
```
3. Aşağıdaki cümleyi temizleyin ve en sık geçen kelimeyi bulun (ipucu, **replace** ve **regular express** kullanın):
```sh
'%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
```
```js
let text = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
let cleanText = text.replace(/[^a-zA-Z ]/g, '')
let words = cleanText.split(' ')
let wordCount = {}
words.forEach(word => {
  if (wordCount[word]) {
    wordCount[word] += 1
  } else {
    wordCount[word] = 1
  }
})
let mostFrequent = Object.keys(wordCount).reduce((a, b) => wordCount[a] > wordCount[b] ? a : b)
console.log(mostFrequent) // teaching
```
4. Aşağıdaki cümleden kişinin yıllık gelirini çıkarın.
```sh
He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.
```
```js
let text = 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'
let numbers = text.match(/\d+/g)
let total = numbers.reduce((a, b) => parseInt(a) + parseInt(b))
console.log(total) // 30000
```
[Gün 3 >>](./../03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md)