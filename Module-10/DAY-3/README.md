# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by arraylist class , adding n elements to object of List interface and display the list is empty or not.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and an empty `ArrayList` named `list`
-	b) Read integer `n`
4.	Check if `list` is empty, print corresponding message
5.	Use a loop to add `n` strings to `list`
6.	Check if `list` is empty again, print corresponding message
7.	End

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054

  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class GFG
{
	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al=new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
	       al.add(sc.next());
        }
        al.add(1,sc.next());
		
		System.out.println(al);
	}
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/123a0196-2b09-4e41-a7ce-07d3034af568)



## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










