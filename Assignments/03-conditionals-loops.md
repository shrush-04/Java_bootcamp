# [Video Link](https://youtu.be/ldYLYRNaucM)
## Write Java programs for the following: 

### Basic Java Programs
1. Area Of Circle Java Program
2. Area Of Triangle
3. Area Of Rectangle Program 
4. Area Of Isosceles Triangle 
5. Area Of Parallelogram
6. Area Of Rhombus
7. Area Of Equilateral Triangle
8. Perimeter Of Circle
9. Perimeter Of Equilateral Triangle
10. Perimeter Of Parallelogram
11. Perimeter Of Rectangle
12. Perimeter Of Square
13. Perimeter Of Rhombus
14. Volume Of Cone Java Program
15. Volume Of Prism
16. Volume Of Cylinder
17. Volume Of Sphere
18. Volume Of Pyramid
19. Curved Surface Area Of Cylinder
20. Total Surface Area Of Cube
21. Fibonacci Series In Java Programs
22. [Subtract the Product and Sum of Digits of an Integer](https://leetcode.com/problems/subtract-the-product-and-sum-of-digits-of-an-integer/)
23. Input a number and print all the factors of that number (use loops).
24. Take integer inputs till the user enters 0 and print the sum of all numbers
(HINT: while loop)
25. Take integer inputs till the user enters 0 and print the largest number from
all.
26. Addition Of Two Numbers

Answer:
package Conditional_statements_loops;

import java.util.Scanner;

public class Main {
	public static void main(String[] args) {
		Scanner in=new Scanner(System.in);
		
		/*System.out.println("area of circle");
		
		float r=in.nextFloat();
	    double area=0;
	    area=(3.14)*r*r;
	    System.out.println(area);*/
	    
	    
        /*System.out.println("area of triangle");
		
		float b=in.nextFloat();
		float h=in.nextFloat();
	    double area=0.5*b*h;
	    System.out.println(area);*/
		
        /*System.out.println("area of Isosceles Triangle");
		
		float base=in.nextFloat();
		float side=in.nextFloat();
		if (2 * side <= base) {
		    System.out.println("Invalid Isosceles Triangle");
		} else {
		    double area = (base * Math.sqrt(4 * side * side - base * base)) / 4;
		    System.out.println("Area = " + area);
		}*/
		
       /*System.out.println("area of rhombus");
		
		float d1=in.nextFloat();
		float d2=in.nextFloat();
	    double area=(d1 * d2)/2;
	    System.out.println(area);*/
		
      /*System.out.println("area of Equilateral Triangle");
		
		float side=in.nextFloat();
		
	    double area=double area = (Math.sqrt(3) / 4) * side * side;
	    System.out.println(area);*/
		
       /*	System.out.println("Volume of Sphere");
		
		float r=in.nextFloat();
		
	    double area=(4.0/3.0)*Math.PI*r*r*r;
	    System.out.println(area);*/
	    
		/*Fibonacci series
		int n=in.nextInt();
		int a=0;
		int b=1;
		int count=2;
		
		while(count<=n) {
			int temp=b;
			b=b+a;
			a=temp;
			count++;
		}
		System.out.println(b);*/
		
		/*System.out.println("Subtract the Product and Sum of Digits of an Integer");
		
		int a=in.nextInt();
		int b=in.nextInt();
		
		int sum=a+b;
		System.out.println(sum);
		int product=a*b;
		System.out.println(product);
		
		int result=sum-product;
		System.out.println(result);*/
		
		/*System.out.println("Enter numbers (0 to stop):");

		int sum = 0;
 
	
		while (true) {
		    int num = in.nextInt();

		    if (num == 0) {
		        break;
		    }

		    sum += num;
		}

		System.out.println("Sum = " + sum);*/
		
		
		/*System.out.println("Take integer inputs "
		+ "till the user enters 0 and print the largest number from\r\n"+ "all.");

		int num=in.nextInt();
		if(num==0){
			System.out.print("no number is entered");
			return;
			
		}
		
		int large=num;
		
		while(true) {
			 num=in.nextInt();
			
			if(num==0) {
				break;
			}
			
			if(num>large) {
				large=num;
			}
			 
		}
		System.out.println("Largest number: " + large);*/
		
		
		System.out.println("Input a number and print all the factors of that number (use loops).");
		
		int num=in.nextInt();
		
		for(int i=1; i<=num;i++) {
			if(num % i==0) {
			 System.out.println(i);
			}
		}
		 
			    
		
		
	}

}


### Intermediate Java Programs
1. Factorial Program In Java
2. Calculate Electricity Bill
3. Calculate Average Of N Numbers
4. Calculate Discount Of Product
5. Calculate Distance Between Two Points 
6. Calculate Commission Percentage
7. Power In Java
8. Calculate Depreciation of Value
9. Calculate Batting Average
10. Calculate CGPA Java Program
11. Compound Interest Java Program
12. Calculate Average Marks
13. Sum Of N Numbers
14. Armstrong Number In Java
15. Find Ncr & Npr
16. Reverse A String In Java
17. Find if a number is palindrome or not 
18. Future Investment Value
19. HCF Of Two Numbers Program
20. LCM Of Two Numbers
21. Java Program Vowel Or Consonant 
22. Perfect Number In Java
23. Check Leap Year Or Not
24. Sum Of A Digits Of Number
25. Kunal is allowed to go out with his friends only on the even days of a given month. Write a program to count the number of days he can go out in the month of August.
26. Write a program to print the sum of negative numbers, sum of positive even numbers and the sum of positive odd numbers from a list of numbers (N) entered by the user. The list terminates when the user enters a zero.
