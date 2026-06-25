import java.util.Scanner;

class Marksheet {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter Student Name: ");
        String name = sc.nextLine();

        System.out.print("Enter Marks in 5 Subjects: ");
        int m1 = sc.nextInt();
        int m2 = sc.nextInt();
        int m3 = sc.nextInt();
        int m4 = sc.nextInt();
        int m5 = sc.nextInt();

        int total = m1 + m2 + m3 + m4 + m5;
        double percentage = total / 5.0;

        String grade;
        if (percentage >= 90)
            grade = "A";
        else if (percentage >= 75)
            grade = "B";
        else if (percentage >= 60)
            grade = "C";
        else if (percentage >= 40)
            grade = "D";
        else
            grade = "F";

        System.out.println("\n--- MARKSHEET ---");
        System.out.println("Name: " + name);
        System.out.println("Total: " + total);
        System.out.println("Percentage: " + percentage + "%");
        System.out.println("Grade: " + grade);

        sc.close();
    }
}
