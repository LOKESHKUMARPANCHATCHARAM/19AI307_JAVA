# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.StringTokenizer;

public class TokenizeString {
    public static void main(String[] args) {
        // String to be tokenized
        String str = "welcome to java# programming";
        
        // Create a StringTokenizer to split the string based on the '#' symbol
        StringTokenizer tokenizer = new StringTokenizer(str, "#");
        
        // Tokenize and print each part
        while (tokenizer.hasMoreTokens()) {
            System.out.println(tokenizer.nextToken());
        }
    }
}
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/4ac12de3-4e43-412f-b8f8-596d4d6d85fd)



## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
