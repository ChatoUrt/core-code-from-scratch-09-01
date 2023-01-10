# core-code-from-scratch-09-01

## ---Strings: substr()---
* [ .substr() method and how to apply it](https://www.jshero.net/en/koans/stringsubstr.html)

Solution / /
``` javascript
function firstWord(v){
  let firstS = v.indexOf(' ');
  return v.substr(0, firstS);
}
```

---
## ---String: replace()---

* [.replace() method](https://www.jshero.net/en/koans/replace.html)

Solution / /
``` javascript
function normalize(v){
  return v.replace(/-/g , '/');
}
```

---
## ---Increment---

* [Increase++, decrease--](https://www.jshero.net/en/koans/increment.html)

Solution / /
x = 7

---
## ---Fahrenheit---

* Write a function toFahrenheit that converts a temperature from Celsius to Fahrenheit.

Example: toFahrenheit(0) should return 32.

Solution / /
``` javascript
function toFahrenheit(x){
  let f = (1.8 * x + 32);
  return f
}
```

## ---Boolean---
* [Boolean](https://www.jshero.net/en/koans/bool.html)

Solution / /
``` javascript
function nand(a, b){
  let n = a && b;
  return !n
}
```

---
## Knowledge base
1. [String: .substr()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr) <br>
1.2. [String: substracting](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substring)
2. [String: .replace()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)
3. [Increment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Increment)<br>
3.2. [Decrement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Decrement)<br>
3.3. [Addition](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Addition)<br>
4. [NAND Logic table](https://testbook.com/learn/digital-electronics-nand-gate/)<br>
4.2. [What is a NAND gate](https://www.electrical4u.com/nand-gate/)
