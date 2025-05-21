# Ex.No:3(B) STRING BUFFER IN JAVA

## AIM:
To develop a java program use append() method concatenates the given argument with this String and use stringbuffer class.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `concat`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read two strings `a` and `b` from user input
4.	Create a `StringBuffer` object `sb` initialized with string `a`
5.	Append a space and string `b` to `sb`
6.	Print the concatenated result from `sb`
7.	End







## PROGRAM:
 ```
/*
Program to implement a String Buffer using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class RemoveX {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        
        String str = sc.nextLine();
        if (str.startsWith("x")) str = str.substring(1);
        if (str.endsWith("x")) str = str.substring(0, str.length() - 1);
        System.out.println(str); // Output: Hi
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/260c238c-f875-4834-8dad-1d404c30ffbb)






## RESULT:
Thus the java program use append() method concatenates the given argument with this String and use stringbuffer class was executed successfully.
