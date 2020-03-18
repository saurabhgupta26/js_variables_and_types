1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
#### name is a variable name.
2. Find the error if any
```js
  var product cost = 3.45;
```
#### var productCost = 3.45;

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"   Right
  'Hello World"   Wrong
  "Hello World'	  Wrong
  'Hello World'   Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;			valid
var 1girl;			invalid
var woman3;			valid
var -girl;			invalid
var blackDog; 			valid
var 42;				invalid
var $42;			valid
var userName;			valid
var x, y, z;			valid
var x = 5, y = 6, z = 7;	valid
var x = 5 + 10 + 2;		valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
#### var num1 = amount - 80;

// Define a new variable and store the value that is 200 more then the value of amount.
#### var num2 = amount + 200;
// Define a new variable and store the value that is 4 times the value of amount.
#### var var num3 = amount *4 ; 

// Define a new variable and store the reminder when the value of amount is  divided by 21.
####  var num4 = amount % 21;
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark

#### var age = johnAge>markAge ? (`John`) : (`Mark`);
#### alert(age);
// Check who is younger
#### var age = johnAge>markAge ? (`John`) : (`Mark`);
#### alert(age);
// Check if their age is equal
#### var age = (johnAge == markAge) ? (`true`) : (`false`);
#### alert(age);
// Create a new variable and assign the age of john to new variable.
#### var johnNewAge = johnAge;
// Check if john is equal to or greater then mark.
#### var age = (johnAge >= markAge)? `John's age is equal to or more than Mark` : `Mark is elder`;
#### alert (age);
// Check if john is less then or equal to mark.
#### let age = (johnAge <= markAge) ? `mark is young`:`john is elder`;
#### alert(age);
// Calculate the average age of john and mark and assign to a new variable.
#### var avgAge = (johnAge + markAge)/2;
#### alert(avgAge);
```