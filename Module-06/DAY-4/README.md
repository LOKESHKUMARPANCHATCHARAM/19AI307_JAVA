# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

// First interface for name and roll number
interface Student {
    void getStudentData();
}

// Second interface for marks and average
interface Studentdet {
    void getMarks();
    void calculateAverage();
}

// Implementing class that uses both interfaces
class Studentdetails implements Student, Studentdet {
    int rollNo;
    String name;
    int[] marks = new int[6];
    double average;

    Scanner sc = new Scanner(System.in);

    // Implement getStudentData from Student interface
    public void getStudentData() {
        rollNo = sc.nextInt();
        sc.nextLine();  // Consume newline
        name = sc.nextLine();
    }

    // Implement getMarks from Studentdet interface
    public void getMarks() {
        for (int i = 0; i < 6; i++) {
            marks[i] = sc.nextInt();
        }
    }

    // Implement calculateAverage from Studentdet interface
    public void calculateAverage() {
        int sum = 0;
        for (int mark : marks) {
            sum += mark;
        }
        average = sum / 6.0;
    }

    // Display result
    public void display() {
        System.out.println("Roll No : " + rollNo);
        System.out.println("Name : " + name);
        System.out.println("Average  : " + (int)average);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        Studentdetails student = new Studentdetails();
        student.getStudentData();
        student.getMarks();
        student.calculateAverage();
        student.display();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/ce08a4af-eabb-4995-ba70-502f590b82b8)



## RESULT:
Thus, the program has accessed the package from another package has been done successfully.

