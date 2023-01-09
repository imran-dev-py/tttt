# ....

- [10 of the best CSS animation libraries.](https://dev.to/weeb/10-of-the-best-css-animation-libraries-31d7)
- [Awesome js libraries](https://twitter.com/sunilc_/status/1336371860649361408)
- [before jumping to a Javascript framework](https://twitter.com/laasrinadiaa/status/1325468732639109121) | [another](https://twitter.com/ravinwashere/status/1339530417834131462)
- [8 JavaScript Concepts you need to be familiar with!](https://twitter.com/SimonHoiberg/status/1334548171175976968)
- [56 Javascript tools and plugins for you](https://twitter.com/TechParida/status/1332657326705180677)
- [10 Interview Questions Every JavaScript Developer Should Know](https://twitter.com/nickbulljs/status/1317813251053441024)
- [Spread operator tips](https://twitter.com/girlie_mac/status/1263955788990566400/photo/1)
- [Lambda in js](http://willtaylor.blog/an-introduction-to-lambda-calculus-explained-through-javascript/)
- [Web path](https://twitter.com/javascriptual/status/1236415196509470722)
- [front-end topics](https://gist.github.com/emmabostian/aea646464456c2fb4ad66f1051faba83)
- [dsa](https://gist.github.com/emmabostian/c996c68458dd5eb770529b52dd7bfb00)
- [CALL A JAVASCRIPT FUNCTION WITH AN EXPLICIT THIS](https://delicious-insights.com/en/posts/call-and-apply-in-javascript/)
- [Hot Tips from Wes Bos](https://twitter.com/wesbos/timelines/1189618481672667136)
- [Useful software development tools for Web Development](https://twitter.com/Carlillo/status/1328085569625264130)


![Language](https://img.shields.io/badge/JavaScript-vES6+-important)&nbsp;
![Update](https://img.shields.io/badge/Last%20Update-September%2028,%202022-brightgreen)&nbsp;

Once we copy a variable, the new variable is distinct from old one.

```js
let variable = 'abc';
let variableCopy = variable;
console.log(variableCopy); // -> abc
```

- `undefined` is a special variable type used to indicate that something is missing
	- the JavaScript engine will make variables that have no value `undefined`

```js
let falseFlag = false;

if(falseFlag) console.log('This will not print.');
else console.log('This will print!');
```

How Js run codes without `{}`. Technically if statement run only next line/item it sees. when we declare if with `{}` this block, the entire block consider as item, when without `{}` block, it runs only next line.

`===` doesn't allow coercion | where `==` allow coercion, either left or right or both

The double-equal sign is symmetric. That is, `if a == b` is `true`, then `b == a` is also `true`, for all values `a` and `b`.

if we use a function with return statement without returning any value it will return `undefined`

```js
// returning multiple values from function only return last value
function add(num1, num2) {
    let newNumber = num1 + num2;
    return 10,12,15;
}

let twenty = add(5, 15);
console.log(twenty); // -> 15 //=> why?
```

if `key` in `object` is a variable then we must have to use `[]` this notation. If key is `string` we can use both `.` || `[]`
