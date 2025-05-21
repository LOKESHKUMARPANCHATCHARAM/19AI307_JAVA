# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    public static void main(String[]args){
        Scanner sc=new Scanner (System.in);
        int size1=sc.nextInt();
        int size2=sc.nextInt();
        int sum=0;
        int arr[][]=new int[size1][size2];
        for(int i=0;i<size1;i++){
            for(int j=0;j<size2;j++){
                arr[i][j]=sc.nextInt();
                sum+=arr[i][j];
            }
        }
        System.out.println("The sum of all values in the 2D array is: "+sum);
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/1179f592-2791-4020-88f4-8471facbf8fb)




## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


