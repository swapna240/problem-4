# problem-1
import java.util.Scanner;
class Calculator {
public double add(double a,double b) {
return a+b;
}
public double sub(double a,double b) {
return a-b;
}
public double mul(double a,double b) {
return a*b;
}
public double div(double a,double b) {
if(b!=0) {
return a/b;
}
else {
Throw new arithmetic Exception("cannot divide by zero!");
}
}
}
public class main {
public static void main (String[] args) {
Calculator calculator =new Calculator();
Scanner scan=new Scanner(System.in);
while(true)
{
System.out.println("enter the options");
System.out.println("enter 1 for+ addition");
System.out.println("enter 2 for+ subtraction");
System.out.println("enter 3 for+ multiplication");
System.out.println("enter 4 for+ division");
System.out.println("enter 5 for+ exit");
System.out.println("enter choices 1/2/3/4/5");
}
}
}





