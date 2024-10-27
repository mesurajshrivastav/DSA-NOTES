## Array

An array is a collection of elements of the same data type stored in a contiguous memory location. Arrays are useful for storing a fixed number of elements, and they are indexed starting from 0.

**Characteristics:**

- Fixed Size: Once defined, the size of an array cannot be changed.
- Index-Based: You can access elements using an index, starting from 0 up to -array length - 1.
- Single Data Type: All elements in an array must be of the same type.

### syntax of array

```java
dataType[] arrayName = new dataType[size];
```

### Example

```java
int[] numbers = new int[5]; // Declares an array of 5 integers
numbers[0] = 10;
numbers[1] = 20;
numbers[2] = 30;
numbers[3] = 40;
numbers[4] = 50;

System.out.println(numbers[2]); // Output: 30

```

### directly initialize

```java
int[] numbers = {10, 20, 30, 40, 50};

```

## String

A string is a sequence of characters, represented by the String class in Java. Unlike arrays, strings in Java are immutable, meaning once created, they cannot be changed.

**Characteristics:**

- Immutable: Strings cannot be modified after creation.
- Convenient Methods: Java provides many useful methods for string manipulation, such as finding length, concatenating, and comparing strings.
- Object of Class: Strings are objects in Java, even though they are often used like primitives.

### Syntax for Declaring a String

```java
String str = "Hello, World!";

```

### Example

```java
String greeting = "Hello";
String name = "Alice";

// Concatenate strings
String welcomeMessage = greeting + ", " + name + "!";
System.out.println(welcomeMessage); // Output: Hello, Alice!


```

**Common String Operations:**

- Length: str.length()
- Concatenate: str1 + str2 or str1.concat(str2)
- Compare: str1.equals(str2)
- Substring: str.substring(start, end)
