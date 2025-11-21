# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Construct a right-angled triangle star pattern using for loop.

## AIM:
To write a Java program using looping statements to print a right-angled triangle star pattern based on user input.

## ALGORITHM :
1.Start the program.

2.Import the necessary package 'java.util'

3.Read the number of rows from the user.

4.Use an outer loop to iterate through each row.

5.Use an inner loop to print stars (*) for each row.

6.Move to the next line after printing stars for each row.

7.End the program.



## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:
```
import java.util.*;
public class TrianglePattern
{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        for (int i = 1; i <= n; i++) 
        {         
            for (int j = 1; j <= i; j++) 
            {      
                System.out.print("* ");
            }
            System.out.println();              
        }
    }
}
```





## OUTPUT:
<img width="399" height="395" alt="image" src="https://github.com/user-attachments/assets/2b88b3fb-4070-4ba9-a5e1-e0c61d668232" />



## RESULT:
Thus, the Java program using looping statements to print a right-angled triangle star pattern was successfully written, executed, and verified.
