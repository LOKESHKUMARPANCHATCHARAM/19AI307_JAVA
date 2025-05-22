# Ex.No:10(D) JAVA HASHSET & LINKEDHASHSET

## AIM:
 To create a java program use hashset concepts in collection and add the elements to the hashset and then display the elements iterate(use while) in an unordered collection.


## ALGORITHM :
1.	Start the Program.
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `HashSet` named `hs` to store unique strings
4.	Use a loop to read `n` strings and add each to `hs`
5.	Use an enhanced `for` loop to print each element in `hs`
6.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA HASHSET & LINKEDHASHSET using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo{
    public static void main(String args[]){
        HashSet<String> hs=new HashSet<>();
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        sc.nextLine();
        for(int i=0;i<a;i++)
        {
            hs.add(sc.nextLine());
        }
        for(String aa:hs){
            System.out.println(aa);
        }
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/8b138cab-757f-4740-afb0-42f964e89ada)



## RESULT:
Thus the java program of hashmap concepts was executed and verified successfully.



