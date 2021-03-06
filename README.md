# Javascript Homework

1.  Variables
    - https://www.youtube.com/watch?v=cXUWYZXru6o (7 min video)
    - https://www.codeanalogies.com/jsconstruction/ (interactive game)

2.  Conditions
    - https://blog.codeanalogies.com/2018/06/18/javascript-booleans-explained-by-going-to-court/ (reading)


## Assignment Operator
Without running the following code, try to determine:

```js
let a = 1;
let b = 'bongos';
let c = true;

a = b;
b = c;
c = a;
```

### Your solution here:
1.  What is `a`?
```
a is bongos
```
2.  What is `b`?
```
b is true
```
3.  What is `c`?
```
c is bongos
```

## Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". Make sure there are spaces in-between each word.

```js
const firstWord = "Please";
const secondWord = "squeeze";
const thirdWord = "the";
const fourthWord = "cheese";
```
Result should be:
```js
"Please squeeze the cheese"
```

### Your solution here:
4.  Fill in the `console.log()`?
```js
console.log(firstWord + " " + secondWord + " " + thirdWord + " " + fourthWord)
```


## Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false
```
a) 999 > 999
b) 999 === 999 
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5 
g) 81 / 9 === 9
h) 9 !== 8 + 1
```
### Your solution here:
7.  Write `true` or `false` based on the list above
```
a) false
b) true
c) false
d) false
e) false
f) false
g) true
h) false
```

## Conditionals
Declare a variable equal to a number 0 to 100

Write a conditional statement that...
- If it is a multiple of 3, print “Fizz” instead of the number.
- If it is a multiple of 5, print “Buzz” instead of the number.
- If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
- Otherwise, print the number

### Your solution here:
8.  Write your javascript solution below
```js
// your answer here
let number = 9

if(number % 5 === 0 && number % 3 === 0) {
  console.log('FizzBuzz')
} else if (number % 3 === 0){
  console.log('Fizz')
} else if (number % 5 === 0){
  console.log('Buzz')
} else {
  console.log(number)
}
```

## Functions

### currencyConverter(currency, amount)

Define a function `currencyConverter` that takes two arguments an amount and a currency (USD, GBP, EGP, BD) and returns the converted version of the amount in Riyals. Use the if-then-else construct available in Javascript.

**Hint :**
> - 1 Riyal = 4.68 Egyptian pound 
> - 1 Riyal = 0.10 Bahraini dinar

```js
function currencyConverter(currency, amount){
  if( currency === "USD"){
    console.log(amount / 0.27)
  } else if (currency === "GBP"){
    console.log(amount / .21)
  } else if (currency === "EGP"){
    console.log(amount / 4.68)
  } else if (currency === "BD"){
    console.log(amount / .10)
  } else {
    console.log('We only have (USD,GBP,EGP,BD) currencies')
  }
}

currencyConverter('BD', 2) // Result: 20
```
---

### isCharacterAVowel(character)

Write a function `isCharacterAVowel` that takes a character (i.e. a string of length 1) and returns true if it is a vowel and false, otherwise.

```js
function isCharacterAVowel(character){
  if(character.toUpperCase() === "A" || character.toUpperCase() === "E" 
  || character.toUpperCase() === "I" || character.toUpperCase() === "O" 
  || character.toUpperCase() === "U" || character.toUpperCase() === "Y")
  {
    console.log(true)
  } 
  else {
    console.log(false)
  }
}

isCharacterAVowel("y") // Result: true
isCharacterAVowel("r") // Result: false
```
---

## [Homework submission how to!](https://git.generalassemb.ly/sei-jeddah/sei-12/blob/master/lessons/week_1/day_2/Homework-Submission.md)

# Additional Resources
For more practice read about...
- https://javascript.info/variables
- https://javascript.info/types
- https://javascript.info/operators
- https://javascript.info/comparison
- https://javascript.info/ifelse
- https://javascript.info/logical-operators
- https://javascript.info/function-basics

