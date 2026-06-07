import java.util.Scanner;

class LargestSmallest {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size of array: ");
        int n = sc.nextInt();

        int arr[] = new int[n];

        System.out.println("Enter array elements:");
        for(int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        int largest = arr[0];
        int smallest = arr[0];

        for(int i = 1; i < n; i++) {
            if(arr[i] > largest)
                largest = arr[i];

            if(arr[i] < smallest)
                smallest = arr[i];
        }

        System.out.println("Largest Element = " + largest);
        System.out.println("Smallest Element = " + smallest);

        sc.close();
    }
}
