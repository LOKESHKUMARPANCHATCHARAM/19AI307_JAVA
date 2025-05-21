# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: LOKESH KUMAR P
RegisterNumber:  212222240054
*/
```

## Sourcecode.java:
```

    
    public Fruit(String name,String color,double weight){
        this.name=name;
        this.color=color;
        this.weight=weight;
    }
    public void display(){
        System.out.println("Fruit Name is " + name +",weight is "+weight+"kg and Color is "+color);
        
    }
    public static void main(String []args){
        Fruit grape=new Fruit("Grape","Purple",0.75);
        Fruit mango=new Fruit("Mango","Yellow",1.5);
        grape.display();
        mango.display();
    }
    
```







## OUTPUT:
![image](https://github.com/user-attachments/assets/ab301076-d155-4abc-beaf-c3d6a57c4deb)




## RESULT:
Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
