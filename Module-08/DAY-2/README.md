# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a java program to append a NUMBER in a file “testout.txt” using Writer.


## ALGORITHM :
1.	It creates a file testout.txt, writes "Welcome to Java File Concept -Reader" to it, and displays this initial content.
2.	It reopens the file in append mode and adds "1234567890" at the end of the existing content.
3.	It reads the file's content (Welcome to Java File Concept -Reader1234567890) and displays it.
4.	The file is deleted using file.delete().
5.	It tries to read the file again, but this throws an exception since the file no longer exists.




## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by:LOKESH KUMAR P 
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:
```
import java.io.*;
import java.util.*;
public class Main{
    public static void main(String argv[]){
        Scanner sc = new Scanner(System.in);
        String s = sc.nextLine();
        char array[] = new char[39];
        try{
            StringReader input = new StringReader(s);
            input.read(array);
            System.out.println("Data read from the string:");
            System.out.println(array);
            input.close();
        }catch(Exception e){
            System.out.println(e);
        }
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/dedd455d-75e6-4004-b4af-5513ae04681a)



## RESULT:
Thus, the java program to append a NUMBER in a file “testout.txt” using Writer.was executed and verified successfully



