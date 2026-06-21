import java.util.Scanner;

class LongestWord {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a sentence: ");
        String str = sc.nextLine();

        String words[] = str.split(" ");

        String longest = "";

        for (String word : words) {
            if (word.length() > longest.length())
                longest = word;
        }

        System.out.println("Longest Word = " + longest);

        sc.close();
    }
}
