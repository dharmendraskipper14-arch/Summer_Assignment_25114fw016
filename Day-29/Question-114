import java.util.Scanner;

public class ArrayOperations {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int[] arr = {10, 20, 30, 40, 50};
        int choice, sum = 0;

        System.out.println("1. Display Array");
        System.out.println("2. Find Sum");
        System.out.println("3. Find Maximum");
        System.out.print("Enter your choice: ");
        choice = sc.nextInt();

        switch (choice) {
            case 1:
                System.out.print("Array Elements: ");
                for (int num : arr)
                    System.out.print(num + " ");
                break;

            case 2:
                for (int num : arr)
                    sum += num;
                System.out.println("Sum = " + sum);
                break;

            case 3:
                int max = arr[0];
                for (int num : arr) {
                    if (num > max)
                        max = num;
                }
                System.out.println("Maximum = " + max);
                break;

            default:
                System.out.println("Invalid Choice!");
        }

        sc.close();
    }
}
