1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
First sum return the sum of a and b and second will only log the sum of a and b and it will undefined.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
```
First value will give sum of a and b but second value give undefined.
```

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
```
undefined .Because we have only two parameters a and b and we pass three value.
```
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
```
Yes because function is a expression and expression gives vale so we can store function in a variable add.
```

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```
function sayHello(name){
return `Hello ${name}` 
}
 sayHello("Arya");
```
6. What will be the output of the function below and why?


```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();

```
"Hello John" .userName search local variable and not find userName variable so it search outer variable from function and got the value of userName ("John");

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // "john"

showMessage(); // "Hello John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
```
When we not use function name then it's called anonymous function
Example-
let num =function(num1,num2){
  return num1+num2;
} 
```

9. Can function declaration be a Anonymous Function? Explain
```
Yes function declaration be a anonymous function arrow function is one of them.
```

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
```
additionTwoNumber
multiplicationOfNumber
concatinateString
calculateLeapYear
conertNumbertoString

```

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
