# Reverse-the-string-

import java.util.*;
public class Main{
public static void main(String[] args) {
		Scanner sc=new Scanner( System.in);
		System.out.println("Enter the String:");
		String string = sc.nextLine();
	      String reverse = new StringBuffer(string).reverse().toString();
	      System.out.println("String before reverse: "+string);
	      System.out.println("String after reverse: "+reverse);
}
	}

