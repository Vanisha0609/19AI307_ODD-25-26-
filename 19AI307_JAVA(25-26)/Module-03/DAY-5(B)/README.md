# Ex.No:3(F) WRAPPER CLASS

## QUESTION:
Write a Java program to find the square root of a number using Double wrapper class.

## AIM:
To write a Java program that reads a number in string format, converts it into a double, and prints its square root using the Math.sqrt() function.

## ALGORITHM :
1. Start the program.
2. import necessary packages
3. Create a Scanner object to read input from the user.
4. Read a string value representing a number.
5. Convert the string to a Double using Double.parseDouble().
6. Use Math.sqrt() to compute the square root of the number.
7. Display the result in the required format.
8. End the program



## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:

```
import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        String str = s.next();
        
        Double num = Double.parseDouble(str);
        System.out.println("Square root of "+num+" is: "+(Math.sqrt(num)));
    }
}

```


## OUTPUT:


<img width="741" height="233" alt="image" src="https://github.com/user-attachments/assets/2fee1177-ab57-4c63-b6a0-134a9bb416fe" />


## RESULT:
The program has been executed successfully and the desired output has been obtained.
