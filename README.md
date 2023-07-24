# Swapcollege.java
com.java.college

package com.java.college;
import java.util.Scanner;

public class Swap {

	public static void main(String[] args) {
		System.out.println("Enter the value of x and y");
		Scanner sc = new Scanner(System.in);
		int x = sc.nextInt();
		int y = sc.nextInt(); 
		//int x = 20, y = 10;
		System.out.println("before swapping" +x +""+y);
		x = x+y;
		y = x-y;
		x = x-y;
		y = x;
		System.out.println("after swapping" +x +""+y);
		
		
	}

}
