# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileInputStream wrapped in a BufferedInputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedInputStream and FileInputStream to release system resources.




## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: LOKESH KUMAR P
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:

```
  try
  {
     FileOutputStream fout=new FileOutputStream("sample.txt");    
     BufferedOutputStream bout=new BufferedOutputStream(fout);  
     Scanner sc=new Scanner(System.in);
     String s=sc.nextLine();    
     byte b[]=s.getBytes();    
     System.out.println("Original Data:" +s);
     System.out.print("After Skipping:");
     bout.write(b,5,10);    
     bout.close();    
     fout.close();    
       
}
catch (IOException e) 
{
      e.printStackTrace();
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/cd21b764-1479-4a5e-8198-67ebcc86875c)



## RESULT:
Thus, the java program file for displaying the data from the file after skip method using FileInputStream & BufferedInputStream was executed and done successfully.


