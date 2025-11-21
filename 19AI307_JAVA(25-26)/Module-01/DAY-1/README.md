# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:
Lovely is training to become a logic wizard. She enters a gate that tests her understanding of logical conditions.

She is given two magical conditions:

hasKey – whether she has the golden key (boolean)

knowsPassword – whether she knows the secret password (boolean)

The gate then evaluates her truthfulness using logical operators:

Operator	Meaning
&&	Logical AND – both must be true
||	Logical OR– any one can be true
!	Logical NOT – reverse the result
 

Write a program that:

Accepts two boolean inputs: hasKey and knowsPassword

Displays the results of:

hasKey && knowsPassword
hasKey || knowsPassword
!hasKey
!knowsPassword
Input Format:
First line: true or false (hasKey)

Second line: true or false (knowsPassword)

Output Format:
Access with AND: <true/false>
Access with OR: <true/false>
Does NOT have key: <true/false>
Does NOT know password: <true/false>

## AIM:
To write a Java program that read two boolean values and apply logical AND, OR, and NOT operations.

## ALGORITHM :
1.Read the first boolean input as hasKey.

2.Read the second boolean input as knowsPassword.

3.Calculate hasKey && knowsPassword.

4.Calculate hasKey || knowsPassword.

5.Calculate !hasKey and !knowsPassword and print all results.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Vanisha Ramesh
RegisterNumber: 212222040174 
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        boolean input1=sc.nextBoolean();
        boolean input2=sc.nextBoolean();
        System.out.println("Access with AND: "+(input1 && input2));
        System.out.println("Access with OR: " +(input1 || input2));
        System.out.println("Does NOT have key: "+!input1);
        System.out.println("Does NOT know password: "+!input2);
    }
}
```
## OUTPUT:
<img width="948" height="352" alt="image" src="https://github.com/user-attachments/assets/25281494-35e9-4ae4-b69e-fabb573f85b3" />



## RESULT:
The program displays AND, OR, and NOT evaluations of the two boolean conditions.
