### _Syntax:_  
#### Variables:  
Variables are seperated into types that are in different lengths, because when you compile the code the computer has to read it in bytecode.
They are:
byte - 8-bit integer  
short - 16-bit integer  
int - 32-bit integer  
long - 64-bit integer  
float - 32-bit floating point number  
double - 64-bit floating point number  
boolean - true or false  
char - a single character, like 'A' or '$'  
#### Operators:
There are many operators used such as +,-,*,/,%,>,<,= that can be used in boolean expressions.

#### Loops:

How to create  a for loop using continue.
```
for (int i = 1; i <= 20; i++) {
    if (i % 2 == 0) continue;
    System.out.println(i);
}
```
Continue is unique for java. It allows the programmer to not worry about extra calculations that the programmer else has to do themeselve.