import java.util.Scanner;

class FrequencyElement {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size of array: ");
        int n = sc.nextInt();

        int arr[] = new int[n];

        System.out.println("Enter elements:");
        for(int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        System.out.print("Enter element to search: ");
        int key = sc.nextInt();

        int count=0;

        for(int i = 0; i < n; i++) {
            if(arr[i] == key) {
                count++;
            
            }
        }

        if(count!=0)
            System.out.println("Element's frequency in Array: " + count);
        else
            System.out.println("Element not found");

        sc.close();
    }
}
