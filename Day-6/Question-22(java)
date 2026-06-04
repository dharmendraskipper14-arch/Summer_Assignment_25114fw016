import java.util.Scanner;
class binarytodecimal
{
    public static void main(String[] args)
    {
        int decimal=0,binary,i=1,rem;
        Scanner sc =new Scanner(System.in);
        System.out.println("ENTER THE NUMBER:");
        binary=sc.nextInt();
        while(binary!=0){
             rem=binary%10;
            decimal+=rem*i;
            binary/=10;
            i=i*2;
        }
        System.out.println("Decimal of binary is:"+decimal);
        sc.close();
        
    }
}
