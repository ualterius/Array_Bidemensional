# Array_Bidemensional
Programas en Java

public class array_Bidimensional_II {

	public static void main(String[] args) {
		
		
int intermedio=3;
		int acum;
		int doble = 2;
		int [][]array= new int[5][4];
		
		for (int i=0;i<5;i++){
			acum=5;
array[i][0]=5;
		
			for(int j=0;j<4;j++){	
		
			acum=acum*doble+intermedio;
			array[i][j]=acum;
		}
			intermedio=(intermedio+3);
		}
			for(int []f: array){
		
			
			System.out.println();
	for(int z:f){
	
				System.out.print(z+" ");
			}}
	}

}
