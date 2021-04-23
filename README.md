# javaGrammer
package a__;

import java.util.ArrayList;
import java.util.Scanner;


public class a034 {
	public static void main(String[] args) {
		sol1();
	}
	
	static void sol1() {
		Scanner sc=new Scanner(System.in);
		String ln=sc.next();
		System.out.println(Integer.toBinaryString(Integer.parseInt(ln)));
		
	}
	
	static void sol2() {
		Scanner sc=new Scanner(System.in);
		int a=sc.nextInt();
		ArrayList<Integer> arr1=new ArrayList<>();
		while(a>1) {
			arr1.add(a%2);
			a/=2;
		}
		for(int i=arr1.size();i>-1;i++) {
			System.out.print(arr1.get(i));
		}
	}

}
