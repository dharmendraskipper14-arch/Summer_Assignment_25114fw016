import java.util.Scanner;

class SortNames {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter number of names: ");
        int n = sc.nextInt();
        sc.nextLine();

        String names[] = new String[n];

        System.out.println("Enter names:");
        for(int i = 0; i < n; i++) {
            names[i] = sc.nextLine();
        }

        for(int i = 0; i < n - 1; i++) {
            for(int j = i + 1; j < n; j++) {
                if(names[i].compareToIgnoreCase(names[j]) > 0) {
                    String temp = names[i];
                    names[i] = names[j];
                    names[j] = temp;
                }
            }
        }

        System.out.println("Sorted Names:");
        for(String name : names)
            System.out.println(name);

        sc.close();
    }
}
