# Ex.No:12(A)         JAVA TREE MAP
## AIM:
 To implement a Java program to associate the specified value with the specified key in a Tree Map.

## ALGORITHM :

1.	Start the Program
2.	Import `java.util.*` and `java.util.Map.Entry`
3.	Define `Example6` class with `main` method:
-	a) Initialize `TreeMap<String, String> tree_map1`
-	b) Read integer `size` for entries count.
4.	Use a loop to:
-	a) Read `String` values `n1` and `s1`
-	b) Insert each pair into `tree_map1`
5.	Print `tree_map1` as `"Original TreeMap content: "`
6.	Define `sort_key` class that implements `Comparator<String>`:
-	Override `compare` method to compare `String` values `str1` and `str2` using
`compareTo`
7.	End



## PROGRAM:
 ```
/*
Program to implement a JAVA TREE MAP using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
import java.util.TreeMap;

public class TreeMapKeySearch {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        TreeMap<String, String> map = new TreeMap<>();

        int n = sc.nextInt();
        sc.nextLine(); // Consume newline

        // Read n key-value pairs
        for (int i = 0; i < n; i++) {
            String key = sc.nextLine();
            String value = sc.nextLine();
            map.put(key, value);
        }

        // Display the TreeMap
        System.out.println(map);

        // Check for specific keys
        if (map.containsKey("C1")) {
            System.out.println("The Tree Map contains key C1");
        } else {
            System.out.println("The Tree Map does not contain key C1");
        }

        if (map.containsKey("C5")) {
            System.out.println("The Tree Map contains key C5");
        } else {
            System.out.println("The TreeMap does not contain key C5");
        }

        sc.close();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/18b7910c-d32d-4789-b6f8-4824bc36cece)



## RESULT:
Thus the Java program to associate the specified value with the specified key in a Tree Map was executed successfully.
