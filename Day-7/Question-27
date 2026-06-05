import java.util.Scanner;

class RecursiveSumDigits {

    static int sumDigits(int n) {
        

        if (n == 0)
            return 0;
        return (n%10)+sumDigits(n/10);
         

    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        

        System.out.print("Enter a number: ");
        int num = sc.nextInt();

        System.out.println("Sum of digits = " + sumDigits(num));
    }
}
