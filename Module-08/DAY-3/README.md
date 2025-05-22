# Ex.No:8(C)             FILTER READER
## AIM:
 To create a java Program to read the content from the file by using Filter Reader 


## ALGORITHM :
1.  Start the Program
2.  Define CustomFilterReader1, extending FilterReader, and override the read() method to replace spaces with $ while reading.
2.	In main(), create a FileOutputStream and a FilterOutputStream to write "India is my country" to a file named javaFile123.txt.
3.	Write the string to the file using filter.write(), then close the FilterOutputStream.
4.	Create a FileReader to read from javaFile123.txt, and wrap it with CustomFilterReader1.
5.	Read and print each character, where spaces are replaced with $, until the end of the file.
6.	Close CustomFilterReader1 and FileReader to free resources


## PROGRAM:
 ```
/*
Program to implement a Filter Reader using Java
Developed by:LOKESH KUMAR P 
RegisterNumber:212222240054  
*/
```

## Sourcecode.java:
```
   
       try
          {
            FileInputStream f=new FileInputStream("sample.txt");
            FilterInputStream f1=new BufferedInputStream(f);
            Scanner sc=new Scanner(System.in);
            int n=sc.nextInt();
            System.out.println("Available bytes in the file: "+f1.available());
            for(int i=0;i<n;i++)
            {
                f1.read();
            }
            System.out.println("Available bytes in the file: "+f1.available());
      
           } 
           catch (IOException e) 
      {
      System.out.println("An error occurred.");
     
    }
  
           


```






## OUTPUT:

![image](https://github.com/user-attachments/assets/6e257bbf-03f0-4ae2-b588-b86b2a0eb75a)


## RESULT:
Thus the java Program to read the content from the file by using Filter Reader  was executed and verified successfully.









