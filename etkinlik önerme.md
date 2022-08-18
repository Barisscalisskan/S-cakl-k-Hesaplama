package SınıfıGeçme;

import java.util.Scanner;

public class sicaklikhesaplama {

public static void main(String[] args) {

Scanner bar = new Scanner(System.in);

int hava;


System.out.print("Sıcaklık Değerini Giriniz :");
        
hava = bar.nextInt();

if (hava <= 5) {

if ((hava >= -100)) {
                
System.out.println("Kayak yapabilirsin.");
    } 

else if ((hava < -100)) {
                
System.out.println("Bu havada dışarı bile çıkma !!");
    }
    } 

else if (hava <= 25) {
            
if (hava >= 15) {
                
System.out.println("Piknige Gidebilirsin.");
    } 

else if ((hava < 15)) {
                
if (hava > 5) {
                    
System.out.println("Sinemaya gidebilirsin.");
        }
        }
        } 
        
else if ((hava > 25) && (hava <= 60)){

System.out.println("Yüzmeye gidebilirsin.");
        }
        
else {
            
System.out.println("Ekvator bölgesindesin sanırım");
        }
    }
}
