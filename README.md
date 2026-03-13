package PedroGaspar;

import java.util.Scanner;

public class PG01 {
	public static void main(String[] args) {
		System.out.println("*******************************************");
		System.out.println("*Aluno : Pedro Gaspar**********************");
		System.out.println("*Classe PG01 - Número positivo ou negativo*");
		System.out.println("*******************************************");
		
		Scanner sc = new Scanner(System.in);
		
		System.out.print("Digite um número : ");
		int numero = sc.nextInt();
		
		if(numero >= 0) {
			System.out.println("Número positivo!");
		}
		else{
			System.out.println("Número negativo");
		}
		
	}

}
