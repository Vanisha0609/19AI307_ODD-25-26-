# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:

area(int side) for square

area(int length, int breadth) for rectangle

area(double radius) for circle

## AIM:
To calculate the area of a square, rectangle, and circle using method overloading in a single class.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. Create AreaCalculator with three overloaded area() methods.

4. Read side and compute square area.

5. Read length & breadth and compute rectangle area.

6. Read radius and compute circle area.

7. Print all computed areas.




## PROGRAM:
 ```
/*
Program to implement a Polymorphism using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class AreaCalculator {
    int area(int side) {
        return side * side;
    }

    int area(int length, int breadth) {
        return length * breadth;
    }

    double area(double radius) {
        return Math.PI * radius * radius;
    }
}
public class Main{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        AreaCalculator calc = new AreaCalculator();

        int side = sc.nextInt();
        System.out.println("Area of square: " + calc.area(side));

        int length = sc.nextInt();
        int breadth = sc.nextInt();
        System.out.println("Area of rectangle: " + calc.area(length, breadth));

        double radius = sc.nextDouble();
        System.out.println("Area of circle: " + calc.area(radius));

        sc.close();
    }
}
```




## OUTPUT:


<img width="939" height="521" alt="image" src="https://github.com/user-attachments/assets/81852fd7-f56c-4a01-a4bd-1d9ea594709a" />


## RESULT:

The program correctly computes areas of all shapes using method overloading.
