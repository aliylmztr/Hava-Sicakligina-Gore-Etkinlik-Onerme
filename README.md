# Hava-Sicakligina-Gore-Etkinlik-Onerme
Java Hava Sicakligina Gore Etkinlik Onerme

www.patika.dev

import java.util.Scanner;

public class Main {
    
    public static void main(String[] args) {

        int temperature;

        Scanner input = new Scanner(System.in);
        System.out.print("Sıcaklık Değerini Giriniz :");
        temperature = input.nextInt();

        if (temperature < 5) {
            System.out.println("Kayak yapabilirsiniz.");
        } else if (temperature >= 5 && temperature <= 15) {
            System.out.println("Sinemaya gidebilirsiniz.");
        } else if (temperature > 15 && temperature <= 25) {
            System.out.println("Pikniğe gidebilirsiniz.");
        } else {
            System.out.println("Yüzmeye gidebilirsiniz.");
        }
    }
}
