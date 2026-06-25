import java.util.Scanner;

class BankAccount {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        double balance = 5000;

        System.out.println("1. Deposit");
        System.out.println("2. Withdraw");
        int choice = sc.nextInt();

        switch (choice) {
            case 1:
                System.out.print("Amount: ");
                double deposit = sc.nextDouble();
                balance += deposit;
                break;

            case 2:
                System.out.print("Amount: ");
                double withdraw = sc.nextDouble();

                if (withdraw <= balance)
                    balance -= withdraw;
                else
                    System.out.println("Insufficient Balance");
                break;
        }

        System.out.println("Current Balance: ₹" + balance);
        sc.close();
    }
}
