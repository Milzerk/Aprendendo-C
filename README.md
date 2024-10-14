# Aprendendo-C
Decidi que quero aprender C, por motivos nenhum, Então pedi que o chat-GPT gerace alguns desafios de nível de alguém que não sabe C até a criação de um compilador.
Mas por que um compilador? eu vi que alguém aleatório fez, então vou fazer também.
Não tenho um cronograma, então vou só fazendo e em algum momento devo terminar

*Gerado por CHAT-GPT*
# Desafios em C

## Nível Iniciante

1. **"Hello, World!"**  
   Escreva seu primeiro programa em C que exiba "Hello, World!" no console.

2. **Cálculo de Operações Simples**  
   Crie um programa que peça dois números ao usuário e exiba a soma, subtração, multiplicação e divisão desses números.

3. **Condicionais e Loops**  
   Escreva um programa que peça ao usuário um número e diga se é par ou ímpar.  
   Expanda para um programa que verifique se um número é primo.

4. **Vetores e Matrizes**  
   Crie um programa que leia 10 números inteiros e exiba a soma e a média deles.  
   Depois, modifique para trabalhar com uma matriz 3x3 e calcular a soma dos elementos da diagonal principal.

5. **Funções**  
   Escreva um programa que use uma função para calcular o fatorial de um número.  
   Expanda para incluir funções que trabalhem com outras operações matemáticas, como a potência e a raiz quadrada.

---

## Nível Intermediário

6. **Manipulação de Strings**  
   Crie um programa que peça uma string e verifique se é um palíndromo (mesma sequência de letras lida de trás para frente).

7. **Ponteiros**  
   Escreva um programa que troque o valor de duas variáveis usando ponteiros.  
   Depois, crie um programa que trabalhe com ponteiros para manipular um array de inteiros.

8. **Estruturas e União**  
   Crie um programa que modele um cadastro de alunos, utilizando uma `struct` para armazenar nome, idade e nota.  
   Use uma união (`union`) para armazenar diferentes tipos de dados (inteiro, float, char) em um mesmo bloco de memória.

9. **Manipulação de Arquivos**  
   Crie um programa que leia um arquivo de texto e conte o número de linhas, palavras e caracteres no arquivo.  
   Expanda para permitir que o usuário forneça o nome do arquivo via linha de comando.

10. **Recursão**  
    Escreva um programa que resolva o problema das Torres de Hanói usando recursão.

---

## Nível Avançado

11. **Alocação Dinâmica de Memória**  
    Crie um programa que aloque dinamicamente memória para um array de números e permita que o usuário insira quantos elementos desejar. O programa deve calcular a média desses números e liberar a memória alocada no final.

12. **Implementação de Algoritmos Clássicos**  
    Escreva um programa para implementar algoritmos de ordenação (ex.: Bubble Sort, Merge Sort) e busca (ex.: Busca Binária). Compare o desempenho de cada algoritmo para diferentes tamanhos de entrada.

13. **Estruturas de Dados Personalizadas**  
    Implemente uma lista encadeada simples com operações de inserção, remoção e busca de elementos.  
    Expanda para uma árvore binária de busca, com funções para inserir, buscar e remover nós.

14. **Criação de um Jogo Simples**  
    Crie um jogo de adivinhação onde o computador gera um número aleatório e o usuário deve tentar adivinhar. O programa deve dar dicas como "maior" ou "menor" após cada tentativa.

15. **Criação de Threads (Pthread)**  
    Escreva um programa que crie várias threads em C usando a biblioteca Pthread, onde cada thread executa uma tarefa diferente (ex.: calcular uma soma, escrever em um arquivo, etc.).

---

## Nível Expert

16. **Simulador de Compilador Simples**  
    Comece a desenvolver um simples "compilador" para uma linguagem fictícia. Os passos podem incluir:
   - **Análise Léxica (Lexer)**: Escreva um analisador léxico que leia uma string e quebre o código em tokens (palavras reservadas, variáveis, números, etc.).
   - **Análise Sintática (Parser)**: Desenvolva um parser que verifique a sintaxe dos tokens gerados pelo lexer, assegurando que as regras gramaticais sejam seguidas.
   - **Gerador de Código (Code Generator)**: Crie uma fase que transforme a árvore sintática em código de uma linguagem de montagem simples ou C.
   - **Interpretador**: Em vez de gerar código, faça com que seu compilador execute diretamente as instruções a partir da árvore sintática.

17. **Implementação de um Sistema de Gerenciamento de Memória**  
    Crie um sistema básico de gerenciamento de memória que simule o comportamento de alocação e liberação de blocos de memória em um sistema operacional.

18. **Sistema de Arquivos Simulado**  
    Implemente um sistema de arquivos simples que suporte a criação, leitura e escrita de arquivos em um "disco" virtual, usando alocação sequencial ou alocação por lista encadeada.

---

## Desafio Final

19. **Compilador Completo**  
    Crie um compilador simples para uma linguagem de programação de sua escolha ou uma inventada por você, que seja capaz de gerar um código executável básico ou interpretar as instruções diretamente.
