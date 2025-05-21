# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End





## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[]args){
        Scanner sc=new Scanner (System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        int max=(a>b)?(a>c?a:c):(b>c?b:c);
        System.out.println(max+" is the Greatest value");
        
    }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/1358d545-0e46-4340-9ecc-643156a1e456)




## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

