# line2.java
import java.util.Scanner;

public class linecomparisonuc3 {
	public static void main(String[] args) {

		System.out.println("Welcome to Line Comparison Computation Program ");

		Scanner sc = new Scanner(System.in);


		System.out.print("Enter the value of starting point of x-axis  of frist line: ");
		double x1 = sc.nextDouble();


		System.out.print("Enter the value of starting point of y-axis  of frist line: ");
		double y1 = sc.nextDouble();


		System.out.print("Enter the value of end point of x-axis  of frist line: ");
		double x2 = sc.nextDouble();


		System.out.print("Enter the value of end point of y-axis  of frist line: ");
		double y2 = sc.nextDouble();


		double length_of_line = Math.sqrt(Math.pow((x2 - x1),2) + Math.pow((y2 - y1 ),2));


		System.out.println(length_of_line);


		System.out.print("Enter the value of starting point of x-axis  of Second line: ");
		double x3 = sc.nextDouble();


		System.out.print("Enter the value of starting point of y-axis  of Second line: ");
		double y3 = sc.nextDouble();


		System.out.print("Enter the value of end point of x-axis  of Second line: ");
		double x4 = sc.nextDouble();


		System.out.print("Enter the value of end point of y-axis  of Second line: ");
		double y4 = sc.nextDouble();


		double Sec_length_of_line = Math.sqrt(Math.pow((x4 - x3),2) + Math.pow((y4 - y3 ),2));
        	System.out.println(Sec_length_of_line);


		double lineOne = length_of_line;
		double lineTwo = Sec_length_of_line;


		if(length_of_line == Sec_length_of_line){
			System.out.println("The length of line 1 is equals to line 2");
			}

			else if(length_of_line > Sec_length_of_line){
				System.out.println("The length of line 1 is greater than  line 2");
	        }

			else
				System.out.println("The length of line 1 is less than line 2");

	}

}
