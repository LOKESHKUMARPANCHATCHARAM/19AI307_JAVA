# Ex.No:10(B) JAVA LINKED LIST
## AIM :
To Create a java program to perform linkedlist, read size of the list , read the elements for the linkedlist and display the elements from the linkedlist.


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling and list functionality
3.	Define class `Hello` with the `main` method:
-	a) Create `Scanner` object `sc` for input
-	b) Read an integer `n` to specify the number of strings
-	c) Create a `LinkedList` named `str` to store strings
4.	Use a `for` loop to:
-	a) Read `n` strings from input and add each to `str`
5.	Print the entire `str` list
6.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED LIST using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.LinkedList;
import java.util.Scanner;
public class LinkedListDemo {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        LinkedList<String> linkedList = new LinkedList<>();
        int size = scanner.nextInt();
        scanner.nextLine(); 
        for (int i = 0; i < size; i++) {
            String element = scanner.nextLine();
            linkedList.add(element);
        }
        System.out.println("Linked List :" + linkedList);
        String removedElement = linkedList.removeFirst();
        System.out.println("Element to be removed:" + removedElement);
        System.out.println("LinkedList:" + linkedList);
        scanner.close();
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/2b572255-3397-4e60-bec6-3e8d320bd821)


## RESULT:
Thus the Java program of the creation of a linkedlist was executed successfully.





