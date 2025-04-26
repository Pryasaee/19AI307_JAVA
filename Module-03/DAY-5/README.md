# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```
public class StringBuilderExample {
    public static void main(String[] args) 
        String str1 = "hello";
        StringBuilder sb = new StringBuilder(str1);  
        System.out.println("StringBuilder content: " + sb.toString());  
        System.out.println("Length of StringBuilder: " + sb.length());  
        System.out.println("Memory address of StringBuilder object: " + sb.hashCode());
    }
}
```








## OUTPUT:
```
Input	
hello
Result
5
21
```



## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

