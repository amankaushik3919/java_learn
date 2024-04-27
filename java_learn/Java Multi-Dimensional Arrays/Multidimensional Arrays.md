- it is an array of arrays

- it is useful when tabular data wanted to be stored like a table with 
rows and columns.

# Creating Multidimensional Array
```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
```

---
# Access Elements

```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
System.out.println(myNumbers[1][2]); // Outputs 7
```

---
# Change Elements Values

```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
myNumbers[1][2] = 9;
System.out.println(myNumbers[1][2]); // Outputs 9 instead of 7;
```
---
# Loop through a multidimensional array
```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
for (int i = 0; i < myNumbers.length; ++i) {
	for (int j=0; j < myNumbers[i].length; ++j) {
		System.out.println(myNumbers[i][j]);
	}
}
```

# Using for each loop
```java
int[][] myNumbers = { {1, 2, 3, 4}, {5, 6, 7} };
for (int[] row : myNumbers) {
	for (int i : row) {
		System.out.println(i);
	}
}
```
