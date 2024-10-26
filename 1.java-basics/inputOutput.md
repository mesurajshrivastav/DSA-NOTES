```
import java.util.Scanner;

public class InputOutputExample {
    public static void main(String [] args){
        Scanner sc = new Scanner(System.in);

        //input
        System.out.println("Enter you name: ");
        String name = sc.nextLine(); // for reading the line

        System.out.println("Enter you age: ");
        int age = sc.nextInt(); // for integer

        System.out.println("Enter you height in cm: ");
        double height = sc.nextDouble(); // for decimal value

        //output
        System.out.println("you are "+name);
        System.out.println("your age is "+age);
        System.out.println("your height is "+height);

        sc.close();
    }
}
```
