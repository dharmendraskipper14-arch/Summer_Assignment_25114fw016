import java.util.Scanner;

class DiagonalSum {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter size of square matrix: ");
        int n = sc.nextInt();

        int a[][] = new int[n][n];
        int sum1 = 0,sum2=0;

        System.out.println("Enter matrix:");
        for(int i = 0; i < n; i++)
            for(int j = 0; j < n; j++)
                a[i][j] = sc.nextInt();

        for(int i = 0; i < n; i++){
            sum1 += a[i][i];
           sum2+=a[i][n-1-i];
        }

        System.out.println("Primary Diagonal Sum = " + sum1);
        System.out.println("Secondary Disgonal Sum = " + sum2);


        sc.close();
    }
}
