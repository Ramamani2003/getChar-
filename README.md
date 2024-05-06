# getChar-
getChar() for java
import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
		String s1 = "Ramya Ragashiya Saranya";
		char ch[] = new char[25];
		s1.getChars(1, 10, ch, 0);// 0 is a default argument except mention  value other value are printed 
		System.out.println(ch);
	}
}
