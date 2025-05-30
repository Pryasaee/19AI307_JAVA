# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To demonstrate the control flow of try-catch-finally in Java when an ArrayIndexOutOfBoundsException occurs in the try block and is handled in the catch block.

## ALGORITHM :
1.Declare and initialize an integer array.
2.Use a try block to access an invalid array index (causing ArrayIndexOutOfBoundsException).
3.Catch the exception in a catch block and display an error message.
4.Use a finally block to print a statement that executes regardless of the exception.
5.Execute the program to observe the flow through try, catch, and finally.





## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: Madhumitha.Y
RegisterNumber: 212222020014 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
     
        int[] arr = new int[4];
         
        try
        {
           int i=arr[4];
           System.out.println("Inside try block");
        }
        catch(ArrayIndexOutOfBoundsException ex){
            System.out.println("Exception caught in catch block");
        }
        finally
        {
            System.out.println("finally block executed");
        }
         
        
      
        System.out.println("Outside try-catch-finally clause");
    }
}
```
      






## OUTPUT:
https://github.com/Pryasaee/19AI307_JAVA/blob/d9de50ae8ab08c266084c5cd0e9f5eae8de3ea32/Module-07/DAY-2/5.png



## RESULT:
The program shows that the catch block handles the exception and the finally block always executes.

