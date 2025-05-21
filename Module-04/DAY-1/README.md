# Ex.No:4(A)  JAVA CONSTRUCTOR
## AIM:
To create a Java program using constructor to print the circumference of rectangle.[l=5,w=6]

## ALGORITHM :
1.  1.	Start the Program.
2.	Define a class `circum`
3.	Inside the class, define two integer variables `l` and `w` with values 5 and 6, respectively
4.	Create a constructor `circum()`:
-	a) Calculate the `circumference` as `2 * (l + w)`
-	b) Print the `circumference` twice with different labels ("Area of First Rectangle" and "Area of Second Rectangle")
5.	In `main`, create an object `sc` of the `circum` class
6.	End





## PROGRAM:
 ```
/*
Program to implement a Constructor using Java
Developed by:LOKESH KUAMR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
class Employee{
    String name;
    String designation;
    
    
    Employee(String name,String designation){
        this.name=name;
        this .designation=designation;
    }
     String getName(){
         return name;
        
    }
    String getDesg(){
        return designation;
    }
}
public class sample{
    public static void main(String[]args){
        Employee obj=new Employee("John","Asst.Manager");
        System.out.println(obj.getName());
        System.out.println(obj.getDesg());
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/e780e2c2-51c2-4888-9213-f87e781f7911)


## RESULT:
Thus the Java program using constructor to print the circumference of rectangle was executed successfully.
