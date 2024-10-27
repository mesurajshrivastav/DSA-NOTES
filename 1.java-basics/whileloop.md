## while Loop

the while loop is used to execute a block of code repeatedly as long as a specified condition is true. Unlike the for loop, which is typically used when you know the exact number of iterations, the while loop is more useful when the number of iterations isn’t fixed.

**Syntax of while Loop**

```java
while (condition) {
   // Code to be repeated
}

```

**Components of a while Loop**

- Condition: The loop checks this condition before each iteration. If the condition is true, the loop runs. If it's false, the loop stops.

- Loop Body: Contains the code that executes repeatedly as long as the condition is true.

**Example of a while Loop**

```java
public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 1; // Initialization

        while (i <= 5) { // Condition
            System.out.println("Number: " + i);
            i++; // Update (increment i by 1)
        }
    }
}

```

**Infinite while Loop**

```java
while (true) {
    // Code that repeats indefinitely
}

```
