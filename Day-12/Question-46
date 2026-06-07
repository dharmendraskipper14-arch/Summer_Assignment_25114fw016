import java.util.Scanner;
class FunctionArmstrong
{
    int num;
     void getdata(){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number:");
        num=sc.nextInt();
        
     }
     void putdata(){
        int temp,count=0,fact=1,rem,arms=0;;
        temp=num;
        while(temp!=0){
            temp/=10;
            count++;
        }
        temp=num;
        while(temp!=0){
       rem=temp%10;
       for(int i=1;i<=count;i++){
           fact=fact*rem;
       }
      arms+=fact;
      temp/=10;
        }
        if(num==arms){
            System.out.println("ARMSTRONG");
        }else{
            System.out.println("NOT ARMSTRONG");
        }

     }
    
    
     
     public static void main(String[] args)
     {
FunctionArmstrong aa=new FunctionArmstrong();
        aa.getdata();
        aa.putdata();
        
        
     }
    }
