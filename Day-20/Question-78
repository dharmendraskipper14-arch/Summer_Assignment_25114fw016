import java.util.Scanner;

class SymmetricMatrix {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size: ");
        int n = sc.nextInt();

        int a[][] = new int[n][n];
        boolean symmetric = true;

        System.out.println("Enter matrix:");
        for(int i = 0; i < n; i++)
            for(int j = 0; j < n; j++)
                a[i][j] = sc.nextInt();

        for(int i = 0; i < n; i++) {
            for(int j = 0; j < n; j++) {
                if(a[i][j] != a[j][i]) {
                    symmetric = false;
                    break;
                }
            }
        }

        if(symmetric)
            System.out.println("Symmetric Matrix");
        else
            System.out.println("Not Symmetric Matrix");

        sc.close();
    }
}
