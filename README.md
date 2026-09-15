# OOP-Exercise-Sheet-01
Java Object-Oriented Programming Solutions

# Q1 Identify and correct the errors
 A) Error: the variable k is used without being declared or initialized

 Correction :
```Java
public class Test {
	public static void main (String[] args) {
		int k = 2;
			int i = k + 2;
			System.out.println(i);
	}
}
```
 B) 
  Error: the variable k , j is used without being declared or initialized

 Correction :
```Java
public class Test {
	public static void main (String[] args) {
		int j ;
		int k ;
		int i = j = k = 2;
		System.out.println(i+""+j+""+k);
    	}
}
```
 # Q2) Constants 
A) a value is used several time in a Java program and should not change while the program is running.
	 Would you declare it as a variable or constant? Explain your choice.

Answer: Constant

Explanation: Because its value should not change during execution. Using final prevent accidental changes
		 and make the code clearer.

B) Write a Java statement that declares an int constant named SIZE 
```Java	
final int SIZE = 10 ;
