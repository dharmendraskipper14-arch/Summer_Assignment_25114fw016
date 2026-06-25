import java.util.Scanner;

class MenuCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int choice;
        do {
            System.out.println("\n1.Add 2.Subtract 3.Multiply 4.Divide 5.Exit");
            choice = sc.nextInt();

            if (choice == 5)
                break;

            System.out.print("Enter two numbers: ");
            double a = sc.nextDouble();
            double b = sc.nextDouble();

            switch (choice) {
                case 1:
                    System.out.println("Result = " + (a + b));
                    break;
                case 2:
                    System.out.println("Result = " + (a - b));
                    break;
                case 3:
                    System.out.println("Result = " + (a * b));
                    break;
                case 4:
                    System.out.println("Result = " + (a / b));
                    break;
            }
        } while (true);

        sc.close();
    }
}
