import java.util.Scanner;

class MoveZeroes {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size: ");
        int n = sc.nextInt();

        int arr[] = new int[n];

        System.out.println("Enter elements:");
        for(int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        int index = 0;

        for(int i = 0; i < n; i++) {
            if(arr[i] != 0) {
                arr[index] = arr[i];
                index++;
            }
        }

        while(index < n) {
            arr[index] = 0;
            index++;
        }

        System.out.println("Array after moving zeroes:");

        for(int i = 0; i < n; i++) {
            System.out.print(arr[i] + " ");
        }

        sc.close();
    }
}
