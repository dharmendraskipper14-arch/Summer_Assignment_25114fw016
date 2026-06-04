import java.util.Scanner;
class decimaltobinary
{
    public static void main(String[] args)
    {
        int decimal,binary=0,i=1,rem;
        Scanner sc =new Scanner(System.in);
        System.out.println("ENTER THE NUMBER:");
        decimal=sc.nextInt();
        while(decimal!=0){
             rem=decimal%2;
            binary+=rem*i;
            decimal/=2;
            i=i*10;
        }
        System.out.println("Binary of decimal is:"+binary);
        sc.close();
        
    }
}
