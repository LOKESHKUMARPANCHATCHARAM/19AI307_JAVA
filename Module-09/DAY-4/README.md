# Ex.No:9(D) TRANSIENT ---SERILIZATION

## AIM:
 To implement a Java program to perform Transient in Employee details in Serializable interface to make its object serialized.

## ALGORITHM :
1.	Get employee name and designation from the user.
2.	Save the Employeeinfo object to emp.txt.
3.	Read the object back from emp.txt.
4.	Print employee name and designation (designation is null due to transient).
5.	Delete File: Delete emp.txt and handle any exceptions while trying to read it.




## PROGRAM:
 ```
/*
Program to implement a Transient using Java
Developed by: LOKESH KUMAR P
RegisterNumber: 212222240054 
*/
```

## Sourcecode.java:

```

try
 {
  Scanner sc=new Scanner(System.in);
  String name=sc.nextLine();
  String rollno=sc.nextLine();
  Studentinfo si1=new Studentinfo(name,rollno);
  FileOutputStream fos=new FileOutputStream("student.txt");
  ObjectOutputStream oos=new ObjectOutputStream(fos);
  oos.writeObject(si1);
  oos.close();
     
 }
  catch (Exception e)
  {
      System.out.println(e);
      
  }
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/8c598fb5-e8ff-42a2-be41-4c1124f19ea4)



## RESULT:
Thus, implementation of a Java program to perform Transient in Employee details in Serializable interface to make its object serialized was executed and verified successfully.

