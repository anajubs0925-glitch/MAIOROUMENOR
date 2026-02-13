import java.util.Scanner;

public class SomaOuSubtracao {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n1, n2;

        System.out.print("Digite o primeiro número: ");
        n1 = sc.nextInt();

        System.out.print("Digite o segundo número: ");
        n2 = sc.nextInt();

        if (n2 > n1) {
            System.out.println("Soma: " + (n1 + n2));
        } else if (n1 > n2) {
            System.out.println("Subtração: " + (n1 - n2));
        } else {
            System.out.println("Os números são iguais.");
        }

        sc.close();
    }
}
