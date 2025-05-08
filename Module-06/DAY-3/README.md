# Ex.No:6(C)             HIERARCHICAL INHERITANCE 

## AIM:
  To demonstrate class inheritance and constructor chaining in Java by creating a Vehicle class and its child classes (Car, Truck, and Bus) with appropriate constructors.


## ALGORITHM :
1.Create a Vehicle class with a constructor that displays "Vehicle class has 3 Child Class".
2.Create a Car class that extends Vehicle and calls the parent constructor, displaying "Car is the one of the Child of Vehicle Class".
3.Create a Truck class that extends Vehicle and calls the parent constructor, displaying "Truck is the one of the Child of Vehicle Class".
4.Create a Bus class that extends Vehicle and calls the parent constructor, displaying "Bus is the one of the Child of Vehicle Class".
5.In the Main class, create objects of each child class (Car, Truck, and Bus) to invoke their constructors and display the messages.



## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```
class Vehicle
{
public Vehicle()
{
System.out.println("Vehicle class has 3 Child Class ");
}
}
class Car extends Vehicle
{
public Car()
{

System.out.println("Car is the one of the Child of Vehicle Class");
}
}
class Truck extends Vehicle
{
public Truck()
{
System.out.println("Truck is the one of the Child of Vehicle Class");
}
}
class Bus extends Vehicle
{
public Bus()
{

System.out.println("Bus is the one of the Child of Vehicle Class");
}
}
public class Main
{
public static void main(String[] args)
{
Car obj1=new Car();
Truck obj2=new Truck();
Bus obj3=new Bus();

}
}
```








## OUTPUT:
![image](https://github.com/user-attachments/assets/870e8daa-a9ea-444b-9365-14d9a8a17625)



## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.






