- It is used to store multiple values in a single variable, instead of
declaring separate variables for each value.

# Declaration
```java
Srtring[] cars;
```
# placing values in the array
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
```

# Creating an array of integers
```java
int[] myNum = {10, 20, 30, 40};
```

# Access the Elements of an Array
- Can access an array element by referring to the index number.
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars[0]);
// Outputs Volvo
```

# Change an Array Element
```java
cars[0] = "Opel";
```

```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Opel";
System.out.println(cars[0]);
// Now outputs Opel instead of Volvo
```

# Array Length
```java
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars.length);
// Outputs 4
```
