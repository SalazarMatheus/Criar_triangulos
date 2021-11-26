# Criar_triangulos

	#include <stdio.h>

        int main() {

        int M, N, i, j, k;
        char X = 'A', Y = 'B';

        printf("Quantos triangulos serao formados: ");
        scanf("%d", &M);
        printf("Quantas linhas terao o triangulo: ");
        scanf("%d", &N);
        printf("\n");

        i=1;
        while(i<=M) {
                j=1;
                while(j<=N) {
                        k=1;
                        while(k<=j) {
                                if(i%2)
                                        printf("%c", X);
                                else
                                        printf("%c", Y);
				k=k+1; 
                        }
                        printf ("\n");
                j=j+1;
                }
        printf ("\n");
        i=i+1;
        }

        return 0;

        }
