import java.util.Scanner;

class RowWiseSum {
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

        for(int i = 0; i < r; i++) {
            int sum = 0;
            for(int j = 0; j < c; j++)
                sum += a[i][j];

            System.out.println("Row " + (i + 1) + " Sum = " + sum);
        }

        sc.close();
    }
}
