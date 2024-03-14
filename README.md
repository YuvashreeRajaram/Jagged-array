# Jagged-array


import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();//3
	    int a[][]=new int[n][];
	    for(int i=0;i<n;i++)
	    {
	           a[i]=new int[sc.nextInt()];}//2
	          for(int i=0;i<a.length;i++){
	        for(int j=0;j<a[i].length;j++)
	        {
	        a[i][j]=sc.nextInt();
	    }
	}
	for(int i=0;i<a.length;i++){
	    for(int j=0;j<a[i].length;j++){
	        System.out.print(a[i][j]+" ");
	    }
	    System.out.println();
	}
	}
}

