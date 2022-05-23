# temperature
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int heat;
        Scanner input = new Scanner(System.in);
        System.out.println("Sıcaklık degerini giriniz : ");
        heat = input.nextInt();
        if(heat<5){
            System.out.println("Kayak");
        } else if(heat>=5 && heat<15) {
            System.out.println("sinemaya gidebilirsi");
        } else if ( heat>=15 && heat<=25 ){
            System.out.println("piknik");
        } else {
            System.out.println("Yüzme");
        }
    }
}
