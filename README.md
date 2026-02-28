# JavaScript
**Important Topic/No Covered Topics**

  1. Event Bubbling
  2. Event capturing
  3. event Propogation
  4. event Deligation
---

---> It is a programming languange, it was called **Scripting language** before 2010. Only in the browser before 2010, but now we can use it anywhere.
**Programming Language**: Any language which can take some input and process it, and based on condition it can take decision and generate output.

# What is the purpose of JavaScript?

---

---> It used to create **Dynamic User Interface**(it is used to create dynamic web page).
---> It is used to do client side Validation and **server side validation**.
---> It is used to interact or integrate **Frontend application and Backend application.**

# What kind of applicaiton we can build usign JavaScript?

---

---> We can develop Web Application **(Frontend, Backend, manage database)**
---> we can develop Mobile Application(Android, ios).
---> We can develop desktop app or standalone app.
---> We can build ML App.

**Variables**

---

---> Varibles are the references which points to the memory location
**Why do we required Variables?** ---> To store the data in the memory while executing the program, so that we can utilze the data to do some action or after executing the program, we might required to store some output.

# What is Program?

---> Program is a set of Instruction to perform some actions.

`What is Process?` --> Process is the running state of Program.

`Questions:` 1. What is variable? 2. What is a program? 3. What is Process? 4. Why do we want varibales in the program? 5. What is the difference between variable declaration and varible Initialization

`How to create Variabless in JS?`
---> We need **Scope Statements** 
---> There are 3 Scope Statements: var, let, const

`Syntax`
<Scope Statement><Variable Name>(declaration of variables) = {**value**}(this part is called Variable Assignment) **This whole part called Variable Intialization**
Varibles Intialization: It is a process of creating variable and at that tiem only storing the data inside the memory where that varibale is pointing.

# Data types in JS:

---

There are totally 8 data types in JS
`Primitive Data type`

1. String
2. number
3. Boolean --- True/False
4. BigInt
5. Undefined
6. null
7. Symbol

`Non Primitive Data Type` 8. Object

**In how many Categories Data types are divide** --->
THe datatypes are divided into 2 categories 1. `Primitive DataTypes`: In built data types and all are immutable(can't change) 2. `Non Primitive Datatype`: which are derived from Primitive datatype, its value can be modified--- Mutable dataypes.

# Number types:

    integers or decimal comes under this datatyeps.
    var city = 32123
    var dec = 1.122

# String types

    " " or ' ' or ` ` written inside of this
    var city = `hyderabad`

# Boolean types

    it only consist True or falase
    var isPlaced = true

**In JavaScript, there are two **special values** and they are**

1.  undefined: datatype is also undefined
2.  null:datatype is also null
    --> But, in JavaScript null value is considered as an object: Primitive type

# Bigint

Any value whis is greator that 2^A(53-1)

# Symbol

Any data which is created using Symbol() constructor comes under symbol type
Symbol() Constructor

# Object

To any varibale if we are assigning object or array that comes under object type
---> var name = {}
---> var users = []

# Funciton in JS

`Topics`

1.  What are functions
2.  Parameterised Functions
3.  return function: return keyword
4.  anonymous function
5.  callback function
6.  higher order function
7.  arrow functions

----> Function are set of statements or code or instruction wrapped in the block that perform some action or task
----> Syntax for creating function(funciton declaration):
**Syntax**
keyword <---function <Fun_name>(){
<set_of_instructions>; >>>Function scope or block;
}

**undefined**
---> Whenever we create a variable or parameter and if we don't assign any value to it then javascript automatically will assign one special value to the varible and parameter that special value is undefined.

**Anonymous Function**
---------------------
Function without name is called anonymous funciton
`Syntax`
function(){
    Statements;
}
---------------------------------------------------------------------------------------------------------------------------------------
*As an argument we can pass number, string, or boolean type of data, but apart from this we can pass one function also as an argument*
   **Type of Function which could be pass as an argument** --- Any type of function can be passed as an argument
   1. Normal Function
   2. Parameterised function
   3. Anonymous Function

---------------------------------------------------------------------------------------------------------------------------------------

```undefined + undefined or undefined + Number -`NaN(Not a Number)`-```

Any function which we are `passing as an argument` those functions are called **Callback function**

fn(function (){

    var city = "Delhi";

    console.log(city);
});

---------------------------------------

Any function which is taking **another function as an argument** that function is called **Higher order function**

```Functions are called Higher Order Fucntion only if it takes minimu one function as an argumnents```


input(parameters, Arguments)--->Functdion --->Output(return statement)

**Returned Function** --- When a function return another function is called Returned Function.

`Note`<br>

return should be the last statement inside the function

After return statement if you write anything, it will not execute

### What is Funciton expression?

Function expression is a technique or process of assigning an anonymous function to a varible.

**Objects in JavaScripts**
--------------------------

`Object is Datatype and collection of Properties where each property will be in the key value pair.`<br>
We can store multiple values in an object

on Object we can perform 4 operations:
  1. Red or access the data.
  2. Insert or write the data.
  3. Update the data.
  4. Delete.


`How to create Object in JavaScript`
------------------------------------

 ---> There are two ways to create objects in JavaScripts i.e.
       1. Object Literal
       2. Object Constructor.

# Object Literal
-----------------

    var userdetails = {values}

   **How data will be stored inside the Object**
   ---------------------------------------------

     ---> Inside the Object we can store data in the form of Properties
     ---> Every Property inside the Object will be in key value pair
      
          name:"Sooraj"

          name ---> Key 
<br>      Sooraj--> Value

**How to access Specific Property from the Object**

Syntax:
-------
        1. <ObjectNmae>.<keyName>
        2. <ObjectName>['KeyName']


`Note` Inside the Object every Property should have unique key---<u>If we double or tripled the key the value get updated or overwrite<u>

  **Order of Property doesn't matter in Object**


### How to insert or add or write new Property inside the Object
-----------------------------------------------------------------

Syntax:
-------
      <ObujectName>.<keyName> = <New_Value>


### How to Modify or Update value of a Property in the object
----------------------------------------------------------


--->Even after if our object is const var stil the property can  be changed.
Syntax:
-------
       <ObjectName>.<keyName>= <New_Value>

### How to Delete value of a Property in the object
---------------------------------------------------

Syntax:
-------

   `delete` <ObjectName>.<keyName>


## Arrays 
----------

 

 Syntax:
 =======
        var details = []  `empty array`
        var users = ["Hello", true, 101]
        **The indexing is starts from 0 and goes to n-1**

 ```To findi length of array``` --- Use .lengh property it will show total number of elements
 ```How to add new element inside the array at last position?``` --- use push method<br>
     Syntax:
     -------
          <array>.push(value)

```Add element at startin position``` --- <array>.unshift(value)

```To add any element at any specific position``` --- we use slice

### Splice 
----------
   **Syntax**

   ---> ```arrayName.splice(startingIndex, NumberOfElementswantsToRemove, elements you want to add)```

### Slice
--------- 
   
   ----> ```It is used to extract the part of array```
   ----> Slice will return an array
   ----> Slice does not modify original array
   **Syntax**
        ----> arrayName.slice(startingindex, lastIndex)
        `Note`: Last index is not included while extracting the elements ---always less one than the value of Last element for extraction.

```How to remove element from starting and last position``` --
       **for first element** we use shift() method
       **For last element** we use pop() method
              ---> [***Pop method return the valu7e it removes from the array.***]



**IndexOf()**
--------------

    ----> To check the index of element of array.


**Includes**
------------

    ---->It checkts the element is present in the array or not.
    ---->Returns boolean value{true, false}

  `Syntax`
    -----> arrayName.includes(element)


### forEach()
-------------

    ----> <arrayName>.forEach(callabckFunction(element,index){
           conole.log(element, index)
          })

   ----> forEach() callback Function does not returns any value it return **undefine**.



### map()
=========

   <arrayName>.map(function(element, index){
    return <SomeValue>
   })


### filter()
============
   ---> It is used to filter elements or data from the array based on certain condition
   ---> filter callback function will return always a boolean value.
   
`Syntax`
      <arrName>.filter(funciton(element,index){
        return <boolean value>
      })


# Operators in JavaScript

There are **6 categories of operators** in JavaScript.

---

## 1. Arithmetic Operators
- `+` (Addition)
- `-` (Subtraction)
- `*` (Multiplication)
- `/` (Division)
- `%` (Modulus)
- `++` (Increment — pre and post)
- `--` (Decrement — pre and post)

---

## 2. Comparison or Relational Operators
- `>` (Greater than)
- `<` (Less than)
- `==` (Equal to){<It do the type conversion if the types are different and then check the value>}
- `===` (Strict equal to){<It check the type and if it diffrent then it return false, if same type then it check the value>}
- `>=` (Greater than or equal to)
- `<=` (Less than or equal to)
- `!=` (Not equal to)

---

## 3. Logical Operators
   --> Logical operators are used to check two statement or two boolean values
   --> It can used for decision making as well.

- `&&` (Logical AND)
- `||` (Logical OR)
- `!` (Logical NOT)

---

## 4. Bitwise Operators
- `&` (Bitwise AND)
- `|` (Bitwise OR)
- `~` (Bitwise NOT)
- `<<` (Bitwise left shift)
- `>>` (Bitwise right shift)
- `>>>` (Unsigned right shift)

---

## 5. Assignment Operators
- `=` (Assignment)
- `+=` (Add and assign)
- `-=` (Subtract and assign)
- `*=` (Multiply and assign)
- `/=` (Divide and assign)
- `%=` (Modulus and assign)

---

## 6. Special Operators
- `typeof`
- `delete`
- `new`
- `of`
- `in`
- `.`
- `,`
- `?:` (Ternary Operator)
- `void`
- `yield`
- `instanceof`

---


## Selection statement or Control Statements
---------------------------------------------
  
   ---> We can contol the execution of the Program using control or selection statement
   ---> We can execute certain set of statements only if certain condition become true

   `if`, `else`
   `elsefi`, `switch`

   1. Syntax of if:
   -----
     if(<condition>){
        statements `if the condition is true only then the statement will be execute`
     }
   -----

   2. Syntax of else or <if-else>
   -----
       if(<condition>){
        statements `if the condition is true only then the statement will be execute`
     }
       else{
         statements `else execute the statements when the condition is flase`
       }
   -----

   3. Syntax of elseif
   -----
          if(<condition>){
        statements `if the condition is true only then the statement will be execute`
     }
       else if (<condtion>){
         statements `else execute the statements when the first condition is flase, but second conditon is true`
       }
   -----

   4. Syntax of switch:
   -----
     switch(value){
      case "<value>":{--Statmeents--}
      case "<value>":{--Statmeents--}
      case "<value>":{--Statmeents--}
      case "<value>":{--Statmeents--}
     }

     **For example**
     --------------

       var z = "bro";

       switch(z){
           case "bro":{
               console.log("You are my bro");
               break;
           }
           case "sis":{
               console.log("Hello sis, hi there!");
               break;
           }
       
           default: {
               console.log("DO something better")
           }
       }

   -----


   ---------

   # Document Object Model(DOM)
   ----
  - It is a structure of HTML elements which are converted into objects(Nodes) and arranged all this object in **tree data structure**.
  
 ```When Browser loads an HTML page, the browser engine parse that HTML code into Bytes``

   Bytes--->Characters---->Tokens---->Objects(Nodes)
   
   HTML Elements ---------- Objects(Nodes)

### Objects(Nodes):
  --->It will link all the nodes in the sequence and all nodes will be placed in **tree data structure** and `that tree data structure we are going to call as DOM`


``Terms``
  ### 1. DOM
  ### 2. CSSOM
  ### 3. Rendering Tree

# Why DOM is created
    
    Using JS we can manipulate the HTML Document so that we can create Dynamic User Interface.

    the creation of Dynamic Interface by manipualate the DOM is called DOM Manipulation


`Questiomn`
   1. How to access Any DOM node (HTML element)
   2. How to add new HTML element
   3. How to remove existing html element
   4. How to change content or attributes of HTML element


To do all thing mention in Questions --- **Browser** is providing us pre-defined Objects and function which we call **DOM APIs**

## How to access any HTML element in JS
   
  **We can access or Refference HTML element in JS using 4 four ways**
  1. Id value
  2. class Value
  3. Tag Name
  4. name attribute

 ### in document there is a method called **querySelector()** in which we can pass anything class, id, tag-name


 ## How to create DOM Elmenets
 -----------------------------

    Element created using JavaScripts is called DOM elemeents

   `documnet.createElement('button')`

   After creating DOM Element, it should be added in the DOM to make it visible on the screen
   

   `In innerText or innerHTML only the content will be changed, but in outerHTML or outerText the whole element will be replaced`
`innerText is temporary for evenListener but textContent is temporary`
### Eventlistener:
----------------
all eventlistener start with `on<eventName>`
EventListener -- It is used to cathc the event occured on the element 
EvenetHandler -- It is JS funciton call

 --<button onclick="fn()">Click</button>--
    --> onclick is EventListener
    --> fn() is EvenetHandler


 1. onmouseenter
 2. onmouseleave



## Spread Operator
------------------
  Spread is an operator not a function
     
  `Syntax` : ...<objectName> or ...<arrayName>

  **It is used to copy properties of one onject into another object and it is used to copy elements of one array into another array**


## Rest Parameter:
   ---> It is a speacial parameter which is used to hold all the remaining arguments in array format

   `Rest Parameter should be always last parameter` it save all extra parameters in an array format

   ...<ParameterName>


## De-Structuring Of ARRAY or OBJECT
---------------------------------

  It is a technique in JS to unpack elments from the object or Array


--
     var obj = {
       username: "Rajat",
       city: "Delhi",
       id: 101,
       gender: "male",
     };
     
     var {city, gender} = obj
     
     console.log(city, gender)
--


## Clousers in JS

   ---> It is a technique to aaccess scope of outer fucntion inside the inner function 

   or

   ---> It is technique to define a function inside another function

   `Syntax`
   ---------
       

       --
         function Outer(){
          ---------------
          --------------
          --------------
             function Inner(){
              statements;
             }
             return Inner
         }
      --


## Module Pattern 

   It is a technique using which we can access to another JS function or Variables of one file into **Another file**



**IN node JS enviroment ----<Module>(pre-defined-object) ---property--->export**
  var module = {
    export:"",
  }

  module.exports = {
    attributes,
    functions,
  }



**IN node JS enviroment ----<require>(pre-defined-function) ------>"passfile-location-as-string"(relative file location)**

var ref = require('./15.js')


---**This pattern is called commonjs module patter**---


---`There's another pattern which is **es module pattern**`---
    
   To use **Es module pattern** we have two ways
  
  1. save the file with .mjs exention
  2. In our folder we create a file called `package.json` and in the file we have to create an object and in that object there must be a property `type:"module"`
   


### Named Export: export <assets/attribute>----------- import `{attribute name}` from `relative path`

### Default Export:(at the end of the attribute) export default <assest/attribute> ---- import `reference Name` from `relative path`



**this** --> this is a special keyword in JS which will point to window object

to change this reference from window object we have 3 pre-defined functions
 1. call():
        ---
             c : 100,
               var obj1 = {
         }
         var obj2 = {
             c : 100,
         }
         function fnAdd(x,y){
             console.log(x + y + this.c);
         }
         fnAdd.call(obj1,10,30)
         fnAdd.call(obj2,10,23)
         
         ---
 2. apply()
         ---
             c : 100,
               var obj1 = {
         }
         var obj2 = {
             c : 100,
         }
         function fnAdd(x,y){
             console.log(x + y + this.c);
         }
         fnAdd.apply(obj1, [10,30])
         
         ---
 3. bind()
      **bind() is used to permanently set the value of `this` for a function**
        --> It does not call the function 
        --> It returns a new function with `this` fixed.
      
      `Syntax`
         function fn(){
          console.log(this);
         }

         const newFn = fn.bind(someObject)
     
---
      const user = {
        name: "Ritika",
      };
      
      function greet() {
        console.log(this.name);
      }
      
      const greetUser = greet.bind(user);
      greetUser(); // Ritika

---

## hoisting

When we execute our JS file the Node(JS engine) creates a special environment which create and assign every varible to undefined this whole process is called **Hoisting**
--
     console.log(city);
     
     var city = "delhi"
     
     console.log(city)





## Shadowing
   
     When we assign two different values in same variable than the first value will shadowed by the second

        var city = "Delhi"
        var city = "Mumbai"
        console.log(city)

### Scops in JavaScript

   Scope refers to the accessibility
   There are 3 scopes in JS

   **1. Global Scope** : Written globaly and accesible for the whole code
   **2. Function Scope**: Written inside a funciton and only accessible for the function part not outside the funciton
   **3. Module Scope**: One files variables or Functions can be used by other files


*BlockScope --- General term for a thing  inside a block*


### Scope Statements
--------------------

 **var** --- Function Scope
 **let, const** --- Block Scope
 `NOTE` If ther are not defined in the global scope then the 

 ---

  `var`
     --- var Variables will be assigned with undefined value after hoisting

  `let & const`
     --- this variables will not be assigned with undefined value after hoisting

 ---

  ### 1. var and let:  Declaration and initialization both are possible, Re-assigning the value is possible
  ### 2. const: Only initialization is possible, re-assigning is not possible(error thrown by JS engine)

  `var` 
     --- Shadowing is possible
  `let and const` 
     --- Shadowing is not possible



# Object Oreinted Programming (OOPs)
------------------------------------

 It is one of the Programming Paradigm(style or patter of Programming)
 In OOPs everything is considered as an object


 `Syntax`
      class <ClassName>{
        properties ;<variables>
        methods;<functions>
      }


eg:
    class Product{
      productName;
      brandName;
      price;
      rating;
    }


### Constructor
    
     Constructor is a special method in class

     Constructor purpose is to initialise the Properties of the Class

  `While defining the constructor, constructor name should be constructor only and while calling constructor we should use constructor name as ClassName`



## Promises in the Javascript
-----------------------------

  Promise is a special object in the JavaScript which contains **sucess information** or **Error information**(failure Information)


  ### How to create a promise Object?
     
  ----  Promise object is created using a special constructor called Promise()
  ---- **There is a special way to add data inside the Promise Object**
  ---- We can add either **Success Data** or **Failure Data**
  ---- resolve and reject are two pre-defined fucntion in the JavaScript
  ---- And purpose of this functions is to add data inside the Promise Object
  ---- `Success Data`
        ------> The data saved or passed in resolve() method is called **Success Data**
  ---- `Failure Data`
        ------> The data we pass or saved in reject() method is called **failure data**

  ### Promise object have 3 states
      
   `1. Pending State`
        --- Empty Promise Object
   `2. Fulfilled state`
        --- Data stored in the pomise object using resolve function
       
   `3. Rejected state`
        --- Data stored in the promise object using reject function
       
