# Java-Programming-Essentials-Bootcamp-2
Assignment - Java Programming Essentials Bootcamp

import java.util.*;   
class myprogram
{  
public static void main(String args[])  
{  
String original, reverse = ""; 
Scanner in = new Scanner(System.in);   
System.out.println("Enter a number to check if it is palindrome or not");  
original = in.nextLine();   
int length = original.length();   
for ( int i = length - 1; i >= 0; i-- )  
reverse = reverse + original.charAt(i);  
if (original.equals(reverse))  
System.out.println("Entered number is a palindrome.");  
else  
System.out.println("Entered number isn't a palindrome.");   
}  
}  
