# Daire-diliminin-alan-hesaplama-programi
Java101_4  daire diliminin alanını hesaplayan program
/* Ödev Patika.dev
Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulan programı yazınız.

𝜋 sayısını = 3.14 alınız.

Formül : (𝜋 * (r*r) * 𝛼) / 360 */

import java.util.Scanner ;

public class Main {
    public static void main (String[] args) {
        int r, a ;
        double alan, pi=3.14 ;
    
        Scanner input=new Scanner(System.in);
        System.out.print("Dairenin yarı çapını giriniz :");
        r=input.nextInt();
        System.out.print("Dairenin merkez açı ölçüsünü giriniz :");
        a=input.nextInt();
        
        alan=(pi*(r*r)*a/360) ;
        
        System.out.print("Daire diliminin alanı :" +alan);

        
    }    
    
    
}
