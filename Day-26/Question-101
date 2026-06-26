import java.util.Random;
import java.util.Scanner;

class NumberGuessingGame {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Random rand = new Random();

        int number = rand.nextInt(100) + 1;
        int guess;
        int number_of_guesses=0;

        do {
            System.out.print("Guess a number (1-100): ");
            guess = sc.nextInt();

            if (guess > number)
                System.out.println("Too High!");
            else if (guess < number)
                System.out.println("Too Low!");
            else
                System.out.println("Correct! You guessed it.");
            number_of_guesses++;
            
        }  
        
        while (guess != number);
        System.out.println("Total no guesses taken by you="+number_of_guesses);

        sc.close();
    }
}
