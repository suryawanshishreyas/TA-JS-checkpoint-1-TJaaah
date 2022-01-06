1. Using loops take 10 inputs from user and find the average of all the numbers.
```
let sum=0;
var numbers = new Array(10,20,30,40,50,60,70,80,90,100);
  for(i=0; i<10 ; i++){
    sum+= numbers[i];
  }
let average=sum/10;
alert(`${average}`);



2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```error on println statement

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
max=10;
function getEvenSum(max){
  let q=2, sum=0
  for(let i=1; i<=max ; i++){
    sum = sum + q;
    q=q+2;
  }
  return sum;
}
let msg=getEvenSum(10);
alert(msg)

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

max=10;
function getOddSum(max){
  let q=1, sum=0
  for(let i=1; i<=max ; i++){
    sum = sum + q;
    q=q+2;
  }
  return sum;
}
getOddSum();
let msg=getOddSum(10);
alert(msg);

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.
``` 

```function getProductofDigits(num){
  let product=1;
  
  while(num!=0){
    product = product * (num%10);
    num= num/10;
  }
  return product;
}
getProductofDigits();```

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

check(10); // assuming function has been called,op will be 'Bigger than 5'
check(1); // 'smaller than 5'
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya' reason is it matches with the condition of if 
getOutput('John'); // 'You are john'reason is it matches with the condition of if 
getOutput(); // 'Who are you' reason is that function is called without passing any values so it returned with its default statement.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // 'who are you' because although it matches with if statement but theres no return statement following it. although 'you are arya' gets printed on console.
getOutput('John'); // 'who are you' because although it matches with if statement but theres no return statement following it. although 'you are john' gets printed on console.

getOutput(); // 'Who are you' reason is that function is called without passing any values so it returned with its default statement.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

/* Yes a function can have multiple return statement consider if else statement.
assume, */
function check(a,b){
  if(a<b){
    return ('b is bigger');
  }
  else{
    return ('a is bigger');
  }
  return a,b;
}

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
// for loop is helpful when there are set limits on compilation of program lets say starting from '20' take 10 even numbers and calculate addition.
Similarily while loop is used when you want to repeat loop until a condition happens or it doesnt.Imagine buying phones using your credit card until your balance gets zero.(while balance!=0){//buy phones//}