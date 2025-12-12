# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to find the maximum odd number in an array

## AIM:
To read an array and find the maximum odd number present in it.

## ALGORITHM :
1. Start the program and read the size of the array.
2. Input all array elements from the user.
3. Initialize a variable to track the maximum odd number.
4. Traverse the array and update the maximum odd value when found.
5. Display the maximum odd number or a message if none exists.




## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
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
        int n=sc.nextInt();
        int[] arr=new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        int max=Integer.MIN_VALUE;
        for(int i=0;i<n;i++){
            if(arr[i]>max && arr[i]%2!=0) max=arr[i];
            else continue;
        }
        if(max==Integer.MIN_VALUE) System.out.print("No odd number found");
        else System.out.println(max);
    }
}
```




## OUTPUT:
<img width="1230" height="615" alt="image" src="https://github.com/user-attachments/assets/5f1b7b67-5de3-46c7-8c69-ef5eb813b962" />



## RESULT:

