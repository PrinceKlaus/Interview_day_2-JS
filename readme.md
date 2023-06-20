  ### Q9-what is event loop and call stack? 
  ```
  <b>ANS:</b>Event loop in JavaScript is a mechanism through which the 'calls waiting for execution' in the callback queue/job queue can be put on the call stack. For any event from the callback queue/job queue to <br>come to call stack, the call stack will have to be empty.
  ``` 
  <!----------------------------------------------------------------------->
  ### Q10-What is creation phase and execution phase?
  ```
  <b>ANS:</b>CREATION PHASE: it is one of phase of execution context where we declare varisble.
        EXECUTION PHASE: it is one of the phase of execution context where we assing value to variable.
  ``` 
 ### Q11-What is the spread operator?
  ```
  <b>ANS:</b>The JavaScript spread operator ( ... ) allows us to quickly copy all or part of an existing array or object into another array or object.
  ```
  <!-- ---------------------------------------------------------- -->
  ### Q12-What is the use of setTimeout?
  ```
  <b>ANS:</b>The global setTimeout() method sets a timer which executes a function or specified piece of code once the timer expires.
  ``` 
  <!-- ------------------------------------------------------ -->
  ### Q13-What are callbacks? 
   ```
  <b>ANS:</b>A JavaScript callback is a function which is to be executed after another function has finished execution. A more formal definition would be - Any function that is passed as an argument <br>to another function so that it can be executed in that other function is called as a callback function.
  ``` 
  <!-- ------------------------------------------------------- -->
  ### Q14-What is callback hell? 
  ```
  <b>ANS:</b>Callback hell is a phenomenon that happens when multiple callbacks are nested on top of each other. The two common ways of escaping the callback heare are by using promises and <br>async/await. Promises mainly have three stages such as resolved, rejected, and pending. It makes the code more maintainable and understandable.
  ``` 
  <!-- ----------------------------------------------------- -->
  ### Q15-Difference between undefined vs not defined vs NaN?
  ```
  <b>ANS:</b>undefined isn't converted into any number, so using it in maths calculations returns NaN. NaN (Not-A-Number ) represents something which is not a number, even though it's actually a number.
 ```
 - 5:26
 - code
 - 5:26
 - 5:26
 - Spread Operator - Array
 - // const arr = [2,3,4,5,6,7,8,9];
 - // // for(let i = 0 ; i < arr.length ; i++){
 - // //    console.log(arr[i]);
 -  // // }
 -  // console.log(...arr);
 -  // console.log(arr);
 -  // const arr2 = [...arr, ...arr1]
 -  // // console.log(arr2);
 - // // Spread Operator - Function
 - // const arr1 = [1,11, 12, 10]
 - // function Sum(a, b, c){
 - //    console.log(a, b, c);
 - //    return a + b + c;
 - // }
 - // console.log(Sum(...arr1));
 - // Spread Operator - Object
 - // const Obj1 = {
 - //    name : "Dabloo",
 - //    Age : 23
 - // }
 - // const Obj2 = {
 - //    Course : "MERN",
 - //    ...Obj1
 - // }
 - // console.log(Obj1);
 - // console.log(Obj2);
 - // Output
 - // function Display(){
 - //    let time = new Date();
 - //    let hr = time.toLocaleTimeString();
 - //    console.log(hr);
 - // }
 - // setInterval(() => {
 - //    Display();
 - // }, 2000);
 - // setTimeout(() => {
 - // }, 1000);
 - // Display();
 - // Callback function
 - // function greet(name, func){
 - //    console.log(`Hi ${name}`);
 - //    console.log(func());
 - // }
 - // function Sum(){
 - //    console.log("Hey....");
 - // }
 - // // greet('EA23', Sum())
 - // greet('EA23', Sum)
 - console.log(0/0);
 - var a=10;
 - var b="abc"
 - console.log(a - b)