# Java-Proz
Exercícios realizados durante a disciplina 'Desenvolvimento de Aplicações', ministrada no curso de _Desenvolvimento de Sistemas_ da Escola Proz

<hr>

### **Variáveis + Inputs e Outputs + Operadores + Métodos em Strings**

**Q1.** Crie um programa cujo objetivo é inserir seus dados pessoais (nome, idade, gênero e cidade) e armazenar em cada variável determinada e depois exibidos na tela.
```

```
**Q2.** Dado o cálculo 12 x 3 + 4 - 8 / 2 % 3, qual o resultado segundo a precedência de operadores?
```

```
**Q3.** Crie um programa que utilize os métodos de Strings, onde o usuário envia uma frase e o programa exibe as informações dessa frase (tamanho, letra maiúscula, letra minúscula, substring e index).
```

```
**Q1.** Explique como criar um diretório para projetos Java e quais são as Convenções para sua criação. Envie os prints do passo a passo.
```

```
**Q2.** Explique o que é e dê um exemplo de uma Classe em Java e quais são as Convenções para sua declaração.
```

```
**Q3.** Explique o que é e dê um exemplo de um Método em Java e quais são as Convenções para sua declaração.
```

```
**Q4.** Quais são as Convenções para a declaração de uma variável em Java?
```

```
**Q5.** Envie um programa com a classe "Variáveis" que imprima 4 variáveis:
* Uma variável do tipo Texto
* Uma variável do tipo Número Inteiro
* Uma variável do tipo Número Decimal (ou ponto flutuante)
* Uma variável do tipo Lógica
```
public class Variaveis {
    public static void main(String[] args) {
        // Variável do tipo Texto
        String texto = "Marcos Vinicius";

        // Variável do tipo Número Inteiro
        int numeroInteiro = 17;

        // Variável do tipo Número Decimal
        double numeroDecimal = 1.75;

        // Variável do tipo Lógica
        boolean logica = false;

        // Impressão das variáveis
        System.out.println("Nome: : " + texto);
        System.out.println("Idade: " + numeroInteiro);
        System.out.println("Altura: " + numeroDecimal);
        System.out.println("Possui CNH? : " + logica);
    }
}


```
**Q6.** Para cada Operação abaixo, crie um programa que leia dois valores enviados pelo usuário, faça a operação indicada e retorne o valor final.
* Soma
* Subtração
* Multiplicação
* Divisão
* Módulo
* Concatenação
```

```
**Q7.** Crie um programa que utilize os métodos de Strings, onde o usuário envia uma frase e o programa exiba as informações dessa frase (tamanho, letra maiúscula, letra minúscula, substring e index).
```

```
**Q8.** Crie um programa que utilize os métodos de Matemática, onde o usuário envia uma número decimal x e o programa exiba o valor absoluto de x e o quadrado  de x.
```

```
**Q9.** Crie um programa que retorne um número aleatório.
```

```
**Q10.** Crie um programa com operadores lógicos e relacionais.
```

```

### **Controle de Fluxo - Condicionais + Laços de Repetição**

**Q1.** Desenvolva um programa utilizando uma condicional simples.
```
![1 dox](https://github.com/user-attachments/assets/32b728bd-4ba4-4964-8e23-eb542121e569)

```
**Q2.** Desenvolva um programa qualquer utilizando a condicional composta.
```

```
**Q3.** Desenvolva um programa qualquer utilizando a condicional ternária.
```

```
**Q4.** Desenvolva um programa que pede para o usuário digitar o dia da semana. Se for sábado ou domingo, deve aparecer a mensagem "descanso", senão, deve aparecer a mensagem "estudar".
```

```
**Q5.** Desenvolva um programa onde o usuário informa um número de 1 a 12 e retorna o mês correspondente.
```
import java.util.Scanner;

public class exercicefive {
    public static void main(String[] args) {
        Scanner entradaDados = new Scanner(System.in);
        System.out.println("Digite um número de 0-12:");
        String mes = entradaDados.nextLine();
        
        switch (mes) {
            case "1":
              System.out.println("Janeiro");  
              break;
              
            
            case "2":
              System.out.println("Fevereiro");  
              break;

            case "3":
              System.out.println("Março");  
              break;  
              
            case "4":
              System.out.println("Abril");  
              break;
            
            case "5":
              System.out.println("Maio");  
              break;  
              
            case "6":
              System.out.println("Junho");  
              break;  
              
            case "7":
              System.out.println("Julho");  
              break;  
              
            case "8":
              System.out.println("Agosto");  
              break;
              
            case "9":
              System.out.println("Setembro");  
              break;
              
            case "10":
              System.out.println("Outubro");  
              break; 
              
            case "11":
              System.out.println("Novembro");  
              break;  
              
            case "12":
              System.out.println("Dezembro");  
              break;  
              
              default:
              System.out.println("Mês Inválido.");  
              break;
        }
    
        entradaDados.close();
    
    
   
   
    }

}
```
**Q6.** Desenvolva um programa que pede as notas 1, 2 e 3 com pesos 2, 3 e 5, respectivamente, do aluno e faça o cálculo da média. Dependendo da nota, o programa retorna a seguinte mensagem:
* se a media for entre 0.0 e 4.9: reprovado
* se a media for entre 5.0 e 7.9: em recuperação
* se a media for entre 8.0 e 10.0: aprovado
```

```
**Q7.** Crie um laço de repetição com que exiba os com os números de 1 até 10 em ordem crescente e depois em ordem decrescente.
```

```
**Q8.** Crie um laço de repetição que exiba os com os números pares de 10 até 50 em ordem crescente e depois em ordem decrescente.
```

```
**Q9.** Utilizando um laço de repetição, desenvolva um programa que exiba a tabuada de 1 a 10. Para isso, peça para o usuário escolher um número de 1 a 10. Se o usuário digitar um valor fora desse intervalo, deve aparecer a seguinte mensagem de erro: “Digite um valor entre 1 e 10.” A tela esperada deve conter os valores da tabuada para o número digitado pelo usuário.
```

```

### **Vetores e Matrizes**

**Q1.** Crie um programa que leia um vetor de números inteiros e exiba a soma de todos os elementos.
```
import java.util.Scanner;
public class Q1 {

    public static void main(String[] args) {
       
        Scanner scanner = new Scanner(System.in);

        // Lê o tamanho do vetor
        System.out.print("Digite o tamanho do vetor: ");
        int tamanho = scanner.nextInt();

        // Declara o vetor
        int[] numeros = new int[tamanho];

        // Lê os elementos do vetor
        System.out.println("Digite os elementos do vetor:");
        for (int i = 0; i < tamanho; i++) {
            numeros[i] = scanner.nextInt();
        }

        // Calcula a soma dos elementos
        int soma = 0;
        for (int num : numeros) {
            soma += num;
        }

        // Exibe a soma
        System.out.println("A soma dos elementos do vetor é: " + soma);

        // Fecha o scanner
        scanner.close();
    }
}
    
```
**Q2.** Faça um programa que leia um vetor de números inteiros e exiba o maior elemento presente no vetor.
```
import java.util.Scanner;
public class Q2 {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Lê o tamanho do vetor
        System.out.print("Digite o tamanho do vetor: ");
        int tamanho = scanner.nextInt();

        // Declara o vetor
        int[] numeros = new int[tamanho];

        // Lê os elementos do vetor
        System.out.println("Digite os elementos do vetor:");
        for (int i = 0; i < tamanho; i++) {
            numeros[i] = scanner.nextInt();
        }

        // Inicializa a variável maior com o primeiro elemento do vetor
        int maior = numeros[0];

        // Encontra o maior elemento
        for (int i = 1; i < tamanho; i++) {
            if (numeros[i] > maior) {
                maior = numeros[i];
            }
        }

        // Exibe o maior elemento
        System.out.println("O maior elemento do vetor é: " + maior);

        // Fecha o scanner
        scanner.close();
    }

}
```
**Q3.** Faça um programa que leia um vetor de números inteiros e exiba a média dos elementos.
```
import java.util.Scanner;
public class Q3 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Lê o tamanho do vetor
        System.out.print("Digite o tamanho do vetor: ");
        int tamanho = scanner.nextInt();

        // Declara o vetor
        int[] numeros = new int[tamanho];

        // Lê os elementos do vetor
        System.out.println("Digite os elementos do vetor:");
        int soma = 0; // Variável para armazenar a soma dos elementos
        for (int i = 0; i < tamanho; i++) {
            numeros[i] = scanner.nextInt();
            soma += numeros[i]; // Calcula a soma dos elementos
        }

        // Calcula a média dos elementos
        double media = (double) soma / tamanho;

        // Exibe a média
        System.out.println("A média dos elementos do vetor é: " + media);

        // Fecha o scanner
        scanner.close();
    }
    }
```
**Q4.** Crie um programa que leia um vetor de números inteiros e verifique se todos os elementos são pares.
```
import java.util.Scanner;

public class Q4 {

    public static void main(String[] args) {
       Scanner scanner = new Scanner(System.in);

        // Lê o tamanho do vetor
        System.out.print("Digite o tamanho do vetor: ");
        int tamanho = scanner.nextInt();

        // Declara o vetor
        int[] numeros = new int[tamanho];

        // Lê os elementos do vetor
        System.out.println("Digite os elementos do vetor:");
        for (int i = 0; i < tamanho; i++) {
            numeros[i] = scanner.nextInt();
        }

        // Verifica se todos os elementos são pares
        boolean todosPares = true;
        for (int num : numeros) {
            if (num % 2 != 0) {
                todosPares = false;
                break; // Sai do laço ao encontrar o primeiro ímpar
            }
        }

        // Exibe o resultado
        if (todosPares) {
            System.out.println("Todos os elementos são pares.");
        } else {
            System.out.println("Nem todos os elementos são pares.");
        }

        // Fecha o scanner
        scanner.close();
    }
}
 
```
**Q5.** Faça um programa que leia duas matrizes 2x2 e exiba a soma das duas matrizes.
```
import java.util.Scanner;
public class Q5 {
    
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Declara duas matrizes 2x2
        int[][] matriz1 = new int[2][2];
        int[][] matriz2 = new int[2][2];
        int[][] matrizSoma = new int[2][2];

        // Lê os elementos da primeira matriz
        System.out.println("Digite os elementos da primeira matriz 2x2:");
        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++) {
                matriz1[i][j] = scanner.nextInt();
            }
        }

        // Lê os elementos da segunda matriz
        System.out.println("Digite os elementos da segunda matriz 2x2:");
        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++) {
                matriz2[i][j] = scanner.nextInt();
            }
        }

        // Calcula a soma das duas matrizes
        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++) {
                matrizSoma[i][j] = matriz1[i][j] + matriz2[i][j];
            }
        }

        // Exibe a soma das matrizes
        System.out.println("A soma das duas matrizes é:");
        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++) {
                System.out.print(matrizSoma[i][j] + " ");
            }
            System.out.println(); // Pula para a próxima linha
        }

        // Fecha o scanner
        scanner.close();
    }
    }
```

### **Projetos POO - Programação Orientada a Objetos**

:brain: _Calculadora:_ Crie uma calculadora simples que realiza operações aritméticas básicas (adição, subtração, multiplicação e divisão).
```
import java.util.Scanner;
public class calculadora {

    public static void main(String[] args) throws Exception {
        
        //Boas vindas ao usuário.
        System.out.println("Seja bem vindo a calculadora!\n");
        System.out.println("Escolha uma das quatros operações abaixo:\n");
        System.out.println("1- Adição\n2- Subtração\n3- Multiplicação\n4- Divisão\n");

        //Criando escanner.
        Scanner input = new Scanner(System.in);
        
        int calculo = input.nextInt();

        System.out.println("calculo = " + calculo );
        System.out.println("Digite o primeiro número:\n");
        int num1 = input.nextInt();
        System.out.println("Digite o segundo número:\n");
        int num2 = input.nextInt();
        int result = num1 - num2;
        int resulta = num1 + num2;
        switch (calculo) {
        
        //Adição.
        case 1:
        
        System.out.println("O resultado da Adição é:" + resulta);
            
            break;
    
               
        //Subtração.
        case 2:
        
        System.out.println("O resultado da subtração é:" + result);
                
            break;
        
         //Multiplicação.    
        case 3:
        
        System.out.println("O resultado da Multiplicação é:" + num1 * num2);
                
            break;
        
        

        //Divisão
        case 4:
        
        System.out.println("O resultado da Divisão é:" + num1 / num2);
                
            break;
        
        default:
        System.out.println("opção inválida, Digite algo correspondente.");
            break;  
    }
    
    input.close();
    
    }
    
}
```
:brain: _Conversor de unidades:_ Desenvolva um programa que converta unidades de medida como temperatura (Celsius para Fahrenheit e vice-versa) e distância (metros para quilômetros e vice-versa).
```
import java.util.Scanner;

public class conversor_unidades {

    // Método para converter Celsius para Fahrenheit
    public static double celsiusParaFahrenheit(double celsius) {
        return (celsius * 9/5) + 32;
    }

    // Método para converter Fahrenheit para Celsius
    public static double fahrenheitParaCelsius(double fahrenheit) {
        return (fahrenheit - 32) * 5/9;
    }

    // Método para converter Metros para Quilômetros
    public static double metrosParaQuilometros(double metros) {
        return metros / 1000;
    }

    // Método para converter Quilômetros para Metros
    public static double quilometrosParaMetros(double quilometros) {
        return quilometros * 1000;
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.println("Conversor de Unidades");
        System.out.println("Escolha a conversão:");
        System.out.println("1. Celsius para Fahrenheit");
        System.out.println("2. Fahrenheit para Celsius");
        System.out.println("3. Metros para Quilômetros");
        System.out.println("4. Quilômetros para Metros");
        int escolha = scanner.nextInt();

        double valorEntrada;
        double valorConvertido;

        switch (escolha) {
            case 1:
                System.out.print("Digite a temperatura em Celsius: ");
                valorEntrada = scanner.nextDouble();
                valorConvertido = celsiusParaFahrenheit(valorEntrada);
                System.out.println("Temperatura em Fahrenheit: " + valorConvertido);
                break;
            case 2:
                System.out.print("Digite a temperatura em Fahrenheit: ");
                valorEntrada = scanner.nextDouble();
                valorConvertido = fahrenheitParaCelsius(valorEntrada);
                System.out.println("Temperatura em Celsius: " + valorConvertido);
                break;
            case 3:
                System.out.print("Digite a distância em metros: ");
                valorEntrada = scanner.nextDouble();
                valorConvertido = metrosParaQuilometros(valorEntrada);
                System.out.println("Distância em quilômetros: " + valorConvertido);
                break;
            case 4:
                System.out.print("Digite a distância em quilômetros: ");
                valorEntrada = scanner.nextDouble();
                valorConvertido = quilometrosParaMetros(valorEntrada);
                System.out.println("Distância em metros: " + valorConvertido);
                break;
            default:
                System.out.println("Escolha inválida.");
        }

        scanner.close();
    }
}
```
:brain: _Jogo de adivinhação:_ Crie um jogo onde o computador escolhe um número aleatório entre 1 e 100 e o usuário tenta adivinhá-lo. O programa deve fornecer dicas como "é maior" ou "é menor".
```

```
:brain: _Gerador de senhas:_ Crie um programa onde o usuário informa a quantidade de caracteres e o programa gere uma senha aleatória que possua letras maiúsculas, letras minúsculas, números e caracteres especiais.
```
import java.util.Random;
import java.util.Scanner;

public class gerador_senha {
public static void main (String[]args){
    Scanner input = new Scanner(System.in);

    System.out.println("Informe o tamanho da sua senha:");
    int comprimento = input.nextInt();
    String caracteres = "ABCDEFGHIGKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789!@#$%&*/";

    StringBuilder senha = new StringBuilder();
    Random random = new Random();
    for (int i = 0; i < comprimento; i++) {
        int indice = random.nextInt(caracteres.length());
        senha.append(caracteres.charAt(indice));
    }
    System.out.println("Senha gerada!:" + senha.toString());
    input.close();

}

```
:brain: _SmartTv:_ Crie um sistema de uma SmartTv, onde o usuário pode realizar as seguintes tarefas:
* Ligar e Desligar a Tv
* Aumentar volume
* Diminuir volume
* Aumentar canal
* Diminuir canal
* Mudar Canal
```
public class TV_smart {

    private boolean ligada;
    private int volume;
    private int canal;

    public TV_smart() {
        this.ligada = false;
        this.volume = 10; // Volume inicial padrão
        this.canal = 1;   // Canal inicial padrão
    }

    // Método para ligar ou desligar a TV
    public void ligarDesligar() {
        this.ligada = !this.ligada;
        if (this.ligada) {
            System.out.println("TV ligada.");
        } else {
            System.out.println("TV desligada.");
        }
    }

    // Método para aumentar o volume
    public void aumentarVolume() {
        if (this.ligada) {
            if (this.volume < 100) {
                this.volume++;
                System.out.println("Volume aumentado para: " + this.volume);
            } else {
                System.out.println("Volume máximo atingido.");
            }
        } else {
            System.out.println("Ligue a TV primeiro.");
        }
    }

    // Método para diminuir o volume
    public void diminuirVolume() {
        if (this.ligada) {
            if (this.volume > 0) {
                this.volume--;
                System.out.println("Volume diminuído para: " + this.volume);
            } else {
                System.out.println("Volume já está no mínimo.");
            }
        } else {
            System.out.println("Ligue a TV primeiro.");
        }
    }

    // Método para aumentar o canal
    public void aumentarCanal() {
        if (this.ligada) {
            this.canal++;
            System.out.println("Canal aumentado para: " + this.canal);
        } else {
            System.out.println("Ligue a TV primeiro.");
        }
    }

    // Método para diminuir o canal
    public void diminuirCanal() {
        if (this.ligada) {
            if (this.canal > 1) {
                this.canal--;
                System.out.println("Canal diminuído para: " + this.canal);
            } else {
                System.out.println("Você já está no canal mínimo.");
            }
        } else {
            System.out.println("Ligue a TV primeiro.");
        }
    }

    // Método para mudar diretamente para um canal específico
    public void mudarCanal(int novoCanal) {
        if (this.ligada) {
            if (novoCanal > 0) {
                this.canal = novoCanal;
                System.out.println("Canal alterado para: " + this.canal);
            } else {
                System.out.println("Canal inválido.");
            }
        } else {
            System.out.println("Ligue a TV primeiro.");
        }
    }

    // Método para verificar o estado atual da TV
    public void estadoAtual() {
        System.out.println("TV está " + (this.ligada ? "ligada" : "desligada"));
        System.out.println("Volume atual: " + this.volume);
        System.out.println("Canal atual: " + this.canal);
    }
}
```

