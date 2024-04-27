
# Example Assignment in Java:
```java

type variableName = value
```

# Var to store text:
```java
String name = "Jhon";
System.out.println(name);
```

# To create a variable that should store a number:
```java
int myNum = 15;
System.out.println(myNum);
```
# You can also declare a variable without assigning the value, and assign the value later:
```java
int myNum;
myNum = 15;
System.out.println(myNum);
```
# Note that if you assign a new value to an existing variable, it will overwrite the previous value:
```java
int myNum = 15;
myNum = 20; //myNu, is now 20
System.out.println(myNum);
```

----
# Final Variables

if you don't want others (or yourself) to overwrite existing values, use the final keyword (this will declare the variable as "final" or "constant", which means unchangeable and read-only):
```java
final int myNum = 15;
myNum = 20; // will genrate and error: cannot assign a value to a final variable
```

---
# Other Types
```java
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";
```


