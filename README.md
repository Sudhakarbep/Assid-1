1.
package boolian;

public class wh {

	public static void main(String args[] ) {
	int i = 10;
	while(i<=50) {
	System.out.println("i="+i);
	i++;
	}
	}
}

2.
package boolian;

public class Postive {
	public static void main (String[]args) {
	int number =123;
	if (number>0) {
		System.out.println("The number is postive = "+number);
	}else if(number<0) {
		System.out.println("the num is negative ="+number);
	}else {
		System.out.println("the number is zero");
	}
	
	}

}

package boolian;

public class Postive {
	public static void main (String[]args) {
	int number =-100;
	if (number>0) {
		System.out.println("The number is postive = "+number);
	}else if(number<0) {
		System.out.println("the num is negative ="+number);
	}else {
		System.out.println("the number is zero");
	}
	
	}

}


3 
package boolian;

public class Revers {
public static void main (String[]args) {
	int n = 876, reverse=0;
	while(n!=0) {
	int digit = n%10;
	reverse = reverse*10 +digit;
	n = n/10;}
	
	System.out.println("Reverse ="+reverse);
	
}	

5..

package boolian;

public class Discount {

	public static void main(String[] args) {
		int Rs = 999;
		if (Rs<=500)
			System.out.println("No Discount");
		else if (Rs>500 && Rs < 1000)
			System.out.println("10% Discount");
			else
				System.out.println("20 % Discount");
		}
	}

6..
	public class in {
	public class Main {
	    public static void main(String[] args) {
	        for (int i = 5; i >= 1; i--) {
	            System.out.println(i);
	            for (int j = 5; j <= 6 - i; j++) {
	                System.out.println(j);
	                for (int k = 1; k <= 5 - i; k++) {
	                    System.out.println(k);
	                }
	            }
	        }
	    }
	}
}

