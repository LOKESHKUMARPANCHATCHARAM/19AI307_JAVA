# Ex.No:9(E) STRING WRITER

## AIM:
To write a Java program that reads a string from the user and prints it using the StringWriter class.
## ALGORITHM :

a.	Start the program.
b.	Import java.io.* and java.util.Scanner.
c.	Create a Scanner object to read input from the user.
d.	Read a string from the user.
e.	Create a StringWriter object.
f.	Write the string to the StringWriter object.
g.	Convert the StringWriter content to a string using .toString().
h.	Print the result on the output screen.
i.	Close the writer.
j.	End the program.


## PROGRAM:
 ```
/*
Program to implement a STRING WRITER
Developed by:lokesh kumar p 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.io.ByteArrayInputStream;
import java.util.*;
public class Main {
  public static void main(String[] args) 
  {
      byte[] array = {1,2,3,4};
      Scanner sc=new Scanner(System.in);
      int a=sc.nextInt();
      try
      {
          ByteArrayInputStream by =new ByteArrayInputStream(array);
          by.skip(a);
          System.out.print("Input stream after skipping "+a+"  bytes: ");
          int data;
          while((data=by.read())!=-1)
          {
              System.out.print(data+", ");
          }
      
      
      
      

    }

    catch(Exception e) {
      e.getStackTrace();
    }
  }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/46e33bd9-794b-40fa-bbd1-e5913eab7de3)



## RESULT:
Thus, implementation of  a Java program was successfully reads a string from the user and uses StringWriter to write and print the string to the output screen.

