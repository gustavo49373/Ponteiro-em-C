# Ponteiro-em-C
questões de ponteiros resolvidos :)
#include <stdio.h>
#include <locale.h>

int main(){
    setlocale(LC_ALL, "portuguese");
    float cordenada_x;
    float *ponteiro_x;
    ponteiro_x = &cordenada_x;

    printf("Digite a coordenada X: \n");
    scanf("%f", ponteiro_x);

    printf("Posição do portal no eixo X: [%.2f]\n", *ponteiro_x);
    printf("Endereço do portal para teletransporte: [%p]", ponteiro_x);

    return 0;
}
