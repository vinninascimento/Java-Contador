## Controle de Fluxo - Desafio
Neste desafio, vamos aplicar os conceitos de controle de fluxo do Java para criar um programa que recebe dois parâmetros via terminal e realiza operações com eles. A seguir, detalhamos os requisitos do desafio:

### Requisitos do Desafio
O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros.

Com base nos dois números fornecidos, o programa calculará a quantidade de iterações (usando um loop for) e imprimirá os números incrementados no console.

Por exemplo, se você passar os números 12 e 30, o programa realizará uma iteração (loop) com 18 ocorrências, imprimindo números de 1 a 18 no console. A saída será como "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

No caso em que o primeiro parâmetro seja MAIOR que o segundo parâmetro, o programa lançará uma exceção personalizada chamada ParametrosInvalidosException com a seguinte mensagem: "O segundo parâmetro deve ser maior que o primeiro".

### Instruções
Crie um projeto chamado "DesafioControleFluxo" para organizar o código.

Dentro do projeto, crie a classe Contador.java para implementar a lógica do programa.

Além disso, crie uma classe separada chamada ParametrosInvalidosException que representará a exceção personalizada para tratamento de casos onde o segundo parâmetro seja menor que o primeiro.
