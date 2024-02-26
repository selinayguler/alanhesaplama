# alanhesaplama
package patika;
import java.util.Scanner;



public class alanhesaplama {

	public static void main(String[] args) {
		double a , b , c , u, alan ;
		Scanner girdi = new Scanner(System.in);
		System.out.println("Birinci kenarı yazınız: ");
		a = girdi.nextDouble();
		System.out.println("İkinci kenarı yazınız: ");
		b = girdi.nextDouble();
		System.out.println("Üçüncü kenarı yazınız: ");
	    c = girdi.nextDouble();
        u = ((a+b+c)/2);
        System.out.println("u değeri : " + u);
        alan = Math.sqrt(u*(u-a)*(u-b)*(u-c));
        System.out.println("Alan değerim : " + alan);
        
        
	}

}
