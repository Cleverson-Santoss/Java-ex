**Faça um programa que peça as 4 notas bimestrais, calcule e imprima a média.**

```java
import java.util.Scanner;

public class ExemploInput {
    public static void main(String[] args) {
        // Cria um objeto Scanner para ler a entrada do teclado
        Scanner scanner = new Scanner(System.in);

        // Lê uma linha de texto (String)
        //System.out.print("Digite seu nome: ");
        //String nome = scanner.nextLine(); 

        // Lê um número inteiro
        System.out.print("Digite sua nota 01: ");
        float n1 = scanner.nextFloat();

        System.out.print("Digite sua nota 02: ");
        float n2 = scanner.nextFloat();

        System.out.print("Digite sua nota 03: ");
        float n3 = scanner.nextFloat();

        System.out.print("Digite sua nota 04: ");
        float n4 = scanner.nextFloat();
        
        float media = (n1 + n2 + n3 + n4) / 4;

        // Exibe os valores lidos
        System.out.println("Média: " + media);

        // Fecha o scanner para liberar os recursos
        scanner.close();
    }
}
```
**Faça um programa que leia três notas de um aluno, calcule e escreva a média final deste aluno. Considerar que a média é ponderada e que o peso das notas é 2, 3 e 5.**

```java
import java.util.Scanner;

public class ExemploInput {
    public static void main(String[] args) {
        // Cria um objeto Scanner para ler a entrada do teclado
        Scanner scanner = new Scanner(System.in);

       
        System.out.print("Digite sua nota 01: ");
        float n1 = scanner.nextFloat();

        System.out.print("Digite sua nota 02: ");
        float n2 = scanner.nextFloat();

        System.out.print("Digite sua nota 03: ");
        float n3 = scanner.nextFloat();
        
        float media = ((n1 * 2) + (n2 * 3) + (n3 * 5)) / 10; 

        System.out.println("Média: " + media);

        scanner.close();
    }
}
```
**Faça um programa para calcular a área de uma circunferência, considerando a fórmula AREA = π × RAIO2. Utilize as variáveis AREA e RAIO, a constante π (pi = 3,14159) e os operadores aritméticos de multiplicação.**

```java
import java.util.Scanner;

public class ExemploInput {
    public static void main(String[] args) {
        // Cria um objeto Scanner para ler a entrada do teclado
        Scanner scanner = new Scanner(System.in);

        double pi = Math.PI;
        
        System.out.print("Digite o raio : ");
        float raio = scanner.nextFloat();

        double area = pi * (raio * raio); // Fórmula que calcula a área 
        

        System.out.printf("Area: %.2f", area); //%.2f utilizado para formatação de dois números após a vírgula

        scanner.close();
    }
}
```
**Faça um programa que: Leia o nome, Leia o sobrenome, Concatene o nome com o sobrenome e Apresente o nome completo.**

```java
import java.util.Scanner;

public class ExemploInput {
    public static void main(String[] args) {
        // Cria um objeto Scanner para ler a entrada do teclado
        Scanner scanner = new Scanner(System.in);

        double pi = Math.PI;
        
        System.out.print("Digite o primeiro nome : ");
        String nome = scanner.nextLine();

        System.out.print("Digite o primeiro nome : ");
        String sobrenome = scanner.nextLine();

        String completo = nome + " " + sobrenome; 
        

        System.out.println(completo); 

        scanner.close();
    }
}
```
