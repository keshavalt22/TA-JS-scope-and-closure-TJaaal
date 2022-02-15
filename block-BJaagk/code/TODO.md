1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = function (marks, total) {
  return (marks * 100) / total;
}

let percentage = (marks, total) => {
  return (marks * 100) / total;
};

let percentage = (marks, total) => (marks * 100) / total;

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer


```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
<!-- Function Declaration -->

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
<!-- Function Expression -->

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
<!-- Function Expression -->

```js
let percentage = (marks, total) => (marks * 100) / total;
```
<!-- Function Expression -->

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Ans:  function is a object in JavaScript and it can be stored in a variable, which makes function definition a expression.

4. Why is a function call an expression in JavaScript?



5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer valid, the return will be stored in valiable which is five.
five = add; // Answer invalid, there is no let var or const which can direct to what we are doing.
five = five(10, 11); //Answer invalid, there is no let var or const which can direct to what we are doing.
five = function () {
  return 'Hello';
}; // Answer invalid, there is no let var or const which can direct to what we are doing.
```

6. What is the difference between function definition and function call? Explain with an example.

Ans: when a function is starting whith the function keyword it is an function defination, 

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
```
when we have to execute a function and we call it with paranthesis it is known as function call.

```js
percentage(398, 500)
```

7. What is the similarities between function definition and function call?

Ans: they both have the function name and paraenthesis.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid
```

9. What is higher order function explain with an example.

Ans: Any function which takes function as an argument or returns a function is known as higher order function. 

```js
function fullName (fistName,lastName) {
return `${firstName} ${lastName}`;
}

function hello("",fullName){

}

function filltereven(arr){
  return function(){};
} 

```

10. Explain what is callback function. Why you can pass a function inside a function?

Ans: A callback function is a function passed into another function as an argument. this method helps us to reduce the size of the code resulting the same outcome.
