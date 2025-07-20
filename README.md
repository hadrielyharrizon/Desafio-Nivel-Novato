# Desafio-Nivel-Novato
Desafio Nível Novato 

Cadastro de Cartas de Cidades
 Este é um programa simples em C que permite o cadastro e exibição de dados de duas cidades representadas como cartas, contendo informações como estado, código, nome, população, área, PIB e número de pontos 
 turísticos.

Funcionalidades
 Entrada de dados de duas cidades (carta 1 e carta 2)
 Exibição formatada das informações de cada carta
 Utilização de tipos básicos da linguagem C (char, int, float, strings)

Tecnologias Utilizadas
 Linguagem C
 Biblioteca padrão stdio.h

Como Executar
 1. Compile o código
bash
Copiar
Editar
gcc -o cartas_cidades cartas_cidades.c
2. Execute o programa
bash
Copiar
Editar
./cartas_cidades
3. Exemplo de entrada
Você será guiado pelo terminal para inserir os seguintes dados para cada cidade:

less
Copiar
Editar
Cadastro da Carta 1:
Estado (A-H): A
Código (ex: A01): A01
Nome da Cidade: Recife
População: 1600000
Área (km²): 218.4
PIB (bilhões de reais): 75.2
Número de Pontos Turísticos: 12
O mesmo será solicitado para a Carta 2.

📝 Estrutura dos Dados
Cada "carta" armazena as seguintes informações:

Estado (letra entre A e H)

Código da carta (ex: A01, B02, etc.)

Nome da cidade

População total

Área em quilômetros quadrados

PIB em bilhões de reais

Número de pontos turísticos

📄 Saída Exemplo
