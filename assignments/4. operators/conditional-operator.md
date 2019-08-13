## If Statement

1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

⛑ Rule
\_ [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
⚡️ Operations

```js
var num1 = prompt('Enter First Value');
var num2 = prompt('Enter Second Value');
_ [ ] Add
alert(num1+num2)
_ [ ] Sub
if(num2>num1) alert('Number Two is larger then Number one');
else alert(num1-num2)
_ [ ] Mul
alert(num1\*num2) // plz ignore '/' Came from Prettier Extension

- [ ] Div
      //if(num2>num1) alert('Number Two is larger then Number one');
      //else alert(num1/num2)
```

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`

```js
var firstName = "John";
var status = "single";
// Your code goes here
if (status == "single") console.log(`John is single`);
else console.log(`John is married`);
```

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.

```js
//var number1 = prompt('Enter First Value');
//var number2 = prompt('Enter Second Value');
if (number1 > 2) alert("Number one is Greater than Number 2");
else alert("Number 2 is Greater than Number 1");
```

4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.
   //

```js
var countOne = promt("Enter a Count One Value");
var countTwo = promt("Enter a Count Two Value");
var countThree = promt("Enter a Count Three Value");
var product = countOne * countTwo * countThree;
alert("The Product of Three no is ", Product);
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.

- [ ] ONE, if `number` is equal to 1.
- [ ] TWO, if `number` is equal to 2.
- [ ] THREE, if `number` is equal to 3.
- [ ] FOUR, if `number` is equal to 4.
- [ ] FIVE, if `number` is equal to 5.
- [ ] SIX, if `number` is equal to 6.
- [ ] SEVEN, if `number` is equal to 7.
- [ ] EIGHT, if `number` is equal to 8.
- [ ] NINE, if `number` is equal to 9.
- [ ] PLEASE TRY AGAIN, if is none of the above.

```js
var number = prompt("Enter a Number Value");
switch (number) {
  case 1:
    alert("Number is Equal to 1.");
    break;
  case 2:
    alert("Number is Equal to 2.");
    break;
  case 3:
    alert("Number is Equal to 3.");
    break;
  case 4:
    alert("Number is Equal to 4.");
    break;
  case 5:
    alert("Number is Equal to 5.");
    break;
  case 6:
    alert("Number is Equal to 6.");
    break;
  case 7:
    alert("Number is Equal to 7.");
    break;
  case 8:
    alert("Number is Equal to 8.");
    break;
  case 9:
    alert("Number is Equal to 9.");
    break;
  default:
    alert("PLEASE TRY AGAIN");
}
```

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.

- [ ] `AA` if `marks` is greater than 90.
- [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
- [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
- [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
- [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
- [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
- [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
- [ ] `FF` if `marks` is less than or equal to 30

```js
var marks = prompt("Enter A Your Marks");
switch (marks) {
  case marks > 90:
    alert(marks + " is greater than 90.");
    break;
  case marks > 80:
    alert(marks + " is greater than 80 and less than or equal to 90");
    break;
  case marks > 70:
    alert(marks + " is greater than 70 and less than or equal to 80");
    break;
  case marks > 60:
    alert(marks + " is greater than 60 and less than or equal to 70");
    break;
  case marks > 50:
    alert(marks + " is greater than 50 and less than or equal to 60");
    break;
  case marks > 40:
    alert(marks + " is greater than 40 and less than or equal to 50");
    break;
  case marks > 30:
    alert(marks + " is greater than 30 and less than or equal to 40");
    break;
  default:
    alert(marks + " is less than or equal to 30");
}
```
