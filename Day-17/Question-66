import java.util.Scanner;

class UnionArray {
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
        System.out.println("Elements in Array after Union:");

        for(int i = 0; i < n1; i++)
            System.out.print(a[i] + " ");

        for(int i = 0; i < n2; i++) {
            boolean found = false;

            for(int j = 0; j < n1; j++) {
                if(b[i] == a[j]) {
                    found = true;
                    break;
                }
            }

            if(!found)
                System.out.print(b[i] + " ");
        }

        sc.close();
    }
}
