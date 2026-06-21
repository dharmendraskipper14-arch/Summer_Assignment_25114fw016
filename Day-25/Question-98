import java.util.Scanner;

class CommonCharacters {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first string: ");
        String s1 = sc.nextLine();

        System.out.print("Enter second string: ");
        String s2 = sc.nextLine();

        System.out.print("Common Characters: ");

        for(int i = 0; i < s1.length(); i++) {
            char ch = s1.charAt(i);

            if(s2.indexOf(ch) != -1 &&
               s1.indexOf(ch) == i) {
                System.out.print(ch + " ");
            }
        }

        sc.close();
    }
}
