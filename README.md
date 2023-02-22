# EbobEkok
www.patika.dev
--------------


import java.util.Scanner;

public class EbobEkok {
	
	public static void main(String[] args) {

	    Scanner scanner = new Scanner(System.in);

	    int sayi1, sayi2, ebob = 1, ekok;

	    System.out.print("İlk sayıyı giriniz: ");
	    sayi1 = scanner.nextInt();

	    System.out.print("İkinci sayıyı giriniz: ");
	    sayi2 = scanner.nextInt();

	    int i = 1;

	    while (i <= sayi1 && i <= sayi2) {
	        if (sayi1 % i == 0 && sayi2 % i == 0) {
	            ebob = i;
	        }
	        i++;
	    }

	    ekok = (sayi1 * sayi2) / ebob;

	    System.out.println(sayi1 + " ve " + sayi2 + " sayılarının EBOB değeri: " + ebob);
	    System.out.println(sayi1 + " ve " + sayi2 + " sayılarının EKOK değeri: " + ekok);

	}
	}
