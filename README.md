# Resolução exercício Beecrowd1065

## Descrição do problema
Faça um programa que leia 5 valores inteiros. Conte quantos destes valores digitados são pares e mostre esta informação.

## Como Funciona
1. O programa inicializa uma variável contadora (`controle = 0`) para armazenar a quantidade de números pares.
2. Uma estrutura de repetição `for` é executada exatamente cinco vezes para capturar os dados inseridos pelo usuário na variável `numeros`.
3. Dentro do laço, uma estrutura condicional `if (numeros % 2 == 0)` utiliza o operador de resto (`%`) para verificar se o número é par.
4. Se o resto da divisão por 2 for igual a zero, a variável `controle` é incrementada em 1 (`controle++`).
