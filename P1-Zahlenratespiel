import java.util.Scanner;

public class Zahlenratespiel {

	public static void main(String[] args) {

		System.out.printf("Zahlenratespiel");
	    Scanner myScanner = new Scanner(System.in);
	    
	    int randomInt = (int)(Math.random()*100);
	    
	    System.out.println("Bitte raten!");
	    
	    int einInteger = myScanner.nextInt();
	    
	    System.out.print("Ein Integer:" + einInteger);
	   
	    if (randomInt == einInteger) {
	    	System.out.println("Sie haben die Zufällige Zahl erraten!");	
	    }
	  	
	    while(randomInt != einInteger) {
	    	
	    if (randomInt >= einInteger) {
	    	System.out.println("Die angegebene Zahl ist kleiner als die Zufallszahl!");
	    } else (einInteger >= randomInt) {
	    	System.out.println("Die angegebene Zahl ist größer als die Zufallszahl!");
	    }
	}
}
}
