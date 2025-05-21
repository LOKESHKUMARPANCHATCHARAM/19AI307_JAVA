# Ex.No:5(E) HAS-A RELATIONSHIP
## AIM:
To implement a  Java Program to Find the Largest or Max Number in Array using has - a relationship.
## ALGORITHM :
1.	Start the program.
2.	Create a class ArrayData:
a.	Declare an integer array and a variable for size.
b.	Create a method to read array elements from the user.
3.	Create another class ArrayOperation:
a.	Create a method findMax() that accepts an ArrayData object.
b.	Loop through the array and find the largest element.
4.	In the main() method of a class Main:
a.	Create an object of ArrayData and read the input.
b.	Create an object of ArrayOperation and call findMax() by passing the ArrayData object.
5.	Display the largest number.
6.	End the program.



## PROGRAM:
 ```
/*
Program to implement a HAS-A RelationShip
Developed by:LOKESH KUMAR P 
RegisterNumber: 212222240054
*/
```

## Sourcecode.java:
```
import java.util.*;
class Product{
    private int num1;
    private int num2;
    
    public void setNum(int num1,int num2){
        this.num1=num1;
        this.num2=num2;
    }
    public int getNum1(){
        return num1;
    }
    public int getNum2(){
        return num1;
    }
    public void getProduct(){
        System.out.println((num1*num2));
    }
}
public class Main{
    public static void main(String[]args){
        Scanner sc=new Scanner(System.in);
        int n1=sc.nextInt();
        int n2=sc.nextInt();
        Product ob=new Product();
        ob.setNum(n1,n2);
        ob.getProduct();
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/c784740a-decd-42c2-ab1f-70d1c702b057)



## RESULT:
Thus the java program to Find the Largest or Max Number in Array using has - a relationship was executed successfully. 

