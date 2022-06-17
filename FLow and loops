package Flows;

public class UpperAndLowerCase {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		/*
		 
		  Write a program to convert from upper case to lower case and vice versa of an alphabet and
		   print the old character and new character as shown in example (Ex: a->A, M->m).
		 */
		
		
		char a = 'B';
	
		
		if(Character.isLowerCase(a)) {
		  System.out.print(a + " ->" + Character.toUpperCase(a));
		}else
			System.out.print(a + " ->" +Character.toLowerCase(a) );

	}

}


/_________________________________________________________________________



package Flows;
import java.util.*;
public class ReverseGivenNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		/*
		 Write a program to reverse a given number and print
         Eg1)
         I/P: 1234
         O/P: 4321
         Eg2)
         I/P: 1004
         O/P: 4001
		 */
		
		int num = 1234,reverse =0;
		
		while(num!=0) {
			
			
			int remainder = num% 10;
			reverse = reverse * 10 + remainder;
			num =num/10;
					
		
		
		}
		
		System.out.print(reverse);
		
		
		
	}

}
______________________________________________________

package Flows;

public class ProgramToCheckPositiveNegative {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		

		/*
		  Write a program to check if a given number 
		  is Positive, Negative, or Zero.
		 */
		
		int n = 3;
	
		if( n <  0 )
		{
			System.out.println("n is negative");
		}
		else if(n > 0)
		{
			System.out.println("n is positive");
		}
		else if(n == 0)
		{
			System.out.println("n is equal to zero");
		}

	}

}
______________________________________________________________

package Flows;
import java.util.*;
public class ProgramThatDisplayMenu {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		
		/*
		 * 
		 */
		
		Scanner sc = new Scanner(System.in);
		String question ="", option1 ="y";
		int option =0,num1,num2;
		
		
		do {
			System.out.println("Enter 1 to Add");
			System.out.println("Enter 2 to Sub");
			option= sc.nextInt();
			
			if(option == 1) {
				System.out.println("Enter num1");
				num1 = sc.nextInt();
				System.out.println("Enter num2");
				num2 = sc.nextInt();
				System.out.println(num1 + num2);
				
				
			}else {
				System.out.println("Enter num1");
				num1 = sc.nextInt();
				System.out.println("Enter num2");
				num2 = sc.nextInt();
				System.out.println(num1 - num2);
				
			}
				
			
			System.out.print("Do you want to continue[y,n]");
			question = sc.next();
			
		
		}while(option1.equals(question));
	}

}


_____________________________________

package Flows;
import java.util.*;

public class PrintInFlyodsFormat {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		/*
		 Write a program to print * in Floyds format (using for and while loop)
        *
        *  *
        *  *   *
        Example1:
        C:\>java Sample
        O/P Expected : Please enter an integer number
        Example1:
        C:\>java Sample 3
         O/P Expected :
                   *
                   *  *
                   *  *  *
		 */
		
		
		
		Scanner sc = new Scanner(System.in);
	    int num = sc.nextInt();
				
				for(int i =0; i < num;i++)
				{
					for(int x =0; x <= i;x++)
					{
						System.out.print("*");
						
					}
			        System.out.println();					
				}
		 
	}

}

___________________________________________________

package Flows;

public class PrintColorName {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		/*
		  Write a program to print the color name, based on color code. If color code in not valid then 
		  print "Invalid Code". R->Red, B->Blue, G->Green, O->Orange, Y->Yellow, W->White.
		 */
		
		
		char colorName = 'k';
		
		switch(colorName) {
		
		   
		case 'R':
			System.out.print("Red");
			break;
		case 'B':
			System.out.print("Blue");
			break;
		case 'G':
			System.out.print("Green");
			break;
		case 'O':
			System.out.print("Orange");
			break;
		case 'Y':
			System.out.print("Yellow");
			break;
		case 'W':
			System.out.print("White");
			break;
			
			default: System.out.print("Invalide code");
		
		
		}

	}

}


___________________________________________________

package Flows;
import java.util.*;

public class PrimeCompositeNumber {

	public static void main(String[] args) {
		
		// TODO Auto-generated method stub,
		
		

		/*
		 Write a program to check if a given number is prime or not
		 */
		
	   Scanner sc = new Scanner(System.in);
	   int num = sc.nextInt();
			   

	       for (int i = 2; i <=num ; i++)         
	       { 		  	  
	          int counter=0; 	  
	           for(num =i; num>=1; num--)
		       {
	               if(i%num==0)
		           {
	 		          counter = counter + 1;
		           }
		       }
		       if (counter ==2)
		       {
		     
		          System.out.print(i + "is a prime number");
		       }else
		       {
		    	   System.out.print(i + "is a not a prime number");
		       }
		       
	       }
	}

}


