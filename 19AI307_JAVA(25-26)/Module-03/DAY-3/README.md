# Ex.No:3(C) ABSTRACTION

## QUESTION:
Create abstract class GameScore with method finalScore().
Subclasses:

ArcadeGame: score = baseScore + (level × 100)

PuzzleGame: score = (attempts ≤ 3) ? 1000 - (attempts × 100) : 500

Input Format:

First line: 1 or 2
Second line: base, level (or attempts)

Output Format:

Final score (int)

## AIM:
To calculate game scores using an abstract class and subclass-specific implementations for Arcade and Puzzle games.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3. Create an abstract class with an abstract finalScore() method.

4. Implement ArcadeGame class to compute score as base + level × 100.

5. Implement PuzzleGame class to compute score based on attempts.

6. Read user choice and input values.

7. Create the correct object and print the final score.



## PROGRAM:
 ```
/*
Program to implement a Abstraction using Java
Developed by: Vanisha Ramesh
RegisterNumber:  212222040174
*/
```

## SOURCE CODE:

```

import java.util.*;
abstract class gamestore{
    abstract int finalscore();
}
class arcade extends gamestore{
    int base,level;
    arcade(int base,int level){
        this.base=base;
        this.level=level;
    }
    int finalscore(){
        return base+(level*100);
    }
}
class puzzle extends gamestore{
    int attempts;
    puzzle(int attempts){
        this.attempts=attempts;
    }
    int finalscore(){
        return (attempts<=3)?1000-(attempts*100):500;
    }
}
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int choice=sc.nextInt();
        gamestore gg;
        if(choice==1){
            int base=sc.nextInt();
            int level=sc.nextInt();
            gg=new arcade(base,level);
            System.out.println(gg.finalscore());
        }
        else{
            int attempts=sc.nextInt();
            gg=new puzzle(attempts);
            System.out.println(gg.finalscore());
        }
    }
}
```


## OUTPUT:

<img width="481" height="343" alt="image" src="https://github.com/user-attachments/assets/7d9b6b2e-7e1b-4c19-aafb-bdd6fc54e325" />



## RESULT:
The program correctly computes and prints the final score based on the selected game type.
