# for Loop

- A for loop is a control structure used to repeat a block of code a specific number of times.
- It is particularly useful when you know in advance how many times you need to execute a statement or block of statements.

```java
for (initialization; condition; update) {
   // Code to be repeated
}
```

**Components of a for Loop**

- Initialization: This is where you initialize your loop control variable. It runs only once, at the beginning of the loop.

- Condition: Before each iteration, the loop checks this condition. If it's true, the loop executes; if it's false, the loop stops.

- Update: This part updates the loop control variable after each iteration, usually by incrementing or decrementing it.

**simple for loop**

```java
public class ForLoopExample {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {  // i starts at 1 and increases until it reaches 5
            System.out.println("Number: " + i);
        }
    }
}

```

**Example of Looping Through an Array**

```java
public class ArrayLoopExample {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int i = 0; i < numbers.length; i++) {
            System.out.println("Element at index " + i + ": " + numbers[i]);
        }
    }
}

```

### Enhanced for Loop (for-each)

Java also has an enhanced for loop, called a for-each loop, which is useful when you don't need to know the index and just want to access each element:

```java
public class ForEachExample {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int num : numbers) {
            System.out.println("Number: " + num);
        }
    }
}

```
