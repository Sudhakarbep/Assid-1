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
