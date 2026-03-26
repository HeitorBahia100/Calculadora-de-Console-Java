# Calculadora-de-Console-Java
package br.treinamento;

import java.util.Scanner;

public class desafioCalculadora {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc = new Scanner(System.in);
		 
		System.out.println("Escolha a operação que deseja efetuar: ( + . - . * . % )");
		String operacao = sc.nextLine();
		
	
		
		System.out.println("Digite seu primeiro número:");
		int num1 = sc.nextInt();
		
		System.out.println("Digite seu segundo número:");
		int num2 = sc.nextInt();
		
	
		switch (operacao) {
		case "+":
			System.out.println("Sua soma é: " +( num1 + num2));
			break;
		case "-":
			System.out.println("Sua subtração é: " +( num1 - num2));
			break;
		case "*":
			System.out.println("Sua multipicação é: " + (num1 * num2));
			break;
		case "%":
			System.out.println("Sua divisão é: " + (num1 / num2));
			break;	
			default:
				System.out.println("Operação Inválida!");
				break;
		}
		
		
		
		
		sc.close();

	}

}
