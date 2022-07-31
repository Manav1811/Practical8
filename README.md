# Practical8
package part1;
import java.util.*;
public class Practical8 {
	
	
	    public static void main(String[] args) {
	       Scanner sc=new Scanner(System.in);
	        char[][] arr1={  {'A', 'B', 'A', 'C', 'C', 'D', 'E', 'E', 'A', 'D'},
	                         {'D', 'B', 'A', 'B', 'C', 'A', 'E', 'E', 'A', 'D'},
	                         {'E', 'D', 'D', 'A', 'C', 'B', 'E', 'E', 'A', 'D'},
	                         {'C', 'B', 'A', 'E', 'D', 'C', 'E', 'E', 'A', 'D'},
	                         {'A', 'B', 'D', 'C', 'C', 'D', 'E', 'E', 'A', 'D'},
	                         {'B', 'B', 'E', 'C', 'C', 'D', 'E', 'E', 'A', 'D'},
	                         {'B', 'B', 'A', 'C', 'C', 'D', 'E', 'E', 'A', 'D'},
	                         {'E', 'B', 'E', 'C', 'C', 'D', 'E', 'E', 'A', 'D'} };
	        char[] arr2={'D','B','D','C','C','D','A','E','A','D'};
	for(int i=0;i<8;i++)
	{
	    int count=0;
	    for(int j=0;j<10;j++)
	    {
	        if(arr1[i][j]==arr2[j])
	        {
	            count++;
	        }
	    }
	    System.out.println("Correct answers of student" +i+ "is :"+count);
	}

	//Created by Manav_21CE063.
	    }
	}


