import java.util.Scanner;
public class Fibonacci
{
public static void main (String []args)
{
int c=0,a=1,b=1;
Scanner s=new Scanner(System.in);
System.out.println("enter any number:");
int n=s.nextInt();
System.out.println("1 1");
while(c<=n)
{
c=a+b;
System.out.println(c);
a=b;
b=c;

}
}
}

