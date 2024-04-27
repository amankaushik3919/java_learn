# It is used to Store Text

It Contains Collection of Characters surrounded by double quotes.

```java
String greeting = "Hello";
```

---
# String Length
- By Using `length()` method, the length of the string.

```java
String txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
System.out.println("The Length of the txt string is: " + txt.length());
```

---
# More String Methods
- There r many string methods available, for example `toUpperCase()` and `toLowerCase()`.
```java
String txt = "Hello World";
System.out.println(txt.toUpperCase());		// Outputs "HELLO WORLD"
System.out.println(txt.toLowerCase());		// Outputs "hello world"
```

---
# Finding a Character in a String
- The `indexof()` method returs the index (the position) of the first occurrence of a specified text
in a string (including whitespace).
```java
String txt = "Please locate where 'locate' occurs!";
System.out.println(txt.indexOf("locate")); // Outputs 7
```
