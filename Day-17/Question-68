import java.util.Scanner;

class CommonElements {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter size of array1:");

        int n1 = sc.nextInt();
        int a[] = new int[n1];
        System.out.println("Enter elements:");

        for(int i = 0; i < n1; i++)
            a[i] = sc.nextInt();
        System.out.println("Enter size of Array2:");

        int n2 = sc.nextInt();
        int b[] = new int[n2];
        System.out.println("Enter Elements:");

        for(int i = 0; i < n2; i++)
            b[i] = sc.nextInt();
        System.out.println(" Common Elements in Array :");

        

        for(int i = 0; i < n1; i++) {
            boolean found = false;

            for(int j = 0; j < n2; j++) {
                if(a[i] == b[j]) {
                    found = true;
                    System.out.println(a[i]+" ");
                    break;
                }
            }
        }

        sc.close();
    }
}
