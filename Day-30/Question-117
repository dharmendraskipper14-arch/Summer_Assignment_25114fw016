import java.util.Scanner;

class StudentRecord {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
System.out.println("Enter the Record for how many students:");
        int  n=sc.nextInt();

        String names[] = new String[n];
        int marks[] = new int[n];

        for (int i = 0; i < n; i++) {
            System.out.print("Enter Name: ");
            names[i] = sc.next();

            System.out.print("Enter Marks: ");
            marks[i] = sc.nextInt();
        }

        System.out.println("\nStudent Records");
        for (int i = 0; i < n; i++) {
            System.out.println(names[i] + " - " + marks[i]);
        }

        sc.close();
    }
}
