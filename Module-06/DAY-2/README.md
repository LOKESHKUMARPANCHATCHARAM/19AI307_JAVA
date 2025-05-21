# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by:LOKESH KUMAR P
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

// Base class
class Shapes {
    void print_Shape() {
        System.out.println("Shapes Class");
    }
}

// Intermediate class
class Circle extends Shapes {
    double radius;

    void get() {
        Scanner sc = new Scanner(System.in);
        radius = sc.nextDouble();
    }
}

// Derived class
class Area extends Circle {
    void calc() {
        double area = 3.14 * radius * radius;
        System.out.println("Area of Circle is " + area);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Area obj = new Area();
        obj.get();           // Input radius
        obj.print_Shape();   // From Shapes class
        obj.calc();          // Calculate area
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/abe7e5a2-7d89-4ed9-8923-830c9e958fb3)



## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





