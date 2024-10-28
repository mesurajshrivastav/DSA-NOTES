functions (or methods) only support pass-by-value, meaning that when a variable is passed to a method, a copy of the variable’s value is passed, not a reference to the original variable. This can be a bit confusing because Java behaves differently for primitive data types and objects.

## Pass-by-Value for Primitive Data Types

When you pass a primitive data type (like int, double, boolean) to a method, Java passes a copy of the value. This means that any changes made to the parameter inside the method don’t affect the original variable outside the method.

```java
public class PassByValueExample {
    public static void main(String[] args) {
        int number = 10;
        modifyPrimitive(number);
        System.out.println("After method call, number: " + number); // Output: 10
    }

    public static void modifyPrimitive(int num) {
        num = 20; // Only modifies the local copy
    }
}

```

# Pass-by-Value for Objects (Reference Types)

When you pass an object (like an array, String, or custom object) to a method, Java still passes a copy of the reference to the object, not the actual object itself. This is sometimes misunderstood as "pass-by-reference," but Java doesn’t use pass-by-reference. Instead:

- The method receives a copy of the reference, pointing to the same object in memory.
- You can modify the object’s fields or elements through this reference, but reassigning the reference itself won’t affect the original reference.

```java
public class PassByValueObjectExample {
    public static void main(String[] args) {
        int[] numbers = {1, 2, 3};
        modifyArray(numbers);
        System.out.println("After method call, numbers[0]: " + numbers[0]); // Output: 10
    }

    public static void modifyArray(int[] arr) {
        arr[0] = 10; // Modifies the first element of the array
    }
}

```
