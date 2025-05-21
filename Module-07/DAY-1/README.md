# Ex.No:7(A)           EXCEPTION HANDLING-RUN TIME EXCEPTION
## AIM:
  To Develop a Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism.

## ALGORITHM :
1.  Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `Example1`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read integers `a` and `b` from user input
-	b) Calculate `res = a / b` and print "Result: " followed by `res`
5.	Use `catch` block to handle `ArithmeticException`:
-	a) If division by zero occurs, print "You Shouldn't divide a number by zero"
6.	End







## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Run Time Exception using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int index=sc.nextInt();
         
        try  
        {  
        int arr[]= {1,3,5,7};
        System.out.println(arr[index]);
          
        } 
        catch(ArrayIndexOutOfBoundsException e){
            System.out.println("Array value should be less than 4");
        }
            
       
        
          
    }
}

```






## OUTPUT:
![image](https://github.com/user-attachments/assets/57d92d5a-3170-4ee1-828c-8318a19462a7)



## RESULT:
Thus the Java Program for handling Arithmetic Exception (division by zero exception) using Exception Handling Mechanism was executed successfully.

