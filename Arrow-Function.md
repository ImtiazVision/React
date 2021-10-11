Arrow functions are often used in React to improve efficiency and simplicity (Event Handling, preventing bugs, etc.).

 ES6 style arrow function :  
```
const arrowFunction1 = () => {
  return 'Welcome to arrow 1 function`;
} 

console.log(arrowFunction1());
```
ES6 arrow function with no body and implicit return : 

```
const arrowFunction2 = () => 
  'Welcome to arrow 2 function with no body and return type';
  console.log(arrowFunction2());
```

We must keep the following considerations in mind while developing an arrow function or converting an existing function into an arrow function:

- If the function body has only one statement, we may eliminate the return keyword as well as the curly brackets.

- Remove the function keyword at the start.

- If we just have one parameter, we may also remove the parameter parenthesis.

In React apps, JavaScript arrow functions are frequently utilized to make the code simple and understandable.
