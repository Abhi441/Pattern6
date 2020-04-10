# Pattern6
crux


import java.util.Scanner;

public class Test {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();
		int  nsp = 0;
		int nst = n;
		// row
		int row = 1;
		while (row <= n) {
        
			// work space 
			int csp = 1;
			while (csp <= nsp) {
				System.out.print(" ");
				csp++;
				
				//work stars
				int cst = 1;
				while(cst <= nst) {
					System.out.print("*");
					cst++;
					
				}
					
				// prep
				System.out.println();
				nsp = nsp + 2;
				nst = nst - 1;
				row = row + 1;
				}
						
			}
	}

}
