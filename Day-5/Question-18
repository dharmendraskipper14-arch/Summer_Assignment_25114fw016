import java.util.Scanner;
class strongnumber
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int i,num,temp,sum=0,fact=1;
        System.out.println("Enter the number:");
        num=sc.nextInt();
        temp=num;
        while(temp>0){
            int rem=temp%10;
            for(i=1;i<=rem;i++){
                fact=fact*i;
            }
            sum=sum+fact;
            temp=temp/10;
        }
        if(sum==num)
            System.out.println("Strong Number");
        else
            System.out.println(" Not Strong Number");
        sc.close();
    }
}
