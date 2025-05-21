# Ex.No:7(E)  POLYMORPHISM

## AIM:
To implement method overloading in Java to calculate the sum of two and three numbers demonstrating compile-time polymorphism
## ALGORITHM :
1.	Start the program.
2.	Create a class named SumExample.
3.	Inside the class, define:
     a.	A method sum(int a, int b) to calculate the sum of two numbers.
     b.	An overloaded method sum(int a, int b, int c) to calculate the sum of three numbers.
4.	In the main() method:
      a.	Create an object of the SumExample class.
      b.	Call both versions of the sum() method with appropriate arguments.
      c.	Print the results.
5.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Method Overloading in Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main 
{
  
  static void checkAge(double age) throws ArithmeticException {
    if (age < 18) {
      throw new ArithmeticException("Person is not eligible to vote");
    }
    else {
      System.out.println("Person is eligible to vote!!");
    }
  }

  public static void main(String[] args) 
  { 
      Scanner sc=new Scanner(System.in);
      double n=sc.nextDouble();
      try
      {
      checkAge(n);
      }
      catch(Exception e)
      {
          System.out.println(e);
      }
     // Set age to 15 (which is below 18...)
  }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/83378be5-e60e-41a2-a555-a1526bd58d6e)



## RESULT:

Thus the  java program successfully demonstrates method overloading, showing compile-time polymorphism by calculating the sum of two and three numbers using methods with the same name but different parameter lists..


