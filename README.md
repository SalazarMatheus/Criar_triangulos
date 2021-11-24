# Criar_triangulos
#include <stdio.h>

int main() {

	int M, N, i, j, k;

	printf("Quantos triângulos deseja imprimir: ");
	scanf("%d", &M);
	printf("Quantas linhas possuirá o triângulo: ");
	scanf("%d", &N);
	
	i=1;
	while(i<=M) {
		j=1;
		while(j<=N) {
			k=1;	
			while(k<=j) {
				if(i%2)
					printf("%c", A);
					k=k+1;
				else 
					printf("%c", B);
					k=k+1;					
			}
			printf("\n");
		j=j+1;
		}
	printf("\n");
	i=i+1;
	}
	
	return 0;
	}
