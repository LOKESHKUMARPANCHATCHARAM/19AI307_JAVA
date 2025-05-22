# Ex.No:12(B)   COMPARABLE & COMPARATOR INTERFACE
## AIM :
To Write a java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection.


## ALGORITHM :
1.	Start the Program.
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
Program to implement a COMPARABLE & COMPARATOR INTERFACE using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;

class Student {
    int rollno;
    String name;
    String address;

    public Student(int rollno, String name, String address) {
        this.rollno = rollno;
        this.name = name;
        this.address = address;
    }

    @Override
    public String toString() {
        return rollno + " " + name + " " + address;
    }
}

class NameComparator implements Comparator<Student> {
    @Override
    public int compare(Student s1, Student s2) {
        // Case-sensitive name comparison (as per expected output)
        return s1.name.compareTo(s2.name);
    }
}

public class SortStudentsByName {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = Integer.parseInt(sc.nextLine());

        List<Student> students = new ArrayList<>();

        for (int i = 0; i < n; i++) {
            int rollno = Integer.parseInt(sc.nextLine());
            String name = sc.nextLine();
            String address = sc.nextLine();
            students.add(new Student(rollno, name, address));
        }

        System.out.println("Unsorted");
        for (Student s : students) {
            System.out.println(s);
        }

        System.out.println();
        System.out.println("Sorted by name");
        Collections.sort(students, new NameComparator());
        for (Student s : students) {
            System.out.println(s);
        }

        sc.close();
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/e04856be-6512-4b7c-b155-326d3d9f7caf)


## RESULT:
Thus the java program to compare two elements , if element is greater means display 1 otherwise display -1 use only comparable interface in java collection was executed successfully




