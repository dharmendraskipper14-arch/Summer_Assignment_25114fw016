import java.util.Scanner;

class IntersectionArrays {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size of first array: ");
        int n1 = sc.nextInt();
        int arr1[] = new int[n1];

        System.out.println("Enter first array elements:");
        for(int i = 0; i < n1; i++) {
            arr1[i] = sc.nextInt();
        }

        System.out.print("Enter size of second array: ");
        int n2 = sc.nextInt();
        int arr2[] = new int[n2];

        System.out.println("Enter second array elements:");
        for(int i = 0; i < n2; i++) {
            arr2[i] = sc.nextInt();
        }

        System.out.print("Intersection Elements: ");

        for(int i = 0; i < n1; i++) {
            boolean duplicate = false;

            for(int k = 0; k < i; k++) {
                if(arr1[i] == arr1[k]) {
                    duplicate = true;
                    break;
                }
            }

            if(!duplicate) {
                for(int j = 0; j < n2; j++) {
                    if(arr1[i] == arr2[j]) {
                        System.out.print(arr1[i] + " ");
                        break;
                    }
                }
            }
        }

        sc.close();
    }
}
