
To declare more than one variable of the `same type`, you can use a comma-separated list:

```java
// instead of writing:
int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z);

// Can simply be write:
int x = 5, y = 6, z = 50;
System.out.println(x + y + z);
```
# One Value to Multiple Variables
You can also assign the `same value` to multiple variable in one line:
```java
int x, y, z;
x = y = z = 50;
System.out.println(x + y + z);
```
