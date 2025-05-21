# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class.

## ALGORITHM :
1.	Start the program.
2.	Define `Cylinder` class:
-	a) Private variables `radius` and `height`
-	b) `setRadius(int r)` and `setHeight(int h)` methods to set values
-	c) `getVolume()` method:
- i) Calculate and print `volume = pi * radius * radius * height`
3.	In `Main` class `main` method:
-	a) Use `Scanner` to read `radius` and `height`
-	b) Create `Cylinder` object, set values, and call `getVolume()`
4.	End









## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by:LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
class Cylinder {
    private double radius;
    private double height;

    // Setter methods
    public void setRadius(double radius) {
        this.radius = radius;
    }

    public void setHeight(double height) {
        this.height = height;
    }

    // Getter methods
    public double getRadius() {
        return radius;
    }

    public double getHeight() {
        return height;
    }

    // Method to calculate volume using 22/7 for Pi
    public double getVolume() {
        double pi = 22.0 / 7.0;  // Using 22/7 for Pi
        return pi * radius * radius * height;
    }
}

public class Main {
    public static void main(String[] args) {
        Cylinder c = new Cylinder();
        java.util.Scanner sc = new java.util.Scanner(System.in);

        // Input the radius and height
        double r = sc.nextDouble();
        double h = sc.nextDouble();

        // Set radius and height using setters
        c.setRadius(r);
        c.setHeight(h);

        // Display the volume using the method
        System.out.println("volume of Cylinder is: " + c.getVolume());
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/63a3c751-f3d3-41c8-ba2e-826821251cf5)



## RESULT:
Thus a java program to display the value of volume of cylinder get the radius and height value as input and use tightly encapsulated class was executed successfully.



