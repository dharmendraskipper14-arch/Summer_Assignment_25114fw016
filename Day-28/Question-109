import java.util.Scanner;

class LibraryManagement {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String book = "Java Programming";
        boolean issued = false;

        System.out.println("1. Issue Book");
        System.out.println("2. Return Book");
        int choice = sc.nextInt();

        if (choice == 1) {
            if (!issued) {
                issued = true;
                System.out.println(book + " Issued Successfully");
            }
        } else if (choice == 2) {
            issued = false;
            System.out.println(book + " Returned Successfully");
        }

        sc.close();
    }
}
