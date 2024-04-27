- Loops can execute a block of code as long as a specified condition is reached.

---
# Java While Loop
- The `while` loop loops through a block of code as long as a specified condition is `true`.
```java
while (condition) {
  // code block to be executed
}
```
# Example
```java
int i = 0;
while (i < 5) {
  System.out.println(i);
  i++;
}
```

---
# The Do/While Loop
It is a variant of the `while` loop.
This loop will execute the code block once, before checking if the condition is true, 
then it will repeat the loop as the condition is true.

```java
do {
  // code block to be executed
}
while (condition);
```

# Example
```java
int i = 0;
do {
  System.out.println(i);
  i++;
}
while (i < 5);
```
