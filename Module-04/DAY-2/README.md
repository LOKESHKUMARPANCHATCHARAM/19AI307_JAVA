# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;

class Vehicle {
    int vehicleId;
    String vehicleName;

    Vehicle(int vehicleId, String vehicleName) {
        this.vehicleId = vehicleId;
        this.vehicleName = vehicleName;
    }

    void display() {
        System.out.print("Vehicle Id is " + vehicleId + " ");
        System.out.print("Vehicle Name is " + vehicleName + " ");
    }
}

class Car extends Vehicle {
    String model;

    Car(int vehicleId, String vehicleName, String model) {
        super(vehicleId, vehicleName);
        this.model = model;
    }

    void displayDetails() {
        super.display();
        System.out.print("Model is " + model);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        
        int vehicleId = sc.nextInt();
        sc.nextLine(); // consume the leftover newline
        
        String vehicleName = sc.nextLine();
        String model = sc.nextLine();

        
        Car car = new Car(vehicleId, vehicleName, model);
        car.displayDetails();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/f357ed23-bb64-4270-a2bd-50783b62786a)



## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

