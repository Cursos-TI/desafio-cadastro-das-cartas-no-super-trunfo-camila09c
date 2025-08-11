#include <stdio.h>
#include <string.h>

// Definição da estrutura para representar uma carta do super trunfo 
struct CartasSuperTrunfo {
    char estado;
    char codigo_carta[4];
    char nome_cidade[50];
    int populacao;
    float area_km2;
    float pib_bilhoes;
    int num_pontos_turisticos;
};

// Protótipo da função para exibir os dados de uma carta
void exibir_carta(const char* titulo, struct CartasSuperTrunfo carta);

int main() {
    // Declaração de duas cartas
    struct CartasSuperTrunfo carta1, carta2;

    // --- CADASTRO DA PRIMEIRA CARTA ---
    printf("--- Cadastro da carta 1 ---\n");

    printf("Estado (A-H): ");
    scanf(" %c", &carta1.estado);

    printf("Codigo da carta (ex: A01): ");
    scanf("%s", carta1.codigo_carta);

    printf("Nome da cidade: ");
    scanf(" %[^\n]", carta1.nome_cidade);

    printf("Populacao: ");
    scanf("%d", &carta1.populacao);

    printf("Area (em km²): ");
    scanf("%f", &carta1.area_km2);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &carta1.pib_bilhoes);

    printf("Numero de pontos turisticos: ");
    scanf("%d", &carta1.num_pontos_turisticos);

    printf("\n");

    // --- CADASTRO DA SEGUNDA CARTA ---
    printf("--- Cadastro da carta 2 ---\n");

    printf("Estado (A-H): ");
    scanf(" %c", &carta2.estado);

    printf("Codigo da carta (ex: B02): ");
    scanf("%s", carta2.codigo_carta);

    printf("Nome da cidade: ");
    scanf(" %[^\n]", carta2.nome_cidade);

    printf("Populacao: ");
    scanf("%d", &carta2.populacao);

    printf("Area (em km²): ");
    scanf("%f", &carta2.area_km2);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &carta2.pib_bilhoes);

    printf("Numero de pontos turisticos: ");
    scanf("%d", &carta2.num_pontos_turisticos);

    printf("\n");

    // --- EXIBIÇÃO DAS CARTAS ---
    exibir_carta("Carta 1", carta1);
    exibir_carta("Carta 2", carta2);

    return 0;
}

// Implementação da função para exibir os dados de uma carta
void exibir_carta(const char* titulo, struct CartasSuperTrunfo carta) {
    printf("--- %s ---\n", titulo);
    printf("Estado: %c\n", carta.estado);
    printf("Codigo: %s\n", carta.codigo_carta);
    printf("Nome da cidade: %s\n", carta.nome_cidade);
    printf("Populacao: %d\n", carta.populacao);
    printf("Area: %.2f km²\n", carta.area_km2);
    // Este era o erro! Estava "print" e não "printf".
    printf("PIB: %.2f bilhoes de reais\n", carta.pib_bilhoes);
    printf("Numero de pontos turisticos: %d\n", carta.num_pontos_turisticos);
    printf("\n");
}
