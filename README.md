# Convert-into-binary
How to convert a value from Decimal to binary in Java

package text1;
import java.util.Scanner;
public class Aclass {

	 static void binary(int x){
		 int binary[]=new int [40];
		 int index = 0;
		 
		while(x>0){
			 binary[index]=x%2;
			 x=x/2;
			 index++;
			 
		 }
			 for(int i = index-1 ; i>=0 ; i--){
				 System.out.print(binary[i]);
			 }                                    
	 }
 
	public static void main(String[] args) {
		Scanner a = new Scanner(System.in);
		int z=a.nextInt();
		System.out.println("hello world !");
		binary (z);

	}

} 
