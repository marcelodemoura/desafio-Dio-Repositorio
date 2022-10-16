# desafio-Dio-Repositorio
Repositorio criado para o desafio


import java.util.Scanner;

public class ExercicoAleatorios {

	public static void main(String[] args) {
	
		Scanner e = new Scanner(System.in); 
		
		
		//1. Desenvolva um programa que solicite ao usuário seu nome.
		//Em seguida, imprima na tela uma mensagem de boas vindas ao
		//usuário.

		System.out.println("Por favor informe seu nome: ");
		String nome = e.next();
		
		System.out.println("Seja bem vindo " + nome +"!");
		
		//2. Elabore um programa que receba o nome e o sobrenome de um
		//usuário, e em seguida informe: “Seu nome completo é ___”
		
		System.out.println("Digite seu nome: ");
		String nomeUm = e.nextLine();
		
		System.out.println("Digite seu sobrenome ");
		String sobrenome = e.nextLine();
		
		System.out.println("Seu nome completo é!" + nomeUm + sobrenome);
		
		//3. Elabore um programa que receba dois números, e retorne ao
		//usuário a soma desses dois números.
		
		int numeroUm;
		int numeroDois;
		
		System.out.println("Digite o primeiro valor ");
		numeroUm = e.nextInt();
		
		System.out.println("Digite o segundo valor ");
		numeroDois = e.nextInt();
		
		int soma = numeroUm + numeroDois;
		
		System.out.println("Resultado da soma é: " + soma);
		
		//4. Escreva um programa que solicite ao usuário as notas de 3
		//disciplinas. Em seguida, exiba a média das notas.
		
		double notaUm;
		double notaDois;
		double notaTres;
		
		System.out.println("Insira a 1° nota: ");
		notaUm = e. nextDouble();
		
		System.out.println("Insira a 2° nota: ");
		notaDois = e.nextDouble();
		
		System.out.println("Insira a 3° nota: ");
		notaTres = e.nextDouble();
		
		double media = (notaUm + notaDois + notaTres) / 3;
		
		System.out.println("A media das notas é: " + media);
		
		
		//5. Elabore um programa que solicite ao usuário dois números.
		//Em seguida imprima na tela se é verdadeiro ou falso que os
		//números são diferentes.

		int numeroUM;
		int numeroDoiS;
		
		System.out.println("Insira 1° numero");
		numeroUM = e.nextInt();		
				
		System.out.println("Insira 2° numero");
		numeroDoiS = e.nextInt();	
		
		if(numeroUM == numeroDoiS) {
			System.out.println("Verdadeiro");
			
		}else {
			System.out.println("Falso");
		}
		
		//6. Elabore um programa que receba um número, e informe se esse
		//número é ímpar. (Lembre do operador %)
		
		int contador = 0;
		
		System.out.println("Digite um numero: ");
		contador = e.nextInt();
		
		if(contador % 2 == 0) {
			System.out.println("Número Par: ");
		}else {
			System.out.println("Número Impar");
		}
		
		//7. Elabore um programa que solicite ao usuário as idades de três
		//irmãos, A, B e C. Em seguida diga se é verdadeiro ou falso que a
		//idade de A é menor que as idades de B e C juntas.
		
		int idadeA = 0;
		int idadeB = 0;
		int idadeC = 0;
		
		System.out.println("Insra a 1° idade");
		idadeA = e.nextInt();
		System.out.println("Insra a 2° idade");
		idadeB = e.nextInt();
		System.out.println("Insra a 3° idade");
		idadeC = e.nextInt();
		
		if(idadeA <  idadeB + idadeC) {
			System.out.println("Verdadeiro: ");
		}else {
			System.out.println("Falso: ");
		}
		
		// 8. Elabore um programa que solicite ao usuário o valor do lado de
		// um quadrado e retorne em tela o valor de sua área.
		
		double largura = 0;
		double comprimento = 0;
		
		
		System.out.println("insira a largura ");
		largura = e.nextDouble();
		
		System.out.println("Insira o comprimrnto" );
		comprimento = e.nextDouble();

		double area = largura * comprimento;
		
		System.out.println("Área total e de " + area + "m². " );
		
	
		
		//9. Elabore um programa que solicite ao usuário os valores de
		//largura e comprimento de um terreno retangular, e a largura e
		//comprimento de uma casa construída neste terreno. Em seguida
		//retorne à tela a área não construída. (Terreno 15mx20, casa
		//9mx12m) além desses valores use outros de sua preferência.
		
		double comprimentoT = 0;
		double larguraT = 0;
		double comprimentoC = 0;
		double larguraC = 0;
		
		
		System.out.println("Insira o comprimento do terreno: ");
		comprimentoT = e.nextDouble();		
		
		System.out.println("Insira o largura do terreno: ");
		larguraT = e.nextDouble();	

		double areaTerreno = comprimentoT * larguraT;
		
		System.out.println("Total de Área é " + areaTerreno + "m².");
		
		System.out.println("\nInsira o comprimento da casa: ");
		comprimentoC = e.nextDouble();		
		
		System.out.println("Insira o largura da casa: ");
		larguraC = e.nextDouble();	
		
		double areaCasa = comprimentoC * larguraC;
		
		System.out.println("Total de área construida é " + areaCasa + "m².");
		
		double diferenca = areaTerreno - areaCasa;

		System.out.println("\ntotal de área livre é " + diferenca + "m².");
		
		
		
		//10. Elabore um programa que recebe o raio de uma circunferência, e
		//retorna sua área. Considere π=3,14.
		
		double raio = 0;
		double pi = 3.14;
		
		System.out.println("Insira a raio da circunferência");
		raio = e.nextDouble();
		
		double areea = pi * raio * raio;

		System.out.println("Area da circunferencia é: " + areea);
		
		
		//11. Elabore um programa que estime a quantidade de caixas de
		//cerâmicas necessárias para revestir um piso de 10x15m. Cada caixa
		//cobre uma área de 2,20m². Imprima na tela a estimativa da quantidade
		//de caixas necessárias.
		
		//double largura = 10; 
		//double comprimento = 15;
		
		double larguraUM= 0; 
		double comprimentoUM = 0;
		
		System.out.println("Insira largura;");
		larguraUM = e.nextDouble() ;
		System.out.println("Insira largura;");
		comprimentoUM = e.nextDouble() ;
		
		double revestimento = (larguraUM * comprimentoUM) / 2.2;
		System.out.println("A previsão de revestimento ceramico e de" + revestimento);
		
		//12. Elabore um programa que retorne o valor correspondente a 75% do
		//número digitado pelo usuário.
		
		double valor = 0;
		
		System.out.println("Digite o valor:");
		valor = e.nextDouble();
		
		double percentual = valor * 0.75;
		System.out.println("O valor com percentual é: " + percentual);
		
		
		//13. Elabore um programa que retorne a idade de um usuário a partir
		//do ano em que ele nasceu. Neste momento desconsidera o dia e mês de
		//nascimento.
		
		int anoN;
		//int anoA = 2022;
		int anoA = 0;
		
		System.out.println("Digite o ano de nascimento");
		anoN = e.nextInt();	
		
		System.out.println("Digite o ano de atual");
		anoA = e.nextInt();	
		
		int idade = anoA - anoN   ;
		System.out.println("Você tem " + idade + " anos de idade." );
		
		
		
		//14. Você é programador de um escritório de contabilidade e tem a
		//missão de desenvolver uma aplicação que elabora o contracheque de cada
		//funcionário. Elabore um programa que recebe o salário bruto de um
		//usuário e em seguida retorne na tela as seguintes informações:
		//a. O salário bruto é: ___
		//b. O recolhimento do FGTS será: ___
		//c. O recolhimento de INSS será: ___
		//d. O salário líquido este mês será: ___
		//OBS. O valor do recolhimento de FGTS é de 8% do salário bruto, o
		//recolhimento de INSS é de 12% do salário bruto e o salário líquido é
		//igual ao salário bruto - o INSS.
		
		double salarioBruto;
		double descontoUm = 0.08;
		double descontoDois = 0.12;
		
		System.out.println("Informe o salário bruto");
		salarioBruto = e.nextDouble();
		
		System.out.println("\nSalario bruto: R$" + salarioBruto);
		
		double fgts = salarioBruto * descontoUm;
		System.out.println("\nO recolhimento do FGTS será: R$ " + fgts);
		
		double inss = salarioBruto * descontoDois;
		System.out.println("\nO recolhimento de INSS será: R$" + inss);
		
		double salarioLiq = salarioBruto - inss;
		
		System.out.println("\nO salário líquido este mês será: R$" + salarioLiq);
		
		
		 
		//15. Luna é uma jovem com forte espírito científico. Certa vez,
		//observando sua mãe costurar, identificou que no chão havia caído
		//uma fita de cetim. Esta fita tocava suas pontas e formava um
		//círculo perfeito. O piso da casa de sua mãe era revestido com
		//cerâmicas de tamanha 40x40. Sabendo que o círculo formado pela
		//fita tocava os limites da pedra de cerâmica (imagem abaixo), Luna
		//perguntou: Qual seria a área de um quadrado, em que seu lado
		//correspondesse ao tamanho do perímetro do círculo formado pela
		//fita. Considere π=3
		
		
		
	e.close();

	}

}
