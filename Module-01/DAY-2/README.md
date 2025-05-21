# Ex.No:1(B) VARIABLES AND OPERATOR

## AIM:
To write a Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true. [Class name is ‘Demo’]

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Define a class named 'Demo'
4.	Implement the main method
5.	Create a new instance of the 'Scanner' class named 'sc' to read user input
6.	Read an integer 'a' from the user using the 'nextInt' method of 'sc'
7.	Read another integer 'b' from the user using the 'nextInt' method of 'sc'
8.	Check if 'a' is less than 50 or if 'a' is less than 'b'
a)	If the condition is true, print "true" using the 'print' method of 'System.out'
b)	If the condition is false, print "false" using the 'print' method of 'System.out'
9.	End





## PROGRAM:
 ```
/*
Program to implement a variable and operators using Java
Developed by: LOKESH KUMAR P
RegisterNumber: 212222240054
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo{
    public static void main(String []args){
        Scanner sc=new Scanner (System.in);
        int a;
        int b;
        a=sc.nextInt();
        b=sc.nextInt();
        if(a<50 && a<b){
            System.out.println("true");
        }
        else{
            System.out.println("false");
        }
    }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/0d9c7d31-d18e-4fe7-a65b-fd8314121b75)



## RESULT:
Thus, the Java program to get values of variables 'a' and 'b' and then check if both the conditions 'a < 50' and 'a < b' are true is created successfully.
