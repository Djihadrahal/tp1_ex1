#include<stdio.h>

int main() {
    char matrice[5][5] = {
	{'1','2','3','4','5'},
    {'7','a','c','d','e'},
    {'6','9','z','8','3'},
    {'5','6','p','n','3'},
    {'2','9','t','m','k'}
	};
	int i, j;
    printf("full matrix:\n");
    for (i = 0; i < 5; i++) {
        for (j = 0; j < 5; j++) {
            printf("%c ", matrice[i][j]);
        }
        printf("\n");
    }

    printf("\nRows with even indices:\n");
    for (i = 0; i < 5; i += 2) {
        for (j = 0; j < 5; j++) {
            printf("%c ", matrice[i][j]);
        }
        printf("\n");
    }

    printf("\nOdd-indexed elements in each row:\n");
    for (i = 0; i < 5; i++) {
        for (j = 1; j < 5; j += 2) {
            printf("%c ", matrice[i][j]);
        }
        printf("\n");
    }

    return 0;
}
