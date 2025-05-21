# Ex.No:5(C)    GETTER AND SETTER METHOD

## AIM:
To Create a java program to print the sum of two number using getter and setter method.

## ALGORITHM :
1.  Start the Program
2.	Define class `Employee`:
-	a) Private variables `n1` and `n2`
-	b) Method `setsum(int n1, int n2)` to set values of `n1` and `n2`
-	c) Method `getsum()` to calculate and print `sum = n1 + n2`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integers `n1` and `n2`
-	b) Create ` Employee ` object, set values, and call `getsum()`
4.	End


## PROGRAM:
 ```
/*
Program to implement a Getter and Setter using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
class Person {
    private int age;

    // Setter method to set age
    public void setAge(int age) {
        this.age = age;
    }

    // Getter method to get age
    public int getAge() {
        return age;
    }
}


public class Main {
    public static void main(String[] args) {
        // Create an object of Person
        Person person = new Person();

        

        // Read the age value
    
        int age = 24;

        // Set the age using setter method
        person.setAge(age);

        // Print the age using getter method
        System.out.println("My age is " + person.getAge());

    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/820c135d-4483-48de-a715-41f81b722282)



## RESULT:
Thus the java program to print the sum of two number using getter and setter method was executed successfully.






