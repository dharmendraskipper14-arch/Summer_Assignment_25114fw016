import java.util.Scanner;

class MissingNumber {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter n: ");
        int n = sc.nextInt();

        int arr[] = new int[n - 1];

        System.out.println("Enter elements:");
        for (int i = 0; i < n - 1; i++) {
            arr[i] = sc.nextInt();
        }

        int total = n * (n + 1) / 2;
        int sum = 0;

        for (int i = 0; i < n - 1; i++) {
            sum += arr[i];
        }

        System.out.println("Missing Number = " + (total - sum));
        sc.close();
    }
}
