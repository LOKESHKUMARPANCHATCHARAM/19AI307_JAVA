# Ex.No:2(E)  SMALLEST ELEMENT IN AN ARRAY

## AIM:
To write a Java program that reads an array size and elements from the user and then finds and prints the smallest element in the array.
## ALGORITHM :
1.	Start the program.
2.	Read the size of the array from the user.
3.	Declare an array of the given size.
4.	Read the array elements from the user.
5.	Initialize a variable min with the first element of the array.
6.	Traverse the array using a loop.
7.	Compare each element with min. If an element is smaller, update min.
8.	After the loop ends, print the smallest number.
9.	End the program.
	

## PROGRAM:
 ```
/*
Program to implement a Smallest Element in an Array
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main{
    public static void main(String[]args){
        Scanner sc=new Scanner(System.in);
        int size1=5;
        int size2=5;
        int arr1[]=new int[size1];
        int arr2[]=new int[size2];
        System.out.println("The merged array is:");
        for(int i=0;i<size1;i++){
            arr1[i]=sc.nextInt();
            System.out.print(arr1[i]+" ");
        }
        for(int j=0;j<size1;j++){
            arr2[j]=sc.nextInt();
            System.out.print(arr2[j]+" ");
        }
        
        
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/8b59881e-e617-4263-9d49-4d021b2808c8)




## RESULT:
Thus the java program successfully reads the array size and elements from the user and correctly finds and prints the smallest number in the array.




