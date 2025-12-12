# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to remove all spaces from a given string.

## AIM:
To remove all spaces from a given string and display the modified result.

## ALGORITHM :
1. Start the program and read a string from the user.
2. Replace all spaces in the string using a string function.
3. Store the updated string without spaces.
4. Display the modified string as the output.
5. End the program.



## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:
```
import java.util.*;
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String str=sc.nextLine();
        String str1=str.replaceAll(" ","");
        System.out.print("String without spaces: "+str1);
    }
}

```



## OUTPUT:
<img width="1229" height="309" alt="image" src="https://github.com/user-attachments/assets/01050335-c3ff-4cc8-9271-92f75d7505fb" />



## RESULT:
Thus, the program executed successfully and displayed the correct output based on the given input and conditions.
