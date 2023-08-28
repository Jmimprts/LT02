# LT02
Respostas Atividade "Lista Erlon" 2

/* Quest 1 Segunda lista

import java.util.Scanner;

public class Jm {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Digite o primeiro numero");
        double num1 = scanner.nextDouble();
        System.out.println("Digite o segundo numero");
        double num2 = scanner.nextDouble();

        if (num1 > num2) {
            System.out.println("O maior numero e  " + num1);
        }   else if (num2 > num1){
            System.out.println("O maior numero e  " + num2);
        }
        }
    }
 */
/* Quest 2
import java.util.Scanner;
public class Jm {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
    System.out.println("Digite um valor");
    Double valor = scanner.nextDouble();
     if (valor > 0){
        System.out.println("O valor e positivo");
    } else if (valor < 0){
        System.out.println("O valor e negativo");
        }
    }
}
 */

/* Questão 3 import java.util.Scanner;
public class Jm {
    public static void main(String[]args) {
        Scanner scanner = new Scanner((System.in));
        System.out.println("Digite a primeira nota");
        Double nota1 = scanner.nextDouble();

        System.out.println("Digite a segunda nota");
        Double nota2 = scanner.nextDouble();

        System.out.println("Digite a terceira nota");
        Double nota3 = scanner.nextDouble();

        Double media = nota1 + nota2 / 2;

        if (media == 10) {
            System.out.println("Aprovado com Distinção");
        } else if (media >= 7) {
            System.out.println("Aprovado");
        } else {
            System.out.println("Reprovado");
        }

    }
}
 */

/* Quest 4
import java.util.Scanner;

public class Jm {
    public static void main(String[] args) {
        Scanner scanner = new Scanner((System.in));

        System.out.print("Digite o primeiro numero");
        Double num1 = scanner.nextDouble();

        System.out.print("Digite o segundo numero");
        Double num2 = scanner.nextDouble();

        System.out.print("Digite o terceiro numero");
        Double num3 = scanner.nextDouble();

        double maiorNumero = num1;

        if (num2 > maiorNumero) {
            maiorNumero = num2;
        }
        if (num3 > maiorNumero) {
            maiorNumero = num3;
        }

        System.out.println("O maior número é: " + maiorNumero);
    }
}
 */

/* Quest 5
import java.util.Scanner;

public class Jm {
    public static void main(String[] args) {
        Scanner scanner = new Scanner((System.in));

        System.out.print("Digite o primeiro numero");
        Double num1 = scanner.nextDouble();

        System.out.print("Digite o segundo numero");
        Double num2 = scanner.nextDouble();

        System.out.print("Digite o terceiro numero");
        Double num3 = scanner.nextDouble();

        double menorNumero = num1;

        if (num2 < menorNumero) {
            menorNumero = num2;
        }
        if (num3 < menorNumero) {
            menorNumero = num3;
        }

        System.out.println("O menor número é: " + menorNumero);
    }
}
/*
import java.util.Scanner;
public class Quest6Lista2 {
    public static void main(String[] args) {

        Scanner turno = new Scanner(System.in);

        System.out.println("Em que turno voce estuda?");
        System.out.println("M - Matutino");
        System.out.println("V - Vespertino");
        System.out.println("N - Noturno");

        System.out.println("Digite a letra conforme a opçao escolhida:");
        char letra = turno.next().charAt(0);

        if(letra == 'M' || letra == 'm') {
            System.out.println("Bom dia!");
        } else if(letra == 'V' || letra == 'v'){
            System.out.println("Boa tarde!");
        } else if(letra =='N' || letra == 'n'){
            System.out.println("Boa noite!");
        }
    }

/*Quest 7
import java.util.Scanner;

public class Jm{
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double salario = scanner.nextDouble();

        double percentualAumento = 0;
        double valorAumento = 0;

        if (salario <= 280) {
            percentualAumento = 20;
        } else if (salario <= 700) {
            percentualAumento = 15;
        } else if (salario <= 1500) {
            percentualAumento = 10;
        } else {
            percentualAumento = 5;
        }
        valorAumento = (percentualAumento / 100) * salario;
        double novoSalario = salario + valorAumento;

        System.out.println("Salário antes do reajuste: R$" + salario);
        System.out.println("Percentual de aumento aplicado: " + percentualAumento + "%");
        System.out.println("Valor do aumento: R$" + valorAumento);
        System.out.println("Novo salário após o aumento: R$" + novoSalario);
    }
}
 */

// OBS NÃO FIZ A QUESTÃO 6 SO FIZ A 1 2 3 4 5 7 A QUESTÃO 6 E DA 8 ATE A 20 NÃO ENTENDI
// IREI TREINAR E TENTAR FAZER POIS NAO CONSEGUI

