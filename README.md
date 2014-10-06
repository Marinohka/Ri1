Ri1
===

	import java.io.*;
	public class Input  {
	public static void main (String args []) throws Exception {
	BufferedReader d = new BufferedReader(new InputStreamReader(System.in));
	String a = d.readLine();
	System.out.println("You typed: "+a);
	try
	{
	int i = Integer.parseInt(a);
	System.out.println("Integer: "+i);
	}
	catch(Exception e) {System.out.println("Error translating text to int");}
	}
	}


