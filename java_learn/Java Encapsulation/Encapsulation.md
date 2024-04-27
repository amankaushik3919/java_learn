# Encapsulation

- The meaning of `Encapsulation`, is to make sure that "sensitive" data is hidden
from users.

- It refers to the bundling of data (attributes) and methods (behaviors) that operate 
on the data into a single unit, called a class. Encapsulation allows the internal state 
of an object to be hidden from the outside world and accessed only through well-defined 
interfaces.
To, achieve this, you must:

1. Declare class variables/attributes as `private`
2. provide public `get` and `set` methods to access and update the value of a
`private` variable

---
# Get and Set
- The only way to access a `private` variable

- `get` method returns the variable value
- `set` method sets the variable value

```java
public class Person {
	private String name; // private = restricted access

	// Getter
	public String getName() {
		return name;
	}

	// Setter
	public String setName(String newName) {
		this.name = newName;
	}
}
```

However, as the `name` variable is declared as `private`, we cannot access it from 
outside this class

```java
public class Main {
	public static void main(String[] args) {
		Person myObj = new Person();
		myObj.name = "Aman"; // error
		System.out.println(myObj.name); // error
	}
}
// Outputs Aman
```
- if `private` variable get accessed then the program throws an error

- Instead, we use the `getName()` and `setName()` methods to access and update
the  variable

# Example
```java
public class Main {
	public static void main(String[] args) {
		Person myObj = new Person();
		myObj.setName("Aman"); // Set the value of the name variable to "Aman"
		System.out.println(myObj.getName());
	}
}
// Outputs "Aman"
```

---
# Why Encapsulation?
- Better control of class attributes and methods
- Class attributes can be made `read-only` or `write-only`
- Flexible: the programmer can change one part of the code without affecting other parts
- Increased security of data
