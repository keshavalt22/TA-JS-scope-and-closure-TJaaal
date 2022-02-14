1. What does thread of execution means in JavaScript?

Ans: Executing a code line by line is known as thread of execution in JavaScript.

2. Where the JavaScript code gets executed?

Ans: JavaScript code gets executed in global execution context.

3. What does context means in Global Execution Context?

Ans:  The environment in which the JavaScript code is executed can be defined as context.

4. When do you create a global execution context.

Ans: Global execution context gets created once when a program is created or when we load a JavaScript file.

5. Execution context consists of what all things?

Ans: Execution context consists of two things one the memory where all the veriable are stored and the other part is where the all the codes are executed.

6. What are the different types of execution context?

Ans: Global execution context created only once through out the program and Function execution context get created every time a function has to be executed.

7. When global and function execution context gets created?

Ans: Global execution context created only once through out the program and Function execution context get created every time a function has to be executed.

8. Function execution gets created during function execution or while declaring a function.

Ans: Function execution gets created during function execution.

9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./media/sayHello.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./media/getPercentage.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./media/customMessage.jpg)