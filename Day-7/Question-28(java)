import java.util.Scanner;

class RecursiveReverse {
    static int rev = 0;

    static void reverse(int num) {
        if (num == 0)
            return;

        rev = rev * 10 + (num % 10);
        reverse(num / 10);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int num = sc.nextInt();

        reverse(num);

        System.out.println("Reversed Number = " + rev);
    }
}
