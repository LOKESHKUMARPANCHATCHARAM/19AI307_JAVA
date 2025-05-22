# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )
## ALGORITHM :

1.	Start the Program
2.	In `main`:
-	a) Create a `Scanner` object to read input.
-	b) Read an integer `n1` (the size of the first vector).
-	c) Initialize `Vector<String> vector1`.
-	d) Use a `for` loop to read `n1` strings and add each to `vector1`.
3.	Repeat similar steps for a second vector:
a)	Read an integer `n2` (size of the second vector).
b)	Initialize `Vector<String> vector2`.
c)	Use a `for` loop to read `n2` strings and add each to `vector2`.
4.	Use `equals()` to compare `vector1` and `vector2` and print whether they are equal.
5.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vector<String> vector = new Vector<>();

        // Read how many elements to read first (2)
        int n1 = Integer.parseInt(sc.nextLine());

        // Read n1 elements and add to vector
        for (int i = 0; i < n1; i++) {
            vector.add(sc.nextLine());
        }

        // Read second batch of n1 elements (again 2 elements)
        for (int i = 0; i < n1; i++) {
            vector.add(sc.nextLine());
        }

        System.out.println("The vector is: " + vector);

        // Read number of elements to add now (1)
        int n2 = Integer.parseInt(sc.nextLine());

        // Read n2 elements and add to vector
        for (int i = 0; i < n2; i++) {
            vector.add(sc.nextLine());
        }

        System.out.println("The new Vector is: " + vector);

        sc.close();
    }
}
```





## OUTPUT:


![image](https://github.com/user-attachments/assets/3259b4f6-02bc-486f-bd14-889278106296)


## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








