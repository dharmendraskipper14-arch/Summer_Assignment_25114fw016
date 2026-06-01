import java.util.Scanner;
class armstrongcheck
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int num,temp,count=0,i,rem,arms=0;
        System.out.println("Enter the number:");
        num=sc.nextInt();
        temp=num;
    int original=num;
        while(num!=0){
            num=num/10;
            count++;

        }
         
        while(temp!=0){
            rem=temp%10;
            int pro=1;
            for(i=1;i<=count;i++){
              pro=pro*rem;
            }
         arms=arms+pro;
         temp=temp/10;
        }
        if(original==arms){
            System.out.println("Armstrong");
        }else{
            System.out.println("Not Armstrong");
        }
        sc.close();
    }
}
