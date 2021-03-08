# Inter_Jav
package mypack.first;

import java.util.Scanner;

public class HellWorld
{
	public static void main(String args[])
	{
		int i,j,count;
	    int[] arr= {1,1,5,4,5};
	    for(i=0;i<arr.length;i++)
	    { 
	    count=0;
	        for(j=0;j<arr.length;j++) 
	        {
		     if((arr[i]==arr[j])&&(i!=j))  //i!=j is not counting the same element
		      { 
		      count++;
		      }
		    }
		    if(count==0)
			   System.out.println(arr[i]);
		}	
	}
}
