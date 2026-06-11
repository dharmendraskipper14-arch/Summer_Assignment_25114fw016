import java.util.Scanner;

class MaxFrequency {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
    System.out.println("Enter no of elements:");
        int n = sc.nextInt();
        int arr[] = new int[n];

        for(int i = 0; i < n; i++)
            arr[i] = sc.nextInt();

        int maxCount = 0, element = arr[0];

        for(int i = 0; i < n; i++) {
            int count = 1;

            for(int j = i + 1; j < n; j++) {
                if(arr[i] == arr[j])
                    count++;
            }

            if(count > maxCount) {
                maxCount = count;
                element = arr[i];
            }
        }

        System.out.println("Element = " + element);
        System.out.println("Frequency = " + maxCount);

        sc.close();
    }
}
