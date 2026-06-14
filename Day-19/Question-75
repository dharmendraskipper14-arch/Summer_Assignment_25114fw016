import java.util.Scanner;

class TransposeMatrix {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter rows and columns: ");
        int r = sc.nextInt();
        int c = sc.nextInt();

        int a[][] = new int[r][c];

        System.out.println("Enter matrix:");
        for(int i = 0; i < r; i++)
            for(int j = 0; j < c; j++)
                a[i][j] = sc.nextInt();

        System.out.println("Transpose Matrix:");

        for(int i = 0; i < c; i++) {
            for(int j = 0; j < r; j++)
                System.out.print(a[j][i] + " ");
            System.out.println();
        }

        sc.close();
    }
}
