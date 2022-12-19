#  JavaScript Problems

  

  

 ## 1.  Create a function that takes an integer as an argument and returns `"Even"` for even numbers or `"Odd"` for odd numbers.



  

```jsx

function  evenOrOdd(number)  {

if(number %  2  ===  0){

console.log('even')

}  else{

console.log('odd')

}

}

evenOrOdd(4)  //0 even

evenOrOdd(3)  //1 odd

```

  

```jsx

function  evenOrOdd(number)  {

return number %  2  ===  0?  'even'  :  'odd'  ;

}

console.log(  evenOrOdd(4)  )

```

  

**explain : we used % reminder operator خارج القسمة لرقمين**

  

4/4 = 0 , 5/4 = 1, 9/8 = 1

  

[Remainder (%) - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Remainder)

  

---
