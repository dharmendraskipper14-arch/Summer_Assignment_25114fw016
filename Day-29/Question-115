import java.util.Scanner;

public class StringOperations {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a String: ");
        String str = sc.nextLine();

        System.out.println("\n----- String Operations -----");
        System.out.println("1. Length");
        System.out.println("2. Uppercase");
        System.out.println("3. Lowercase");
        System.out.println("4. Concatenation");
        System.out.println("5. Reverse String");
        System.out.println("6. Character at Index");
        System.out.println("7. Compare Strings");
        System.out.println("8. Check Palindrome");
        System.out.println("9. Exit");

        System.out.print("Enter Your Choice: ");
        int choice = sc.nextInt();
        sc.nextLine();

        switch (choice) {

            case 1:
                System.out.println("Length = " + str.length());
                break;

            case 2:
                System.out.println("Uppercase = " + str.toUpperCase());
                break;

            case 3:
                System.out.println("Lowercase = " + str.toLowerCase());
                break;

            case 4:
                System.out.print("Enter another String: ");
                String str2 = sc.nextLine();
                System.out.println("Concatenated String = " + str.concat(str2));
                break;

            case 5:
                String rev = "";
                for (int i = str.length() - 1; i >= 0; i--) {
                    rev += str.charAt(i);
                }
                System.out.println("Reverse String = " + rev);
                break;

            case 6:
                System.out.print("Enter Index: ");
                int index = sc.nextInt();
                if (index >= 0 && index < str.length())
                    System.out.println("Character = " + str.charAt(index));
                else
                    System.out.println("Invalid Index");
                break;

            case 7:
                System.out.print("Enter another String: ");
                String s = sc.nextLine();
                if (str.equals(s))
                    System.out.println("Strings are Equal");
                else
                    System.out.println("Strings are Not Equal");
                break;

            case 8:
                String reverse = "";
                for (int i = str.length() - 1; i >= 0; i--) {
                    reverse += str.charAt(i);
                }

                if (str.equalsIgnoreCase(reverse))
                    System.out.println("Palindrome String");
                else
                    System.out.println("Not a Palindrome");
                break;

            case 9:
                System.out.println("Program Ended.");
                break;

            default:
                System.out.println("Invalid Choice");
        }

        sc.close();
    }
}
