import java.util.Scanner;

class  RotateLeft {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size: ");
        int n = sc.nextInt();

        int arr[] = new int[n];

        System.out.println("Enter elements:");
        for(int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        System.out.println("Rotate Left Array:");
     int first=arr[0];
        for(int i=0;i<n-1;i++) {
            arr[i]=arr[i+1];
        }
         arr[n-1]=first;
        for(int i=0;i<n;i++){
            System.out.println(arr[i]);
        }

        sc.close();
    }
}
