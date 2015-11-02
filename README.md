# ForLoops 

## Summary
I created this program to practice with for loops. The code asks a user 4 simple math questions and tells the user if they are right or wrong.

## Code
Copied and pasted from java:
```java 
import java.util.Scanner;

public class ForLoops {
	public static void main(String[] args) {
		
		//Created for loop so code will run 4 times
		for (int i = 0; i < 4; i++){

		//Generate random numbers to add
		int number1 = (int)(Math.random() * 10);		
		int number2 = (int)(Math.random() * 10);
		int correctAnswer = number1 + number2;
		
		System.out.println("What is " + number1 + " + " + number2 + "?");
		
		//Create scanner object
		Scanner input = new Scanner(System.in);
		int userAnswer = input.nextInt();
		
		if (userAnswer == correctAnswer){
		System.out.println("That is correct!");
		}else{
		System.out.println("That is incorrect.");
				}
			}
		System.out.println("You're all done!");
	}
}
```
## Console
Copied text from console.
```java
What is 0 + 5?
5
That is correct!
What is 1 + 0?
1
That is correct!
What is 7 + 7?
14
That is correct!
What is 5 + 0?
5
That is correct!
You're all done!
```

