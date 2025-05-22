# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )


## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by:LOKESH KUMAR P 
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:
```
import java.util.PriorityQueue;
import java.util.Scanner;

public class PriorityQueueExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        PriorityQueue<Integer> queue = new PriorityQueue<>();

       
        int n = scanner.nextInt();

        // Read elements and add to the queue
        for (int i = 0; i < n; i++) {
           
            int element = scanner.nextInt();
            queue.add(element);
        }

        // Display the elements in the priority queue
        System.out.println("Display the element of Queue:");
        System.out.println(queue);

        scanner.close();
    }
}
```






## OUTPUT:


![image](https://github.com/user-attachments/assets/80d4036d-6bf4-46b2-a31d-a314ab3613df)


## RESULT:
Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method )was executed successfully.


