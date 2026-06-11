import java.util.Scanner;

class MergeArrays {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter size of Array1:");

        int n1 = sc.nextInt();
        int a[] = new int[n1];
        System.out.println("Enter Elements:");

        for(int i = 0; i < n1; i++)
            a[i] = sc.nextInt();
        System.out.println("Enter size of Array2:");


        int n2 = sc.nextInt();
        int b[] = new int[n2];
        System.out.println("Enter the Elements in Array2:");

        for(int i = 0; i < n2; i++)
            b[i] = sc.nextInt();

        int c[] = new int[n1 + n2];

        for(int i = 0; i < n1; i++)
            c[i] = a[i];

        for(int i = 0; i < n2; i++)
            c[n1 + i] = b[i];
     System.out.println("Elements in Array after merging:");
        for(int i=0;i<n1+n2;i++)
            System.out.print(c[i] + " ");

        sc.close();
    }
}
