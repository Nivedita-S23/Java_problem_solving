import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc = new Scanner(System.in);
	    int n = sc.nextInt();
	    int count = 0;
	    
	    for(int target=2 ; target<=n ;target++)
	    {
	    int flag = 0;
	    
	    for(int i=2 ; i<=target/2 ; i++)
	    {
	        count++;
	        if(target%i==0)
	        {
	            flag = 1;
	            break;
	        }
	    }
	    if(flag ==0)
	      System.out.print(target +" ");
	    
	     
	    }
	    System.out.println("\ncount = "+count);
	  
	}
}
