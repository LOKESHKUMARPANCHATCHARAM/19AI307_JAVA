# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by:LOKESH KUMAR P 
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:
```
// Parent class
class Bird {
    void display() {
        System.out.println("I am a Bird");
    }
}

// Child class
class Parrot extends Bird {
    // Overriding the display() method
    @Override
    void display() {
        System.out.println("I am a Parrot");
    }

    // Method that calls both overridden and overridden versions
    void print() {
        this.display();     // Calls the overridden method in Parrot
        super.display();    // Calls the original method in Bird using super
    }
}

// Main class to run the program
public class Main {
    public static void main(String[] args) {
        // Creating an instance of the child class
        Parrot p = new Parrot();

        // Calling the print method
        p.print();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/301096d0-eeb2-4fbf-96fd-5c912009d46b)



## RESULT:
Thus the java program for constructor chaining was executed successfully.




