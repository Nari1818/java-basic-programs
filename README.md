# java-basic-programs
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner s=new Scanner(System.in);
		
		int a =s.nextInt();
	    int	c=0;
		
		for(int i=1;i<=a;i++){
		   if( a%i==0 ){
		    c++;
		   }  
		}
		if(c == 2){
		    System.out.println("prime");
		}
		else{
		    System.out.println("not prime");
		}
}
}

import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	   Scanner s=new Scanner(System.in);
	   int n=s.nextInt();
	   int[] arr =new int[n-1];
	   
	   int sum1=0;
	   int sum2=0;
	   for(int i=0;i<n;i++){
	       arr[i] = s.nextInt();
	   }
	   for(int j=0;j<(arr.length);j++){
	       sum1 += arr[j];
	   }
	   for(int k=arr[0];k<(arr.length-1);k++){
            sum2=sum2+arr[k];
	   }
	   int sum =sum2 - sum1;
	   System.out.println(sum);
	}
}




import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    Scanner s =new Scanner(System.in);
		int n=s.nextInt();
		int a=0;
		int b=1;
		System.out.print(a+" "+b);
		int sum=0;
		for(int i=2;i<n;i++){
		    sum=a+b;
		    System.out.print(" " +sum);
		    a=b;
		    b=sum;
		    }
	}
	
	   
}


import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
	int a=s.nextInt();
	int b=s.nextInt();
	int temp;
	temp=a;
	a=b;
	b=temp;
	System.out.println(a);
	System.out.println(b);
	
	}
}


import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	Scanner s= new Scanner(System.in);
	int a=s.nextInt();
	int mult=1;
	for(int i=1;i<=a;i++){
	 mult *=i;   
	}
    System.out.print(mult);
	
	}
}


import java.util.Scanner;
import java.util.Arrays;
public class Main
{
	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		    int n = s.nextInt();
            int[] arr = new int[n];
            for (int i = 0; i < n; i++) {
            arr[i] = s.nextInt();
        }
        Arrays.sort(arr);
        for (int i = 0; i < n; i++) {
            System.out.print(arr[i]+" ");
        }

		
	}
}
