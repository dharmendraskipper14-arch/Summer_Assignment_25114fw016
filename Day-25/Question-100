import java.util.Scanner;

class SortWordsByLength {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a sentence: ");
        String str = sc.nextLine();

        String words[] = str.split(" ");

        for(int i = 0; i < words.length - 1; i++) {
            for(int j = i + 1; j < words.length; j++) {
                if(words[i].length() > words[j].length()) {
                    String temp = words[i];
                    words[i] = words[j];
                    words[j] = temp;
                }
            }
        }

        System.out.println("Words Sorted By Length:");
        for(String word : words)
            System.out.print(word + " ");

        sc.close();
    }
}
