# Girilen-Say-dan-K-k-2-nin-Kuvvetlerini-Bulan-Program
Girilen Sayıdan Küçük 2’nin Kuvvetlerini Bulan Program

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int n;
        Scanner input = new Scanner(System.in);
        System.out.println( " Sınır sayısını giriniz: ");
        n = input.nextInt();

        for (int i = 1; i<=n; i*=4){
            System.out.println(i);
        } for (int i = 1; i <=n; i*=5){
            System.out.println(i);

        }


    }
}

































