# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
// Student class
class Student {
    int rollno;
    String name;
    static String college = "ABC"; 

  
    Student(int rollno, String name) {
        this.rollno = rollno;
        this.name = name;
    }

    void display() {
        System.out.println("Rollno is " + rollno + " Name is " + name + " College Name is " + college);
    }
}


public class Main {
    public static void main(String[] args) {
        Student s1 = new Student(101, "Student1");
        Student s2 = new Student(102, "Student2");
        Student s3 = new Student(103, "Student3");
        Student s4 = new Student(104, "Student4");

        
        s1.display();
        s2.display();
        s3.display();
        s4.display();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/80e172b0-1e86-47df-8eee-abae477679de)



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
