import java.util.Scanner;

class MaxOccurringCharacter {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a string: ");
        String str = sc.nextLine();

        char maxChar = str.charAt(0);
        int maxCount = 0;

        for (int i = 0; i < str.length(); i++) {
            int count = 0;

            for (int j = 0; j < str.length(); j++) {
                if (str.charAt(i) == str.charAt(j))
                    count++;
            }

            if (count > maxCount) {
                maxCount = count;
                maxChar = str.charAt(i);
            }
        }

        System.out.println("Maximum Occurring Character = " + maxChar);

        sc.close();
    }
}
