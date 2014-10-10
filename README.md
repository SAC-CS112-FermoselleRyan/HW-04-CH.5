HW-04-CH.5
==========
Ryan Fermoselle


import java.io.BufferedReader;
import java.io.InputStreamReader;



public class shapes {

	//A)
	public static void main(String[] args) throws Exception {
		
		
		BufferedReader reader = new BufferedReader (new InputStreamReader(System.in));
		System.out.println("Enter size");
		int size = Integer.parseInt(reader.readLine());
	
	
		for(int i=1;i<=size;i++)
		{
			for(int j=1;j<=size;j++)
			{
				if(j<=i)
				System.out.print("*");
				
			}
			
			System.out.println();
			
			
		}
			
		
		System.out.print("*");
	
		
		
	}
	
}


//B)
public class Shape2 {

	public static void main(String[] args) throws Exception {
		
		int size =5;
		for(int i=1;i<=size;i++)
		{
		for(int j=size;j>=1;j--)
		{
			
			
			if(j>=i)
			System.out.print("*");
			
		}
		
		}
		System.out.println();
		
	}
	
}



//C)
public class Shape3 {

	public static void main(String[] args){
		
		int size=5;
		
		for(int i=1;i<=size;i++){
			for (int j = 1; j <= size; j++){
				if (j < i) {
					System.out.print("");
				} else{
					
					System.out.print("*");
					
				}
				
				}
			
			System.out.println();	
				
			}
			
		}		





//D)

public class Shape4 {



	public static void main(String[] args){

		

		int size=9;

		for(int i=1;i<size;i++)

		{

			for(int j=size; j>=1;j--){

				

				if(j>i)

					System.out.print("");

				else

					System.out.print("*");

					

				

				

			}

			

			System.out.println();

			

			

		}

		

		

		

		

		

		

		

		

		

	}

	

	

	

	

}


5.15
