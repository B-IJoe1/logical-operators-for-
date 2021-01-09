# logical-operators-for-
if statements for && and || : logic operators on exam scores



    package lab02;
    import java.util.Scanner;

    public class HelloWorld
    {



     public static void main (String[] args)
    {
      //initialising variable and declaring the variable
    	  Scanner input = new Scanner (System.in);
    	  System.out.print("Please Enter a number");
    	  double score; 
    	  double score2;
    	  score = input.nextDouble();
    	  score2 = input.nextDouble();
    	  
    	
    	  System.out.print("Please Enter second number");
    	 
    	  //if statements for && and || logic operators on exam scores0
    	if ((score>90 && score2>90))
    			
    		System.out.println("Way to Go!");
    	
    	else if ((score2<70 || score<70 ))
    
    		System.out.println("Study More!");
    	
    	else  
    		
    		System.out.print ("Keep it up");
    	   	
    	  	
        }
        }
