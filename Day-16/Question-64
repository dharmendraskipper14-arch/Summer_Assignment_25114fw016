import java.util.Scanner;

class RemoveDuplicates {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter size of Array:");

        int n = sc.nextInt();
        int arr[] = new int[n];
    System.out.println("Enter Elements:");
        for(int i = 0; i < n; i++)
            arr[i] = sc.nextInt();

        System.out.println("Array after removing duplicates:");

        int i,j,count;
        for(i=0;i<n;i++){
            count=1;
            for(j=i+1;j<n;j++){
                if(arr[i]==arr[j]){
                    count++;
                }

            }
            if(count==1){
                System.out.println(arr[i]);
            }
            
        }

        sc.close();
    }
}
