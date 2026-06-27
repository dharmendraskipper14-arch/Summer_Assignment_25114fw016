import java.util.Scanner;

class StudentManagementProject {

    static void display(String names[], int marks[]) {
        System.out.println("\nStudent Records");
        for (int i = 0; i < names.length; i++) {
            System.out.println(names[i] + " - " + marks[i]);
        }
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
System.out.println("Enter the Record For How Many Student:");
int n=sc.nextInt();

        String names[] = new String[n];
        int marks[] = new int[n];

        for (int i = 0; i < n; i++) {
            System.out.print("Enter Name: ");
            names[i] = sc.next();

            System.out.print("Enter Marks: ");
            marks[i] = sc.nextInt();

        }

        display(names, marks);

        sc.close();
    }
}
