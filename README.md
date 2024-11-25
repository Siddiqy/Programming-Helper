# Programming-Helper

## Variables

**Java**
```
String
int
float
char
boolean
```

**JavaScript**
```
var
let
const
```

**Python**
```
Text Type:	str
Numeric Types:	int, float, complex
Sequence Types:	list, tuple, range
Mapping Type:	dict
Set Types:	set, frozenset
Boolean Type:	bool
Binary Types:	bytes, bytearray, memoryview
None Type:	NoneType
```

## Comments

**Java**
```
// This is a comment
/* The code below will print the words Hello World
to the screen, and it is amazing */
```

**JavaScript**
```
// This is a comment
/*
The code below will change
the heading with id = "myH"
*/
```

**Python**
```
#This is a comment
"""
This is a comment
written in
more than just one line
"""
```

## User Input

**Java**
```
Scanner myObj = new Scanner(System.in);  // Create a Scanner object

String userName = myObj.nextLine();  // Read user input
 // Output user input
```

**JavaScript**
```
const userInput = prompt("Please enter your name:");
```

**Python**
```
input('Enter your name:')
```

## Output

**Java**
```
System.out.println("Hello World!");
```

**JavaScript**
```
console.log("Hello World!");
```

**Python**
```
print('Hello World!')
```

## Syntax

**Java**
```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

## If ... Else Statements

**Java**
```
if (condition1) {
  //block of code to be executed if condition1 is true
} else if (condition2) {
  //block of code to be executed if the condition1 is false and condition2 is true
} else {
  //block of code to be executed if the condition1 is false and condition2 is false
}

variable = (condition) ? expressionTrue :  expressionFalse;   //Short Hand if...else
```

**JavaScript**
```
if (condition1) {
  //block of code to be executed if condition1 is true
} else if (condition2) {
  //block of code to be executed if the condition1 is false and condition2 is true
} else {
  //block of code to be executed if the condition1 is false and condition2 is false
}
```

**Python**
```
if condition1:
  //block of code to be executed if condition1
elif a == b:
  //block of code to be executed if the condition1 is false and condition2 is true
else:
  //block of code to be executed if the condition1 is false and condition2 is false
```

## Switch Statements

**Java**
```
switch(expression) {
  case x:
    //code block
    break;
  case y:
    //code block
    break;
  default:
    //code block
}
```

**JavaScript**
```
switch(expression) {
  case x:
    //code block
    break;
  case y:
    //code block
    break;
  default:
    //code block
}
```

## While Loop

**Java**
```
int i = 0;
while (i < 5) {
  System.out.println(i);
  i++;
}
```

**JavaScript**
```
while (i < 10) {
  text += "The number is " + i;
  i++;
}
```

## For Loop

**Java**
```
for (int i = 0; i < 5; i++) {
  System.out.println(i);
}
```

**JavaScript**
```
for (let i = 0; i < 10; i++) {
  consol.log(i)
}
```

**Python**
```
for x in range(6):
  print(x)

for x in range(2, 6):
  print(x)

for x in range(2, 30, 3):
  print(x)
```

## Arrays

**Java**
```
String cars[] = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars[0]);
```

**JavaScript**
```
const cars = ["Saab", "Volvo", "BMW"];
let car = cars[0];
```

**Python**
```
cars = ["Ford", "Volvo", "BMW"]
x = cars[0]
```
