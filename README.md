#FindPrimeNumber
package Mth;

public class FindPrimeNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int LIMIT = 100;
		
		
		for(int i = 2; i<LIMIT; i++){
			if(isPrime(i)){
				System.out.print(i + ", ");
			}
				
		}
}

	public static boolean isPrime(int number){
		
		for(int i = 2; i<number; i++){
			
			if(number % i== 0){
				
				return false;
			}
			
		}
		
		return true;
		
		
	}
	
		
}
