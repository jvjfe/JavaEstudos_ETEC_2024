package MediaEscolar2;

import java.util.Scanner;

public class MediaEscolar2 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        System.out.print("Digite a nota do 1º bimestre: ");
        double nota1 = sc.nextDouble();
        
        System.out.print("Digite a nota do 2º bimestre: ");
        double nota2 = sc.nextDouble();
        
        System.out.print("Digite a nota do 1º trabalho: ");
        double trabalho1 = sc.nextDouble();
        
        System.out.print("Digite a nota do 2º trabalho: ");
        double trabalho2 = sc.nextDouble();
        
        System.out.print("Digite o percentual de presença: ");
        double percentualPresenca = sc.nextDouble();
        
        sc.close();
        
        double media = (nota1 + nota2 + trabalho1 + trabalho2) / 4;

        String resultado;
        if (media >= 7 && percentualPresenca >= 75) {
            resultado = "Aprovado";
        } else {
            resultado = "Reprovado";
        }

        System.out.printf("Média: %.2f (%s)%n", media, numeroPorExtenso((int) media));
        System.out.printf("Percentual de Presença: %.2f%%%n", percentualPresenca);
        System.out.println("Resultado: " + resultado);
    }
    
    private static String numeroPorExtenso(int numero) {
        if (numero == 0) return "zero";
        if (numero == 1) return "um";
        if (numero == 2) return "dois";
        if (numero == 3) return "três";
        if (numero == 4) return "quatro";
        if (numero == 5) return "cinco";
        if (numero == 6) return "seis";
        if (numero == 7) return "sete";
        if (numero == 8) return "oito";
        if (numero == 9) return "nove";
        if (numero == 10) return "dez";
        return "fora do intervalo suportado";
    }
}
