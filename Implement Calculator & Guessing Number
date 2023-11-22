# MyInternshipProjects 
Program to Implement a Calculator: 

package calc;



import java.util.Scanner;



public class calculator {



	public static void main(String[] args) {

  		Scanner sc = new Scanner(System.in);

	      System.out.println("Enter value of 1st number ::");

	      int a = sc.nextInt();



	      System.out.println("Enter value of 2nd number ::");

	      int b = sc.nextInt();



	      System.out.println("Select operation");

	      System.out.println("Addition-a: Subtraction-s: Multiplication-m: Division-d: ");

	      char ch = sc.next().charAt(0);

	      switch(ch) {

	         case 'a' :

	         System.out.println("Sum of the given two numbers: "+(a+b));

	         break;

	         case 's' :

	         System.out.println("Difference between the two numbers: "+(a-b));

	         break;

	         case 'm' :

	         System.out.println("Product of the two numbers: "+(a*b));

	         case 'd' :

	         System.out.println("Result of the division: "+(a/b));

	         break;

	         default :

	         System.out.println("Invalid grade");

	      }

	   }

	}

 
import java.util.Scanner;

public class GuessNum {
    public static void guessingNumberGame() {
        Scanner sc = new Scanner(System.in);
        int number = 1 + (int) (100 * Math.random());
        int k = 5;
        int i, guess;
        System.out.println("A number is chosen" + " between 1 to 100." + " Guess the number" + " within 5 trials.");

        for (i = 0; i < k; i++) {
            System.out.println("Guess the number:");

            guess = sc.nextInt();

            if (number == guess) {
                System.out.println("Congratulations" + " you guessed the number.");
                break;
            } else if (number > guess && i != k - 1) {
                System.out.println("The number is" + " greater than" + guess);

            } else if (number < guess && i != k - 1) {
                System.out.println("The number is" + " less than" + guess);
            }
        }

        if (i == k) {
            System.out.println("you have exhausted" + " k trials.");
            System.out.println("The number was" + number);
        }
    }

    public static void main(String[] args) {
        guessingNumberGame();
    }
}
 
