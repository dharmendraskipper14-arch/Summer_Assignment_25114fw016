import java.util.Scanner;

class BinarySearch {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter size of Array:");

        int n = sc.nextInt();
        int arr[] = new int[n];
        System.out.println("Enter elements:");

        for(int i = 0; i < n; i++)
            arr[i] = sc.nextInt();

        System.out.print("Enter key: ");
        int key = sc.nextInt();

        int low = 0, high = n - 1;
        boolean found = false;

        while(low <= high) {
            int mid = (low + high) / 2;

            if(arr[mid] == key) {
                System.out.println("Found at index " + mid);
                found = true;
                break;
            }
            else if(arr[mid] < key)
                low = mid + 1;
            else
                high = mid - 1;
        }

        if(!found)
            System.out.println("Element not found");

        sc.close();
    }
}
