import java.util.Scanner;

class DescendingSort {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter size of Array:");

        int n = sc.nextInt();
        int arr[] = new int[n];
        System.out.println("Enter Elements:");

        for(int i = 0; i < n; i++)
            arr[i] = sc.nextInt();
        System.out.println("Descending array after sorting:");

        for(int i = 0; i < n - 1; i++) {
            for(int j = i + 1; j < n; j++) {
                if(arr[i] < arr[j]) {
                    int temp = arr[i];
                    arr[i] = arr[j];
                    arr[j] = temp;
                }
            }
        }

        for(int x : arr)
            System.out.print(x + " ");

        sc.close();
    }
}
