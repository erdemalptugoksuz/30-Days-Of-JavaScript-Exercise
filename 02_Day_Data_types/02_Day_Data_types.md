## 💻 Day 2: Exercises

### Exercise: Level 1

1. Declare a variable named challenge and assign it to an initial value **'30 Days Of JavaScript'**.
```js
let challenge = '30 Days Of JavaScript' // string
```
2. Print the string on the browser console using __console.log()__
```js
console.log(challenge) // 30 Days Of JavaScript
```
3. Print the __length__ of the string on the browser console using __console.log()__
```js
console.log(challenge.length) // 21
```
4. Change all the string characters to capital letters using __toUpperCase()__ method
```js
console.log(challenge.toUpperCase()) // 30 DAYS OF JAVASCRIPT
```
5. Change all the string characters to lowercase letters using __toLowerCase()__ method
```js
console.log(challenge.toLowerCase()) // 30 days of javascript
```
6. Cut (slice) out the first word of the string using __substr()__ or __substring()__ method
```js
console.log(challenge.substr(0, 2)) // 30
```
7. Slice out the phrase __Days Of JavaScript__ from 30 Days Of JavaScript.
```js
console.log(challenge.substr(3)) // Days Of JavaScript
```
8. Check if the string contains a word __Script__ using __includes()__ method
```js
console.log(challenge.includes('Script')) // true
```
9. Split the string into an array using __split()__ method
```js
console.log(challenge.split()) // [ '30 Days Of JavaScript' ]
```
10. Split the string 30 Days Of JavaScript at the space using __split()__ method
```js
console.log(challenge.split(' ')) // [ '30', 'Days', 'Of', 'JavaScript' ]
```
11. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.
```js
let companies = 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon'
console.log(companies.split(', ')) // [ 'Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon' ]
```
12. Change 30 Days Of JavaScript to 30 Days Of Python using __replace()__ method.
```js
console.log(challenge.replace('JavaScript', 'Python')) // 30 Days Of Python
```
13. What is character at index 15 in '30 Days Of JavaScript' string use __charAt()__ method.
```js
console.log(challenge.charAt(15)) // a
```
14. What is the character code of J in '30 Days Of JavaScript' string using __charCodeAt()__
```js
console.log(challenge.charCodeAt('J')) // 74
``` 
15. Use __indexOf__ to determine the position of the first occurrence of a in 30 Days Of JavaScript
```js
console.log(challenge.indexOf('a')) // 1
```
16. Use __lastIndexOf__ to determine the position of the last occurrence of a in 30 Days Of JavaScript.
```js
console.log(challenge.lastIndexOf('a')) // 14
```
17. Use __indexOf__ to find the position of the first occurrence of the word __because__ in the following sentence: 'You cannot end a sentence with because because because is a conjunction'
```js
let sentence = 'You cannot end a sentence with because because because is a conjunction'
console.log(sentence.indexOf('because')) // 31
```
18. Use __lastIndexOf__ to find the position of the last occurrence of the word __because__ in the following sentence: 'You cannot end a sentence with because because because is a conjunction'
```js
console.log(sentence.lastIndexOf('because')) // 47
```
19. Use __search__ to find the position of the first occurrence of the word __because__ in the following sentence: 'You cannot end a sentence with because because because is a conjunction'
```js
console.log(sentence.search('because')) // 31
```
20. Use __trim()__ to remove any trailing whitespace at the beginning and the end of a string.E.g ' 30 Days Of JavaScript '.
```js
let trim = ' 30 Days Of JavaScript '
console.log(trim.trim()) // 30 Days Of JavaScript
```
21. Use __startsWith()__ method with the string 30 Days Of JavaScript and make the result true
```js
console.log(challenge.startsWith('30')) // true
```
22. Use __endsWith()__ method with the string 30 Days Of JavaScript and make the result true
```js
console.log(challenge.endsWith('Script')) // true
```
23. Use __match()__ method to find all the a’s in 30 Days Of JavaScript
```js
console.log(challenge.match(/a/gi)) // [ 'a', 'a', 'a', 'a' ]
```
24.  Use __concat()__ and merge '30 Days of' and 'JavaScript' to a single string, '30 Days Of JavaScript'
```js
let first = '30 Days of'
let second = 'JavaScript'
console.log(first.concat(' ', second)) // 30 Days of JavaScript
```
25.  Use __repeat()__ method to print 30 Days Of JavaScript 2 times
```js
console.log(challenge.repeat(2)) // 30 Days Of JavaScript30 Days Of JavaScript
```

### Exercise: Level 2

1. Using console.log() print out the following statement:
```sh
The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another
```
```js
console.log('The quote \'There is no exercise better for the heart than reaching down and lifting people up.\' by John Holmes teaches us to help one another.') // The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.
```
2. Using console.log() print out the following quote by Mother Teresa:
```sh
Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.
```
```js
console.log('Love is not patronizing and charity isn\'t about pity, it is about love. Charity and love are the same -- with charity you give love, so don\'t just give money but reach out your hand instead.') // Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead.
```
3. Check if typeof '10' is exactly equal to 10. If not make it exactly equal.
```js
console.log(typeof '10' === 10) // false
```
4. Check if parseFloat('9.8') is equal to 10 if not make it exactly equal with 10.
```js
console.log(parseFloat('9.8') === 10) // false
```
5. Check if 'on' is found in both python and jargon
```js
console.log('python'.includes('on') && 'jargon'.includes('on')) // true
```
6. I hope this course is not full of jargon. Check if jargon is in the sentence.
```js
let sentence = 'I hope this course is not full of jargon'
console.log(sentence.includes('jargon')) // true
```
7. Generate a random number between 0 and 100 inclusively.
```js
console.log(Math.floor(Math.random() * 101)) // 0 - 100
```
8. Generate a random number between 50 and 100 inclusively.
```js
console.log(Math.floor(Math.random() * 51) + 50) // 50 - 100
```
9. Generate a random number between 0 and 255 inclusively.
```js
console.log(Math.floor(Math.random() * 256)) // 0 - 255
```
10. Access the 'JavaScript' string characters using a random number.
```js
let random = Math.floor(Math.random() * 11)
console.log('JavaScript'[random]) // J
```
11. Use console.log() and escape characters to print the following pattern.
```sh
1 1 1 1 1
2 1 2 4 8
3 1 3 9 27
4 1 4 16 64
5 1 5 25 125
```
```js
console.log('1 1 1 1 1\n2 1 2 4 8\n3 1 3 9 27\n4 1 4 16 64\n5 1 5 25 125') 
// 1 1 1 1 1
// 2 1 2 4 8
// 3 1 3 9 27
// 4 1 4 16 64
// 5 1 5 25 125
```
12. Use substr to slice out the phrase because because because from the following sentence:'You cannot end a sentence with because because because is a conjunction'
```js
let sentence = 'You cannot end a sentence with because because because is a conjunction'
console.log(sentence.substr(31, 23)) // because because because
```

### Exercise: Level 3

1. 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word love in this sentence.
```js
let sentence = 'Love is the best thing in this world. Some found their love and some are still looking for their love.'
console.log(sentence.match(/love/gi).length) // 4
```
2. Use match() to count the number of all because in the following sentence:'You cannot end a sentence with because because because is a conjunction'
```js
let sentence = 'You cannot end a sentence with because because because is a conjunction'
console.log(sentence.match(/because/gi).length) // 3
```
3. Clean the following text and find the most frequent word(hint, use replace and regular expressions).
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
4. Calculate the person's total annual income by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'
```js
let text = 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'
let numbers = text.match(/\d+/g)
let total = numbers.reduce((a, b) => parseInt(a) + parseInt(b))
console.log(total) // 30000
```

## Support to Organizer
  * [Ad Link](https://ay.live/lYtYWg)

[Day 3 >>](../03_Day_Booleans_operators_date/03_Day_Booleans_operators_date.md)