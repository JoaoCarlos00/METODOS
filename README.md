# ETAPA 2 AC1

Nesta etapa os exercícios serão sobre números

### 📋 Códigos
Escreva um método que mostra se um número é positivo ou negativo. Considere o zero positivo.

import java.util.Scanner; //Importei o scanner pois ele é importante para determinar se o numero é positivo ou negativo
public class NumeroPositivoNegativo {
    public static void main(String[]args) {
	

    Scanner scanner = new Scanner(System.in); 

    System.out.println("Digite um número:"); //Pedi para o codigo pedir um numero
    int numero = scanner.nextInt();

    if (numero == 0) { //Nessa sequencia eu determinei o que faz o numero ser positivo e negativo para assim o codigo funcionar de acordo com o que se pede
    System.out.println("Positivo");
    } else if (numero > 0) {
    System.out.println("Positivo");
    } else {
    System.out.println("Negativo");
    }
    scanner.close();
}
}
///////////////////////////////////////////////////////////
Escreva um método recebe 3 números e informa a média aritmética;

import java.util.Scanner;

public class MediaAritmetica {
    public static void main(String[]args) {
	
    double numero; //Nesta sequencia eu determinei como o codigo deve entender o numeros, no caso utilizei o double pois numa media aritmetica o resultado pode dar um numero quebrado
    double numero2;
    double numero3;
    double media;
    Scanner scanner = new Scanner(System.in);

    System.out.println("Digite o primeiro número:"); //Pedi para o codigo pedir os 3 numeros 
    numero = scanner.nextDouble();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextDouble();

    System.out.println("Digite o terceiro número:");
    numero3 = scanner.nextDouble();

    media = (numero + numero2 + numero3)/3;   //Determinei como fazer a media aritmetica e pedi para printar o resultado
    System.out.println("A média aritmética: " + media);

}
}
//////////////////////////////////////////////////////////////
Escreva um método que recebe três números e retorna o maior.

import java.util.Scanner;

public class MaiorNumero {
    public static void main(String[]args) {

    int numero; //Determinei que codigo deveria entender os numeros como numeros inteiros 
    int numero2;
    int numero3 ;
    Scanner scanner = new Scanner(System.in);

    System.out.println("Digite o primeiro número:"); //Pedi para o codigo pedir os numeros para quem gerar os codigos
    numero = scanner.nextInt();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextInt();

    System.out.println("Digite o terceiro número:");
    numero3 = scanner.nextInt();

    if (numero > numero2 && numero > numero3) {  //Determinei como o codigo vai entender qual numero sera o maior ou menos e pedi para printar o maior
    System.out.println("O maior número é: " + numero);
    }
    else if (numero > numero2 && numero < numero3) {
    System.out.println("O maior número é: " + numero3); 
    }
    else if (numero < numero2 && numero2 < numero3) {
    System.out.println("O maior número é: " + numero3); 
    }
    else if (numero < numero2 && numero2 > numero3) {
    System.out.println("O maior número é: " + numero2); 
    }
}
}
///////////////////////////////////////////////////////////////////
Escreva um método que recebe dois números, a e b, e retorna ab.

import java.util.Scanner;

public class A_elevado_a_B {
    public static void main(String[]args) {
	
    int numero;
    int numero2;
    int retorno;
    Scanner scanner = new Scanner(System.in);

    System.out.println("Digite o primeiro número:");
    numero = scanner.nextInt();

    System.out.println("Digite o segundo número:");
    numero2 = scanner.nextInt();

    retorno = (numero*numero2); //Pedi para o codigo retornar o Resultado do primeiro numero elevado ao segundo numero
    System.out.println(retorno);

}
}
////////////////////////////////////////////////////////////////////
Escreva um método que recebe uma quantidade de minutos e retorna o equivalente em horas e minutos.
Por exemplo: 90 min = 1 hora e 30 minutos

import java.util.Scanner;

public class Horas_e_Minutos {
    public static void main(String[]args) {
	
    double numero;   //Determinei que o codigo deveria entender os numeros e o retorno como double para que possa gerar o resultado com maior precisão
    double retorno;
    double retorno2;
    Scanner scanner = new Scanner(System.in);

    System.out.println("Digite a quantidade de minutos à ser convertido em horas: ");
    numero = scanner.nextDouble();

    retorno = numero % 60; //Determinei que o primeiro retorno mostraria o resto do numero por 60 e o segundo retorno seria o numero subtraindo o resto do primeiro retorno e dividindo por 60
    retorno2 = (numero - retorno) / 60;

    System.out.println(retorno2 + " Horas(s) e " + retorno + " minuto(s)"); //O primeiro retorno é os minutos e o retorno2 as hroas

}
} 
////////////////////////////////////////////////////////////////////
Escreva uma função que retorna o fatorial de número informado por parâmetro

import java.util.Scanner;
public class Fatorial {

public static void main (String args[]){

	Scanner scanner = new Scanner (System.in);
	
	double retorno;
	
	System.out.println("Digite o Primeiro número: ");
        double numero = scanner.nextDouble();; // Aqui determinei e criei uma variavel que ira armazenar o numero do fatorial
    
        System.out.println("Digite o Segundo número: ");
	double numero2 = scanner.nextDouble();; // Aqui criei outra variavel para a fatoração

        retorno= numero * (numero2-1); // Aqui determinei como o codigo ira fatorar o numero
     
     System.out.println(retorno); 
  }
  }
  
////////////////////////////////////////////////////////////////////
## 🛠️ Construído com

Ferramentas utilizadas e bibliotecas

* IDE Eclipse

## 📌 Versão

* **Versão 1.0** caso seja atualizado manter a descrição inicial e inserir uma nova linha com descrição da atualização.
* **Versão 1.1** - *Refatoração* *data 09/09/24*

## ✒️ Autores

João Carlos Ferreira de Araujo RA 248152 -- AC1 de Programação Orientada à Objetos

