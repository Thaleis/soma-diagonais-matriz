# Análise de Matriz Quadrada: Soma das Diagonais 

## Sobre o Projeto
Este script realiza operações de baixo nível em matrizes quadradas. O objetivo é demonstrar o domínio sobre o endereçamento de memória em arrays bidimensionais, percorrendo os eixos para calcular a soma dos elementos de suas diagonais principais e secundárias.

## Funcionalidades
- Estruturação de uma matriz quadrada (linhas = colunas).
- Cálculo independente da soma dos itens da Diagonal Principal.
- Cálculo independente da soma dos itens da Diagonal Secundária.
- Exibição dos resultados detalhados no terminal.

## Lógica e Estrutura
- Percorrer laços aninhados (`for` dentro de `for`).
- Controle de indexação de matriz (ex: acesso via `matriz[i][j]`).
- Lógica matemática `i == j` para diagonal principal e `i + j == (n - 1)` para diagonal secundária.
