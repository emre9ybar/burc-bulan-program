# patika-hesap---makinesi
hesap makinesi 
package Ders1;

import java.util.Scanner;

public class ders2 {

    public static void main(String[] args) {

        Scanner scan = new Scanner(System.in);
       int n1 , n2 ,select ;

        System.out.print("ilk sayıyı giriniz : ");
        n1 = scan.nextInt();

        System.out.print("ikinci sayıyı giriniz : ");
        n2 = scan.nextInt();

        System.out.print("1-toplama\n2-çıkarma\n3-çarpma\n4-bölme\n");
        System.out.print("seçiminiz :");
        select = scan.nextInt();



        switch (n1&n2&select) {
            case 1 :
                boolean kosul =(1==select) ;
                System.out.println("toplama : "+(n1+n2) );
                break;

            case 2 :
                boolean kosul1 =(2==select) ;
                System.out.println("çıkarma : " +(n1-n2));

                break;

            case 3 :
                boolean kosul2 =(3==select);
                System.out.println("çarpma :"+(n1*n2));

                break;

            case 4 :
                boolean kosul3= (4==select);
                System.out.println("bölme : " +(n1/n2));

                break;

            default:
                System.out.println(("hatalı giriş yaptınız "));

                System.out.println();
        }
  }}
