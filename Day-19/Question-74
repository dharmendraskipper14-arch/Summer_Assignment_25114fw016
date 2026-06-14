import java.util.Scanner;

class MatrixSubtraction {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter rows and columns: ");
        int r = sc.nextInt();
        int c = sc.nextInt();

        int a[][] = new int[r][c];
        int b[][] = new int[r][c];

        System.out.println("Enter first matrix:");
        for(int i = 0; i < r; i++)
            for(int j = 0; j < c; j++)
                a[i][j] = sc.nextInt();

        System.out.println("Enter second matrix:");
        for(int i = 0; i < r; i++)
            for(int j = 0; j < c; j++)
                b[i][j] = sc.nextInt();

        System.out.println("Matrix after Subtraction:");
        for(int i = 0; i < r; i++) {
            for(int j = 0; j < c; j++)
                System.out.print((a[i][j] - b[i][j]) + " ");
            System.out.println();
        }

        sc.close();
    }
}
