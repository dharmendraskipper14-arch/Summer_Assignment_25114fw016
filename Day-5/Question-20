import java.util.Scanner;
class largestprimefactor
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
       long  num,i,largest=0;
        System.out.println("Enter the number:");
        num=sc.nextInt();
        while(num%2==0){
            largest=2;
            num/=2;

        }
        
        for(i=3;i*i<=num;i+=2){
            while(num%i==0){
                largest=i;
                num/=i;
                
            }
        }
        if(num>2){
            largest=num;
        }
        System.out.println("Largest prime factor="+largest);
        sc.close();

    }
}
