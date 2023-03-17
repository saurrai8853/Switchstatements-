# Switchstatements-
package mypackage;
import java.util.Scanner;
public class findPrice {
	public static void main(String[] args) {		 
		 Scanner Sc= new Scanner(System.in);
		 
		 String str1="Biscuit";
		 String str2="Solt";
		 String str3="Milk";
		 String str4="Choclate";
		 String str5="bread";
		
		//
			 System.out.print("Enter token Number:");
			 int ch= Sc.nextInt();
		 switch(ch){
		 case 1:
			 System.out.println("1:"+str1);		 
			 System.out.print("Enter rate:");
			 double rate=Sc.nextDouble();
			 System.out.print("Enter the item quantity:");
			 double quantity=Sc.nextDouble();
			 double Price= rate*quantity;
			 System.out.println("Price="+Price);
			 break;
		 case 2:
			System.out.println("2:"+str2);
			 System.out.print("Enter rate:");
			 double rate2=Sc.nextDouble();
			 System.out.print("Enter the item quantity:");
			 double quantity2=Sc.nextDouble();
			 double Price2= rate2*quantity2;
			 System.out.println(Price2);
			 break;
		 case 3:
			 System.out.println("3:"+str3);
			 System.out.print("Enter rate:");
			 double rate3=Sc.nextDouble();
			 System.out.print("Enter the item quantity:");
			 double quantity3=Sc.nextDouble();
			 double Price3= rate3*quantity3;
			 System.out.println("Price="+Price3);
			 break;
		 case 4:
			 System.out.println("4:"+str4);
			 System.out.print("Enter rate:");
			 double rate4=Sc.nextDouble();
			 System.out.print("Enter the item quantity:");
			 double quantity4=Sc.nextDouble();
			 double Price4= rate4*quantity4;
			 System.out.println("Price="+Price4);
			 break;
		 case 5:
			 System.out.println("5:"+str5);
			 System.out.print("Enter rate:");
			 double rate5=Sc.nextDouble();
			 System.out.print("Enter the item quantity:");
			 double quantity5=Sc.nextDouble();
			 double Price5= rate5*quantity5;
			 System.out.println("Price="+Price5);
			 break;
		 
			 default:
				 System.out.println("Invaild Input");}
				 System.out.println("Thanks for coming");
			 
		 }//while(ch==6);
		// } 
	
		 
	
	}
