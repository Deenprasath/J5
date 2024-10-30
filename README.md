import java.util.Scanner;
public class Main 
{
    public static void main(String[] args)
    {
     
     Scanner sc = new Scanner(System.in);
     System.out.println("enter the basic salary");
     int a = sc.nextInt();
     int b=a*12000;
     int c=a*2340;
     System.out.println("so the total Salary is" + (a+b+c));
    }
}
 
