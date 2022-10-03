# Dik-Ucgende-Hipotenus-Bulma
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class HipotenusBulma {
    public static void main(String[] args) {
        double a,b,c;
        Scanner input = new Scanner (System.in);
        System.out.print("Birinci Dik Kenarı Giriniz:");
        a = input.nextDouble();
        System.out.print("İkinci Dik Kenarı Giriniz:");
        b = input.nextDouble();
        c = Math.sqrt(a*a + b*b);
        System.out.print("Hipotenüs:"+c);
    }
}
```
