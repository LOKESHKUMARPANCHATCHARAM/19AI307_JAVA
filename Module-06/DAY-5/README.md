# Ex.No:6(E)  MULTIPLE INHERITANCE

## AIM:
To write a Java program using multiple inheritance through interfaces to read student details and marks, calculate the average, and display the mark sheet.

## ALGORITHM :

1.	Start the program.
2.	Create interface Student:
a.	Declare methods to read name and rollno.
3.	Create interface Studentdet:
a.	Declare a method to read marks of 6 subjects and calculate the average.
b.	Create a class Studentdetails that implements both interfaces:
c.	Define variables for name, roll number, marks array, and average.
4.	Implement all methods from the interfaces.
a.	Create a display() method to show student details and average.
5.	In main() method:
a.	Create an object of Studentdetails.
b.	Call the methods to get input and display results.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a Multiple Inheritance
Developed by: LOKESH KUMAR P
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
class Student{
    int Stu_id;
    void display(int Stu_id){
        System.out.println(Stu_id);
        
    }
}
class Subject extends Student{
    String sub1="Java";
    String sub2="DS";
    String sub3="TOC";
    String sub4="CG";
    void print(){
        System.out.println(sub1+" "+sub2+" "+sub3+" "+sub4);
    }
}
public class Main{
    public static void main(String[]args){
        Subject ob=new Subject();
        ob.display(101);
        ob.print();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/6810fb30-e1ec-4ed2-b374-e5b2ad02467b)



## RESULT:

Thus, the java program demonstrates multiple inheritance using interfaces and successfully displays the mark sheet of a student by collecting personal and academic data. 
