<h1 align="center"> Javascript Notes </h1>

## Commenting in Javascript

### Inline comment
```javascript
//You can comment in javascript using doube slash
```

### Multiline comment
```js
/* 
You can use 
slash asterisk
to make multiline
comments
*/
```

---
## Variables
There are 3 types of variables,

You can use ``var``, ``let``, ``const``
**Note-** Variables in javascript are case sensitive

**Examples,**

```js
var MyVariable = "Hello World"; // This variable is mutable
```

```js
let MyVariable = "Hello World"; // This variable used within a scope 
```

```js
const pi = 3.14; // Variable which is immutable
```




## Data Types

Examples of each Data Type are given below

|Data Type|Explanation|Example|
|---|---|---|
|Undefined|A variable set to nothing|[Click here]()|
|None|A specific data type which is set to nothing|[Click here]()|
|Boolean| True or False|[Click here]()|
|String|Text|[Click here]()|
|Symbol||[Click here]()|
|Number||[Click here]()|
|Object||[Click here]()|

### Undefined

```js
var MyVariable;
```

### Null

```js
var MyVariable = "";
```

### Boolean

```js
var XVariable = True;
var YVariable = False;
```

### String

```js
var MyVariable = "I am a string";
```

### Number

---

## Operators

### Assignment 

```js
var x = 6;
var y = 2;
```

### Adding

```js
var x = 3;
var y = 4;

var z = x + y;
```

### Multiplying

```js
var x = 5;
var y = 2;

var z = x * y;
```


### Arithmetic Operators
|Operator|Description|
|---|---|
|+|Addition|
|-|Subtraction|
|*|Multiplication|
|**|Exponent|
|/|Division|
|%|Modulas (Gives remainder)|
|++|Increment|
|--|Decrement|

### Assignment Operators

|Operator|Example|Same as|
|---|---|---|
|=|`x = y`|`x = y`|
|+=|`x += y`|`x = x + y`|
|-=|`x -= y`|`x = x - y`|
|*=|`x *= y`|`x = x * y`|
|/=|`x /= y`|`x = x / y`|
|%=|`x %= y`|`x = x % y`|
|**=|`x **= y`|`x = x ** y`|

## Escape sequencs

|Code|Output|
|---|---|
|`\'`|Single Quote|
|`\"`|Double Quote|
|`\\`|Backslash|
|`\n`|New Line|
|`\r`|Carriage Return|
|`\t`|Tab|
|`\b`|Backspace|
|`\f`|Form Feed|


## Arrays

Arrays allow you to store several pieces of data in one place

**Example-**
```js
var MyArray = ["Hello",23];
```

Accessing data in array,

```js
var MyArray = ["Hello",23];

var SecondElement = MyArray[1]; // Note start counting from 0

```

Nested Array,
```js
var NestedArray = [["Hi",0],["ok",1]];
```

Accessing nested array,
```js
var NestedArray = [["Hi",0],["ok",1]];

var FFA = NestedArray[0][0]; // Returns First element of the first array, That is "hi"
```

### Array Manipulation

|Function|Descreption|Example|
|--|--|--|
|.push()|Appends data to the end of an array|``MyArray.push("Hi");``|
|.unshift()|Appends data to the start of an array|`MyArray.unshft("Hey");`|
|.pop()|Removes data from the end of an array|`MyArray.pop();`|
|.shift()|Removes data from the start of an array|`MyArray.shiift();`|



## Functions

Block of code which is reusable.

```js
function MyFunction(a,b) {
  console.log(a-b); // a and b are parameters of the function
  }
 
MyFunction();
```

## if else and else if statements

```js
var x = "Hello";

if (x == "Hello") {
  console.log("Hello world");
}

else if (x == "world"){
  console.log("World Hello");
}

else {
  console.log("Hi");
}
```

## Switch case

```js
function CaseInSwitch(x) {
	var answer = "";
	
	switch(x){
		case 1:
			answer = "Alpha";
			break;
		
		case 2:
			answer = "Beta";
			break;
		
		case 3:
			answer = "Gamma";
			break;
		
		case 4:
			answer = "Delta";
			break;
	}

	return answer;
}
```
