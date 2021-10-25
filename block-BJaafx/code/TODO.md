1. Using loops take 10 inputs from user and find the average of all the numbers.
```js

let sum = 0;
for(let i= 1; i <= 10; i++){
  sum += i;
}
let average = sum/10;

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
//'hi'
//'hi'
//'hi'
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
function getEvenSum(max=10){
  let sum = 0;
  for(let i= 1; i<=max; i++){
    if(i%2===0){
 sum += i;
    }
  }
  return sum;
}
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getEvenSum(max=10){
  let sum = 0;
  for(let i= 1; i<=max; i++){
    if(i%2!==0){
 sum += i;
 
    }
  }
  return sum;
}
```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
```js
function getEvenSum(num=9){
  let product = 1;
  for(let i= 0; i<=num; i++){
    if(i%2!==0){
 product *= i;
 return product;
    }
    else{
      return `not a valid input`;
    }
  }
  
}
```
- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

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

check(10); // output is 'Bigger than 5' because condition first goes true the num is greater than 5;
check(1); // output is 'Smaller than 5' because condition second goes true the num is greater than 5;
check(5); // output num all because all conditions goes wrong.
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya' we call a function argument 'Arya' so it check in if condition the first condition is true so it return the 'You are arya'.
getOutput('John'); // 'You are john'because condition second goes true.
getOutput(); // 'Who are you' because all conditions goes wrong.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // it log the value 'You are arya' and will return 'Who are you
getOutput('John'); //it log the value 'You are john' and will return 'Who are you
getOutput(); // return 'Who are you'.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
```js
function multipleReturn(digit){
  switch(marvel){
    case 1:
    return `One`;
    break;
    case 2:
    return `Two`;
    break;
    case 3:
    return `Three`;
    break;
    case 4:
    return `Four`;
    break;
    default:
    return `write a valid statemenr`;
    }
}
multipleReturn(3);
// we use multiple return statment beceause when the use give different input it give different output
``
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
/* 
for loop take 3 statment .
1. use for initization by defining a value.
2. condition it help the loop in deciding when to stop the loop when ever the condition does false it stop the loop.
3. Explain what to do after ever iteration.
/*
/*
while loop take the condition if the condition is true it execut the body
the condition is false loop break