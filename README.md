# Faculdade_P2
Atividades do segundo período da facul

A) Exercícios sobre VETOR:

Exercício 1. Faça um código que:
a) Leia um valor informado pelo usuário, que representa a quantidade de alunos de uma sala.
b) Declare quatro vetores de float (Nota1[],Nota2[], Nota3[] e Media[]), com o valor informado pelo usuário.
c) Realize a leitura das três notas de cada aluno, armazenando nos vetores respectivos (cada aluno é
identificado pelo índice do vetor).
d) Realize a média das três notas e armazene o valor no vetor Media[] (para o aluno do respectivo índice).


Exercício 2. Faça um programa que leia um valor inteiro N que representa o tamanho do vetor. Em seguida, defina
um vetor X de inteiros de tamanho N. O programa deve fazer a leitura de N valores inteiros e salvá-los no vetor X.
Após isso, o programa deve copiar os elementos das posições pares do vetor X para um novo vetor Y. Para encontrar
o tamanho do vetor Y, considere o valor de N, se N for ímpar, o tamanho de Y será (N/2)+1, caso contrário N/2.
Considere a posição 0 como sendo par. Como saída, o programa deve apresentar na saída padrão o vetor Y, onde,
para cada posição do vetor Y, escreva “Y[i] = z”, onde i é a posição do vetor e z é o valor armazenado naquela
posição.
 --
 Exemplos de entrada e saída:
 Input --> 5                    Input --> 6                           Input --> 1
           10 9 8 7 6                     56 89 74 32 41 25                     45
 Result --> Y[0] = 10           Result --> Y[0] = 56                  Result --> Y[0] = 45
            Y[1] = 8                       Y[1] = 74
            Y[2] = 6                       Y[2] = 41
            

Exercício 3. Faça um programa que leia um valor inteiro N que representa o tamanho do vetor. Em seguida, defina
um vetor X de inteiros de tamanho N. O programa deve fazer a leitura de N valores inteiros e salvá-los no vetor X.
Valide para sejam aceitos apenas valores entre 0 e 9 (inclusive) no vetor X. Em seguida, verifique se a sequência de
elementos do vetor é a mesma se lida da esquerda para a direita ou da direita para a esquerda. Se sim, apresente na
saída padrão "Mesma sequencia!", caso contrário, "Sequencias diferentes.".
 --
 Exemplos de entrada e saída:
 Input --> 5                     Input --> 10                           Input --> 4  
           1 2 3 2 1              
           0 1 4 5 9 9 5 4 1 0                    7 6 4 1
 Result --> Mesma sequencia!     Result --> Mesma sequencia!            Result --> Sequencias diferentes.
 
 Input --> 4                           Input --> 5
           1 0 0 0                               47 6 2 5 2 6
 Result --> Sequencias diferentes.     Result --> Valor inválido! Tente novamente.
                                                  Mesma sequencia.
                                                  

Exercício 4. Faça um programa que leia um valor inteiro N que representa o tamanho do vetor. Em seguida, defina
um vetor X tipo float de tamanho N. O programa deve fazer a leitura de N valores float e salvá-los no vetor X. Em
seguida, o programa deve receber da entrada padrão um valor float qualquer. Após isso, o programa deve verificar
se o valor informado está no vetor X. Caso o valor for encontrado, apresentar na saída padrão "Encontrado na
posicao z", onde z é o valor da posição. Caso contrário, apresentar " Valor nao esta armazenado no vetor ".
 --
 Exemplos de entrada e saída:
 Input --> 6                                     Input --> 6                                             Input --> 3
           1.5 3.8 7.4 5.0 1.0 9.9                         1.5 3.8 7.4 5.0 1.0 9.9                                 2.0 1.6 1.6
           7.4                                             4.0                                                     1.6
 Result --> Encontrado na posicao 2              Result --> Valor nao esta armazenado no vetor           Result --> Encontrado na posicao 1


Exercicio 5. Faça um programa em C que leia um valor inteiro N que representa o tamanho do vetor. Após isso, 
defina um vetor de double de tamanho N. O programa deve fazer a leitura de N valores double e salvá-los no vetor. 
Por fim, o programa deve imprimir a posição do vetor e o valor correspondente como mostrado no exemplo abaixo 
(com uma casa decimal) em ordem crescente e decrescente.
  Entrada: Um valor inteiro N, seguido de N valores double .
  Saída: Os valores do vetor em ordem crescente e decrescente conforme exemplo abaixo.
  --
 Exemplos de entrada e saida: 
 Input --> 5 / 10.0 5.0 9.0 8.0 7.0
 Result --> V[0] = 10.0
            V[1] = 5.0
            V[2] = 9.0
            V[3] = 8.0
            V[4] = 7.0
            V[4] = 7.0
            V[3] = 8.0
            V[2] = 9.0
            V[1] = 5.0
            V[0] = 10.0
            
            
Exercicio 6. Faça um programa em C que leia um valor inteiro N que representa o tamanho do vetor. Após isso, 
defina um vetor de inteiros de tamanho N. O programa deve fazer a leitura de N valores e salvá-los no vetor. 
Por fim, o programa deve imprimir a posição do vetor e o valor somente dos números pares do vetor.
  Entrada: Um valor inteiro N, seguido de N valores inteiros.
  Saída: A posição e os valores pares do vetor.
  --
 Exemplos de entrada e saida:
 Input --> 5                  Input --> 3
           10 8 1 4 7                   3 5 7
 Result --> V[0] = 10         Result --> (vazio)
            V[1] = 8
            V[3] = 4
 
 
Exercicio 7. Faça um programa em C que leia um valor inteiro N que representa o tamanho do vetor. Após isso, 
defina um vetor de float de tamanho N. O programa deve fazer a leitura de N valores e salvá-los no vetor. 
Em seguida, o programa deve ler um valor float X. Por fim, o programa deve mostra somente os valores menores 
que X (com duas casas decimais) e a posição do vetor em que elas estão.
  Entrada: Um valor inteiro N, seguido de N valores float e, ao final, um float X.
  Saída: Os valores menores que X do vetor e a sua respectiva posição no vetor.
  --
 Exemplos de entrada e saida:
 Input --> 5                      Result --> V[0] = 6.30
           6.3 14.9 8.3 3.15 5.5             V[1] = 3.15
           8.3                               V[4] = 5.50
           
           
Exercicio 8. Faça um código que leia dois vetores, V={v1, v2, . . . , vN} e W={w1, w2, . . . , wN}, 
de inteiros longos, ambos de tamanho N da entrada padrão (ver formato em Entrada) e imprima o somatório, S, 
da exponenciação entre os valores que estão na mesma posição dos vetores, de modo que os valores do vetor V 
correspondam a base e os valores do vetor W correspondam ao expoente.
  Entrada: O caso de teste é composto por três linhas. A primeira linha contém um inteiro 1 <= N <=30, indicando 
o tamanho dos vetores. A segunda linha contém N inteiros separados por um espaço em branco com os valores do vetor V. 
A terceira linha contém N inteiros em ordem separados por um espaço em branco com os valores do vetor W.
  Saída: Imprima uma linha contendo o valor S.
  --
 Exemplos de entrada e saida:
 Input --> 5          Result --> 35
           1 2 3 4 5
		       2 2 2 2 1
 
 
Exercicio 9. Faça um programa em C que encontre a primeira posição de valores em um vetor. Primeiramente leia um 
vetor V, de tamanho N, da entrada padrão no formato especificado abaixo. Após isso, para cada uma das M consultas 
retorne a primeira posição do vetor na qual tal valor pode ser encontrado.
  Entrada:
   (a) A entrada inicia com uma linha contendo um único inteiro 0 < N = 20 indicando a quantidade de itens do vetor V.
   (b) A segunda linha contém N inteiros, sendo que o primeiro deve ser armazenado na posição V[0], o segundo na posição V[1] e assim sucessivamente.
   (c) A terceira linha contém o um único inteiro 0< M=20 indicando o número de consultas.
   (d) Finalmente, a quarta linha contém M inteiros, cada um representando um valor a ser consultado.
  Saída: Para cada consulta imprima uma linha com a posição do vetor na qual o valor sendo consultado se encontra OU a 
  mensagem ”NOT FOUND” se o valor não pode ser encontrado.
  --
 Exemplos de entrada e saida:
 Input --> 3               Input --> 5
           2 7 1                     4 3 1 2 0
           5                         2
           2 1 7 8 2                 0 1
 Result --> 0              Result --> 4
            2                         2
            1
            NOT FOUND
            0
