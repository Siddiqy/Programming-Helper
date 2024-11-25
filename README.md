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
if(condition1) {
  
}else if (condition2) {
  
}else {
  
}

variable = (condition) ? expressionTrue :  expressionFalse;   //Short Hand if...else
```

**JavaScript**
```
if(condition1) {
  
}else if (condition2) {
  
}else {
  
}
```

**Python**
```
if condition1:

elif a == b:

else:

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
for x in range(6):     #Started from 0 and stopped at 5 and increment the sequence with 1
  print(x)

for x in range(2, 6):    #Started from 2 and stopped at 5 and increment the sequence with 1
  print(x)

for x in range(1, 30, 3):    #Started from 1 and stopped at 30 and increment the sequence with 3
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

## Class

**Java**
```
public class Main {
  int x = 5;

  public static void main(String[] args) {
    Main myObj = new Main();
    System.out.println(myObj.x);
  }
}
```

**JavaScript**
```
class Car {
  constructor(name, year) {
    this.name = name;
    this.year = year;
  }
}

const myCar1 = new Car("Ford", 2014);
const myCar2 = new Car("Audi", 2019);
```

**Python**
```
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

  def myfunc(self):
    print("Hello my name is " + self.name)

p1 = Person("John", 36)
p1.myfunc()
```

## Methods 

**Java**
```
public class Main {
  static void myMethod() {
    System.out.println("Hello World!");
  }

  public static void main(String[] args) {
    myMethod();
  }
}
```

## Function 

**JavaScript**
```
function myFunction(parameter1, parameter2) {
  return parameter1 * parameter2;
}
```

**Python**
```
def my_function(name):
  print(" Hello " + name)

my_function("Tobias")
```

## JavaScript Objects 

function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
}

const myFather = new Person("John", "Doe", 50, "blue");

const person = {
  firstName:"John",
  lastName:"Doe",
  age:50, 
  eyeColor:"blue"
}

const x = person;      // Create a copy

x.age = 10;     // Change Age in both

person.lastName

person["lastName"]

## Python Dictionaries

thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964
}

print(thisdict)             #Print Dictionaries

x = thisdict["model"]       #Accessing Items

thisdict["year"] = 2018     #Change Values

thisdict["color"] = "red"   #Adding Items

thisdict.pop("model")       #Removing Items
