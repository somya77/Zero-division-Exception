# Zero-division-Exception
import java.util.Scanner;
class Test22
{
 public static void main(String args[])
{
 int a;
int b;
 Scanner obj=new Scanner(System.in);
 System.out.println("Enter the value of A:");
  a=obj.nextInt();
  System.out.println("Enter the value of B:");
b=obj.nextInt();
int c=a/b;
System.out.println("Division is:"+c);
}}

      THE OUTPUT OF THE PROGRAM IS:- Exception in thread "main" java.lang.ArithmeticException: / by zero
                                     at Test22.main(Test22.java:13)
