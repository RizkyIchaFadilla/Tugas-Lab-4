# Tugas-Lab-4
package com.xsis.example;
import java.util.Scanner;

public class Main
{

    public static void main(String[] args)
    {
        Scanner baca = new Scanner(System.in);

            System.out.println("Masukan Nama Kota Pertama : ");
            String data1 = baca.nextLine();

            System.out.println("Masukan Nama Kota Kedua : ");
            String data2 = baca.nextLine();



        System.out.println("\nTampilan nama kota setelah di urutkan : ");
        if(data1.compareTo(data2) > 0){
            System.out.println(data2 +"\n" + data1);
        }
        else if(data1.compareTo(data2) < 0){
            System.out.println(data1 + "\n" + data2);
        }
    }
}
