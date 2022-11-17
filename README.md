# lista-de-Repeticao
numero-13 /*Escreva um programa que leia um número inteiro, maior ou igual a zero, do usuário.
Imprima o enésimo termo da sequência de Fibonacci. Essa sequência começa no termo de
ordem zero, e, a partir do segundo termo, seu valor é dado pela soma dos dois termos
anteriores. Alguns termos dessa sequência são: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34*/
#include <stdio.h>

int main  (){
	int idade;

do {
	printf("digite sua idade? para verificarmos se voce e maior de idade ");
	scanf ("%d", &idade);
   
   }while (idade<18);
   printf ("parabens, voce e maior de idade!");
 
}



numero -14 /*Elabore um programa que faça a leitura de vários números inteiros até que se digite um
número negativo. O programa tem de retornar o maior e o menor número lido.*/

#include <stdio.h>

int main (){
	int numero;
	int maior=0;
	int menor=1000;
	
	do { 
		printf ("digite um numero: ");
		scanf ("%d", &numero); 
		
		if (numero>maior){	
		maior = numero;
		}
		else if (numero<menor){
		menor= numero;
		}
		
	}while(numero > 0);
		printf ("maior %d\n", maior);
		printf ("menor %d\n", menor) ;
return 0;
}

