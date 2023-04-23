# CinZondagi
import java.util.Scanner;

public class CinZodyagi {
    public static void main(String[] args) {
    
        Scanner inp = new Scanner(System.in);
        System.out.println("Doğum Yılınızı Giriniz" );
        int yil = inp.nextInt();
        int kalan = yil % 12;
        switch (kalan) {
        
            case 0:
                System.out.println("Burcunuz: Maymun" );
                break;
            case 1:
                System.out.println("Burcunuz Horoz" );
                break;
            case 2:
                System.out.println("Burcunuz Köpek" );
                break;
            case 3:
                System.out.println("Burcunuz Domuz" );
                break;
            case 4:
                System.out.println("Burcunuz Maymun" );
                break;
            case 5:
                System.out.println("Burcunuz Fare" );
                break;
            case 6:
                System.out.println("Burcunuz Öküz" );
                break;
            case 7:
                System.out.println("Burcunuz Kaplan" );
                break;
            case 8:
                System.out.println("Burcunuz Tavşan" );
                break;
            case 9:
                System.out.println("Burcunuz Ejderha" );
                break;
            case 10:
                System.out.println("Burcunuz Yılan" );
                break;
            case 11:
                System.out.println("Burcunuz At" );
                break;
            case 12:
                System.out.println("burcunuz koyun");
        }

    }

}
