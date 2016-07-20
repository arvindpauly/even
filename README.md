# even
import java.util.Scanner;
public class oddoreven {
	public static void main(String [] arg){
	Scanner ab=new Scanner(System.in);
	int x;
	System.out.println("enter the number to know whether it is odd or even");
	x=ab.nextInt();
	if(x/2==0)
	{
		System.out.println("the given number "+x+"is even number");
	}
	else
	{
		System.out.println(" the given number"+x+"is odd number");
		
	}

}
}
