import java.util.Scanner;
class FunctionPalindrome
{
    int num,temp;
    
     void getdata(){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number:");
        num=sc.nextInt();
        
     }
     void putdata()
     {
        int rev=0,rem;
        temp=num;
        while(temp!=0){
             rem=temp%10;
            rev=rev*10+rem;
            temp=temp/10;
        }

        if(num==rev){
            System.out.print("palindrome");
        }else{
            System.out.println("Number is not palindrome:");
        }
    
    
     }
     public static void main(String[] args)
     {
FunctionPalindrome aa=new FunctionPalindrome();
        aa.getdata();
        aa.putdata();
        
        
     }
    }
