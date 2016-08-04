# Oops-2-Assignment-1

package project;

import java.util.Arrays;
import java.util.Collections;
import java.util.List;

public class Array
{

	private static final int i = 0;

	public static void main(String arg[])
	{
		String[] strDays =new String[]
				{"Sunday","Monday","Tuesday","Wednesday"};
		List<String>list=Arrays.asList(strDays);
		Collections.reverse(list);
		strDays=(String[])list.toArray();
		System.out.println("String array reversed");
		for(int i=0;i <strDays.length;i++);
		System.out.println(strDays[i]);
			
	}
}
