# Ex.No:7(D) SYNCHRONIZATION
## AIM:
 To Develop a Java Program to perform static synchronization method for the below Scenario Create a Class Display with synchronized void wish method in that perform "Welcome : Message. Note :Assume Sleep as 400 ms i.e Thread.Sleep(400)
 
## ALGORITHM :
1.	1.	Start the Program.
2.	Define class `Display`:
-	a) Create a `Scanner` object `sc` for input
-	b) Define a synchronized method `wish(String str)`:
- i) Print "Welcome :: " followed by `str` (twice)
3.	End



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
class Table {
    // Synchronized method to print multiplication table
    synchronized void printTable(int num) {
        for (int i = 1; i <= 5; i++) {
            System.out.println(num * i);
            try {
                Thread.sleep(400); // Simulate a delay of 400ms
            } catch (InterruptedException e) {
                System.out.println(e);
            }
        }
    }
}

class MyThread1 extends Thread {
    Table table;

    MyThread1(Table table) {
        this.table = table;
    }

    public void run() {
        table.printTable(5);  // Print multiplication table for 5
    }
}

class MyThread2 extends Thread {
    Table table;

    MyThread2(Table table) {
        this.table = table;
    }

    public void run() {
        table.printTable(100);  // Print multiplication table for 100
    }
}

public class Main {
    public static void main(String[] args) {
        Table table = new Table();  // Create an instance of the Table class

        MyThread1 thread1 = new MyThread1(table);  // Create the first thread for 5's table
        MyThread2 thread2 = new MyThread2(table);  // Create the second thread for 100's table

        thread1.start();  // Start thread 1
        thread2.start();  // Start thread 2
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/677cf085-a448-4bd9-8691-0d4a530768c4)



## RESULT:
Thus the java program for synchronization was executed successfully.

