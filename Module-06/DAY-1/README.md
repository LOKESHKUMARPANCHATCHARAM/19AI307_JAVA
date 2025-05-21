# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program to implement Method Local Inner Class.

## ALGORITHM :
1.  Start the Program.
2.	Define outer class `name`:
-	a) Declare `String name` and initialize it to "Johnson"
-	b) Define inner class `inner`:
- i) Define method `display()` that prints "Name given in Outer Class is " followed by `name`
3.	In the `main` method of `name` class:
-	a) Create an instance `obj` of the `name` class
-	b) Create an instance `obj2` of the inner class `inner` using `obj`
-	c) Call `display()` on `obj2` to print the outer class name
4.	End






## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
class Login {
    // Private members of the outer class
    private String userName;
    private String password;

    // Constructor to initialize userName and password
    public Login(String userName, String password) {
        this.userName = userName;
        this.password = password;
    }

    // Regular inner class
    class ValidateCredentials {
        // Public method to validate and display credentials
        public void validate() {
            // Accessing outer class private members
            System.out.println(userName + " " + password);
        }
    }
}

public class Main {
    public static void main(String[] args) {
        // Creating object of outer class and initializing credentials
        Login login = new Login("Saveetha", "12345");

        // Creating object of inner class using outer class object
        Login.ValidateCredentials validator = login.new ValidateCredentials();

        // Calling the validate method
        validator.validate();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/e2dd2448-a11b-41d0-b554-0cf0d2a61781)



## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

