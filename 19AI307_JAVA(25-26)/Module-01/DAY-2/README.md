# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
A pirate ship has a code lock that only opens if:

The input code is even, and

If it is less than 100, say "Weak Code".

If it is between 100 and 999, say "Strong Code".

If the code is odd, deny access -"Access Denied".


## AIM:
To check whether a pirate code is even or odd and classify it as "Weak Code", "Strong Code", or "Access Denied",using conditional statements

## ALGORITHM :
1.Read the input integer code.

2.Check if the code is even using code % 2 == 0.

3.If even and less than 100 → print "Weak Code".

4.If even and between 100–999 → print "Strong Code".

5.Otherwise print "Access Denied" for all odd or invalid cases.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

public class PirateCodeLock {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int code = sc.nextInt();

        if (code % 2 == 0) { 
            if (code < 100) {
                System.out.println("Weak Code");
            } else if (code >= 100 && code <= 999) {
                System.out.println("Strong Code");
            }
            else{
                System.out.println("Access Denied");
            }
        } else {
            System.out.println("Access Denied");
        }

        sc.close();
    }
}

```




## OUTPUT:
<img width="764" height="299" alt="image" src="https://github.com/user-attachments/assets/86b716db-598c-4380-a1e7-c87632321fac" />



## RESULT:
The program classifies the code based on even/odd and its numeric range.
