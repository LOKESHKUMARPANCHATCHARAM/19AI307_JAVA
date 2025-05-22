# Ex.No:11(C)             JAVA LINKED HASHMAP
 ## AIM :

To Create a java program to display the contains key of 104 and to retrieve the key and value using linked hash map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `LinkedHashMap` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	Check if the `hash` contains the key `104` and print the result
7.	End


## PROGRAM:
 ```
/*
Program to implement a JAVA LINKED HASH MAP using Java
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.LinkedHashMap;
import java.util.Map;
import java.util.Scanner;

public class LinkedHashMapIsEmptyExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Create a LinkedHashMap to preserve insertion order
        LinkedHashMap<Integer, String> map = new LinkedHashMap<>();

        // Read number of entries
        int n = scanner.nextInt();
        scanner.nextLine(); // consume newline

        // Read key-value pairs
        for (int i = 0; i < n; i++) {
            int key = Integer.parseInt(scanner.nextLine());
            String value = scanner.nextLine();
            map.put(key, value);
        }

        // Display each entry in insertion order
        for (Map.Entry<Integer, String> entry : map.entrySet()) {
            System.out.println(entry.getKey() + " " + entry.getValue());
        }

        // Check if the map is empty
        System.out.println("Is HashMap is empty: " + map.isEmpty());

        scanner.close();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/ba9a28e6-9579-4113-a1c1-9e34b9d3960d)



## RESULT:
Thus the  java program to display the contains key of 104 and to retrieve the key and value using linked hash map was executed successfully.








