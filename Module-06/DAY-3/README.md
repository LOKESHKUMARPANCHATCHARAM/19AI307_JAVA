# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.


## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `child` and call `show()` and `print()` on it
-	b) Create `Child2` object `chi` and call `show()` and `display()` on it
6.	End




## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
// Parent class
class Number {
    int num1 = 10;
    int num2 = 5;
    int result;
    
    void displayResult(String operation) {
        System.out.println(operation + " of 2 values " + result);
    }
}

// Addition class inheriting from Number
class Addition extends Number {
    void add() {
        result = num1 + num2;
        displayResult("Addition");
    }
}

// Subtraction class inheriting from Number
class Subtraction extends Number {
    void sub() {
        result = num1 - num2;
        displayResult("Subtraction");
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        // Create object for Addition
        Addition addition = new Addition();
        addition.add();  // Outputs: Addition of 2 values 15

        // Create object for Subtraction
        Subtraction subtraction = new Subtraction();
        subtraction.sub();  // Outputs: Subtraction of 2 values 5
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/8fac61dd-f0e8-40f5-adb9-f815ee2afc99)



## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






