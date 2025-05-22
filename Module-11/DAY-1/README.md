# Ex.No:11(A)         JAVA TREESET
## AIM:
 To develop a Java program to iterate through all elements in a tree set.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `TreeSet` named `set` to store integers in sorted order
4.	Use a loop to read `n` integers and add each to `set`
5.	Use an enhanced `for` loop to print each element in `set`
6.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA TREESET using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
import java.util.TreeSet;

public class TreeSetFirstLast {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

    
        int n = Integer.parseInt(scanner.nextLine());

        // Create a TreeSet of strings
        TreeSet<String> treeSet = new TreeSet<>();

        
        for (int i = 0; i < n; i++) {
            String element = scanner.nextLine();
            treeSet.add(element);
        }

        // Display the TreeSet
        System.out.println("Tree set:");
        System.out.println(treeSet);

        // Display first and last elements
        if (!treeSet.isEmpty()) {
            System.out.println("First Element is: " + treeSet.first());
            System.out.println("Last Element is: " + treeSet.last());
        } else {
            System.out.println("The tree set is empty.");
        }

        scanner.close();
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/b146ac08-5bc9-459a-b4fb-b30895087f49)


## RESULT:
Thus the java program to iterate through all elements in a tree set was executed successfully.

