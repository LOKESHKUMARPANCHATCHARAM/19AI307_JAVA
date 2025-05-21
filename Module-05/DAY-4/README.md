# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program to find factorial of number using class and object concepts and apply the has-a relationship.
 
## ALGORITHM :
1.	Start the Program
2.	Define class `A`:
-	a) Declare integer `n` and initialize `fact` to 1
-	b) Define method `factorial(int n)`:
-	i) Set `this.n = n`
-	ii) Use a loop from 1 to `n` to calculate `fact = fact * i`
-	iii) Print "Factorial is:" followed by `fact`
3.	In `main` class `main` method:
-	a) Use `Scanner` to read integer `n`
-	b) Create an `A` object and call `factorial(n)`
4.	End

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:21222224054  
*/
```

## Sourcecode.java:
```
class Animal {
    // eat method in Animal class
    public void eat() {
        System.out.println("I can eat");
    }
}
class Dog extends Animal {
    // eat method in Dog class
    public void eat() {
        System.out.println("I eat dog food");
    }

    // bark method in Dog class
    public void bark() {
        System.out.println("I can bark");
    }
}
public class Main {
    public static void main(String[] args) {
        // Create object of Dog
        Dog dog = new Dog();
        Animal animal = new Animal();
        animal.eat();

        // Call methods
        dog.eat();   // Dog's eat method
        dog.bark();  // Dog's bark method

        // Also call Animal's eat method using Animal reference
          // Animal's eat method
    }
}


```






## OUTPUT:
![image](https://github.com/user-attachments/assets/d4f7d733-30bb-46f4-a7ff-cf7736d6211b)



## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
