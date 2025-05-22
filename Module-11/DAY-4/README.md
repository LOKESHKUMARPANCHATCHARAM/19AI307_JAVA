# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program to insert and display the key and values using map interface.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `Deivamagal` with `main` method:
-	a) Read integer `n` (number of entries).
-	b) Create a `HashMap` `hash`.
4.	Loop to read key-value pairs and add to `hash`.
5.	Print `"Map: " + hash`, keys, values, and entries.
6.	End




## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
import java.util.stream.*;

public class MapComparingByValueExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        Map<Integer, String> map = new HashMap<>();

        // Read number of entries
        int n = scanner.nextInt();
        scanner.nextLine(); // consume newline

        // Read key-value pairs
        for (int i = 0; i < n; i++) {
            int key = Integer.parseInt(scanner.nextLine());
            String value = scanner.nextLine();
            map.put(key, value);
        }

        // Get entry set, stream it, sort by value, then print each entry as key=value
        map.entrySet()
            .stream()
            .sorted(Map.Entry.comparingByValue())
            .forEach(entry -> System.out.println(entry.getKey() + "=" + entry.getValue()));

        scanner.close();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/3539e2e6-dae0-4f2d-a8f6-8444d1c1ce74)



## RESULT:
Thus the java program to insert and display the key and values using map interface was  executed and verified successfully.


