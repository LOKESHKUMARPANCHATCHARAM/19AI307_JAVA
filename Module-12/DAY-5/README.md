# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: LOKESH KUAMR P
RegisterNumber:212222240054  
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

![image](https://github.com/user-attachments/assets/d5484961-ab26-43b4-b5b8-64031f1daa3b)



## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


