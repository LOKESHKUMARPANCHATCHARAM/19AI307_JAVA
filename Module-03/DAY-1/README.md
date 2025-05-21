# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[]args){
        Scanner sc=new Scanner(System.in);
        String sentence=sc.nextLine();
        String words[]=sentence.split(" ");
        for(String word:words){
            System.out.println(word);
        }
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/5959e794-b51f-42c2-a5e7-0a7747bcae45)




## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

