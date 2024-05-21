package Exercise;
import java.util.Scanner;
public class kdvTutar {

	public static void main(String[] args) {
		
		Scanner input =new Scanner(System.in);
		
		double urunFıyat,kdvOran,kdvsızFıyat;
		
		System.out.print("Lütfen ürün fiyatını giriniz :" );
		urunFıyat =input.nextDouble();
		
		
	    System.out.println("KDV'li Fiyat :" + urunFıyat);
	
		kdvOran = 0.18;
		System.out.println("Ürünün KDV oranı :" + kdvOran);
		
		kdvsızFıyat =urunFıyat - ( urunFıyat * kdvOran );
		System.out.println("KDV'siz fiyat :" + kdvsızFıyat);
		
		System.out.println("KDV tutar :" + ( urunFıyat - kdvsızFıyat) );
		
		
		
		
		

		
		


