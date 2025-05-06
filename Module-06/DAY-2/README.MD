# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```
import java.util.*;
class Shape{
    void print(){
        System.out.println("Shapes Class");
    }
}
class Circle extends Shape{
    private int radius;
    public void set(){
        Scanner sc=new Scanner(System.in);
        radius=sc.nextInt();
    }
    public int getRad(){
        return radius;
    }
}
class Area extends Circle{
    void calc(){
        int radius=getRad();
        System.out.println("Area of Circle is " + 3.14 * radius * radius);
    }
}
public class Main{
    public static void main(String[] args){
        Area obj=new Area();
        obj.print();
        obj.set();
        obj.calc();
    }
}
```








## OUTPUT:
Input:2
Result:Shapes Class
Area of Circle is 12.56



## RESULT:
Thus the java program for multi-level inheritance was executed successfully.





