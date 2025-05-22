# Ex.No:8(E)  INPUT STREAM READER.

## AIM:
To write a Java program that takes continuous input from the user using InputStreamReader and exits when the input ends with the symbol #. The input is taken inside a do-while loop.
## ALGORITHM :
1.	Start the program.
2.	Import java.io.*.
3.	Create an InputStreamReader and wrap it in a BufferedReader.
    	Use a do-while loop to:
    	Prompt and read input from the user.
    	Check if the input ends with #.
4.	If yes, break the loop.
    	Otherwise, print the input.
    	Close the input stream.
5.	End the program


## PROGRAM:
 ```
/*
Program to implement a INPUT STREAM READER
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.io.*;  
    import java.util.*;
    public class JavaCharArrayReaderReadExample4 {  
       public static void main(String[] args) {  
    Scanner sc=new Scanner(System.in);
    String data=sc.nextLine();
   
    char[] array = new char[12];
    try {

      StringReader input = new StringReader(data);
     
      input.read(array);
      System.out.println("Data read from the string:");
      System.out.println(array);
      input.close();
    }
    catch(Exception e) {
      e.getStackTrace();
    }
       }  
    }
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/ed629a27-657f-44ff-b476-6779f02b2e81)



## RESULT:
Thus, the java program uses InputStreamReader to read input and handles loop termination based on the presence of # at the end of the input string, as specified. 

