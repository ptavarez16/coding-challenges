Using the JavaScript language, have the function FirstReverse(str) take the str
parameter being passed and return the string in reversed order. For example: if
the input string is "Hello World and Coders" then your program should return
the string sredoC dna dlroW olleH. 

```javascript
function FirstReverse(str) {

  let splitty = str.split('')
  let reverseArr = splitty.reverse()
  let joinArr = reverseArr.join('')
  
  return joinArr;
         
}
```