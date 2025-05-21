# Ex.No:7(C)             THREAD IN JAVA
## AIM:
 To Develop a Java program to create Thread using Thread class.


## ALGORITHM :
1.  Start the Program
2.	Import necessary classes: `java.util.*`
3.	Define a class `Multi` that extends `Thread`:
-	a) Create a `Scanner` instance for user input.
-	b) Override the `run` method:
-	i) Read a string from user input.
-	ii) Print "Thread Name:" followed by the input string.
4.	In the `main` method:
-	a) Create an instance of `Multi`.
-	b) Create a new `Thread` instance using the `Multi` object.
-	c) Start the thread with `t1.start()`.
5.	End





## PROGRAM:
 ```
/*
Program to implement a Thread concepts using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

class MyRunnable implements Runnable {
    double value;

    MyRunnable(double value) {
        this.value = value;
    }

    public void run() {
        System.out.println("Thread Count: " + value);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double inputValue = sc.nextDouble();

        MyRunnable task = new MyRunnable(inputValue);
        Thread t = new Thread(task);
        t.start();

        sc.close();
    }
}
```






## OUTPUT:

![image](https://github.com/user-attachments/assets/c34f334a-0afa-482d-9dce-c06b656a6065)


## RESULT:
Thus the Java program for the creation of Thread using Thread class was executed successfully.







