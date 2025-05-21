# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when NumberFormat Exception occur in try block and handled in catch block


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `HelloWorld`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read a string `str` from user input
-	b) Convert `str` to an integer using `Integer.parseInt()` and print the result
5.	Use `catch` block to handle `NumberFormatException`:
-	a) If the string can't be converted to an integer, print the exception message
6.	Use `finally` block to:
-	a) Print "Finally block executed"
7.	After the `try-catch-finally` block, print "Outside try-catch-finally clause"
8.	End



## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by:LOKESH KUMAR P 
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class TryCatchFinallyDemo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int result = 0;

        System.out.print("");
        int input = scanner.nextInt();

        try {
            result = 100 / input;
            System.out.println("Valid Statement :" + result);
        } catch (ArithmeticException e) {
            System.out.println("Exception: " + e);
        } finally {
            System.out.println("Finally block executed");
        }

        System.out.println("Outside try-catch-finally clause");

        scanner.close();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/0329559e-d4d9-4631-a431-de417bafc46f)



## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when NumberFormatException occur in try block and handled in catch block was executed successfully.



