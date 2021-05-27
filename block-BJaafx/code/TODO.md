1. Using loops take 10 inputs from user and find the average of all the numbers.
```
let number=+prompt("Enter inputs);

```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```
function getEvenSum(max){
  let even=0;
  for(let i=1;i<=10;i++){
    if(i%2==0){
 even=even+i
    }
  }
  return even;
}
getEvenSum();

```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```
function getOddSum(max){
  let odd=0;
  for(let i=1;i<=10;i++){
    if(i%2!==0){
 odd=odd+i
    }
  }
  return odd;
}
getOddSum();
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
```
function getProductOfDigits(num){
  let number=1;
  for(let i=1;i<=n;i++){
    number=number*i;

  }
  return number;
}
getProductOfDigits();

```
- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
```

```

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // "Bigger than 5"
check(1); // "Smaller than 5"
check(5); //5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'
getOutput('John'); // 'You are john'
getOutput(); // "Who are you"
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); //You are arya. And its return "Who are you"
getOutput('John'); //You are john.And its return "Who are you"
getOutput(); //"Who are you"
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
```
Yes a function have multiple return statement 

function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
```
for loop has initialization condition and ittration so when value get false it will stop execution .Other than this while loop take a condtion if it true then it will execute body and when its false  it break the body.
we use for if we have finite value means initial value and final value .
we use while if we have no idea about final value.



```