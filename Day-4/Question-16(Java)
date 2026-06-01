import java.util.Scanner;

class armstrongrange {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter start: ");
        int start = sc.nextInt();

        System.out.print("Enter end: ");
        int end = sc.nextInt();

        for (int num = start; num <= end; num++) {
            int temp = num;
            int count = 0;
            int arms = 0;

            
            int t = temp;
            while (t != 0) {
                count++;
                t /= 10;
            }

            
            if (num == 0) {
                count = 1;
            }

            
            t = temp;
            while (t != 0) {
                int rem = t % 10;
                int pro = 1;

                for (int i = 1; i <= count; i++) {
                    pro *= rem;
                }

                arms += pro;
                t /= 10;
            }

            if (num == 0) {
                arms = 0;
            }

            if (num == arms) {
                System.out.print(num + " ");
            }
        }

        sc.close();
    }
}
