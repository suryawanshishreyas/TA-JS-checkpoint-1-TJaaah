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
``` This wont return anything and output will be undefined first sum will result in value. ```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

``` In first function it will return with value and second function wont return any value as 'return' is not declared ```

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

``` output will be '36' as it will accept first two values a and b.```

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

``` Yes because function can be executed or called which returns a value . Also variables are used to store values so 'sum' function can be stored in 'add'.```

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

``` 
function sayHello(name){
  return `Hello ${name}`
}
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
``` Output will be undefined because userName is a local variable declared as John whereas the function is not taking arguments for userName.```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // Undefined

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.

``` Anonymous functions are those which are not declared with name.for ex-var hello=function(), var name=function(), var height=function() ```

9. Can function declaration be a Anonymous Function? Explain.

``` No because function declaration is only possible with function name unlike anonymous function which can only be declared without function name```

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

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
"add' -add something
"fetch" -fetch something
"getNoOfPages" - returns with no of pages in book
"checkTrue"-check if returns true
"createString"- creates string 
