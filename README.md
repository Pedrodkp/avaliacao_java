
# Desafio de programação
A ideia deste desafio é nos permitir avaliar melhor as habilidades de candidatos à vaga de programador, em vários níveis.

Este desafio deve ser feito por você em sua casa. Gaste o tempo que você quiser, porém normalmente você não deve precisar de mais do que algumas horas.

## Instruções de entrega do desafio
1. Primeiro, faça um fork deste projeto para sua conta no Github (crie uma se você não possuir).
2. Em seguida, implemente os exercícios tal qual descrito abaixo, em seu próprio fork, sem usar interface gráfica.
3. Crie as instruções de instalação e execução do aplicativo em seu readme.md
4. Por fim, envie o link do seu repositório para avaliarmos seu código.

## Exercícios do projeto

### Calculadora
Implemente um programa para calcular a soma, subtração, divisão e multiplicação de 2 números e exiba para o usuário os resultados.

### Palíndromo (Usando apenas IF, ELSE, WHILE)
Dizemos que um número natural n é palíndromo se o 1º algarismo de n é igual ao seu último algarismo, o 2º algarismo de n é igual ao penúltimo algarismo, e assim sucessivamente.

Exemplos:

567765 e 32423 são palíndromos.

567675 não é palíndromo.

Dado um número natural   n > 10 , verificar se n é palindrome.

### Agenda
Crie uma classe Contato que possui dois atributos: nome e email do tipo String. Crie outra classe, chamada Agenda, que possui um atributo contatos do tipo vetor de Contato. A classe Agenda deve conter um método para adicionar um novo contato em uma posição vazia do vetor, outro método para buscar um contato (retorna uma instância de Contato) através do nome e, por fim, um método para excluir um contato através do nome.

### Loja de tintas
Faça um Programa para uma loja de tintas. Usando apenas IF e ELSE.

O programa deverá pedir o tamanho em metros quadrados da área a ser pintada.

Considere que a cobertura da tinta é de 1 litro para cada 6 metros quadrados e que a tinta é vendida em latas de 18 litros que custam R$ 80,00 ou em galões de 4 litros que custam R$ 25,00.

Informe ao usuário as quantidades de tinta a serem compradas e os respectivos preços em 3 situações:

- comprar apenas latas de 18 litros;

- comprar apenas galões de 4 litros;

- misturar latas e galões, de forma que o preço seja o menor.

Acrescente 10% de folga e sempre arredonde os valores para cima, isto é, considere latas e galões cheios.

### Caixa Eletrônico
Faça um Programa para um caixa eletrônico. O programa deverá perguntar ao usuário o valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais.

O valor mínimo é de 10 reais e o máximo de 600 reais.

O programa não deve se preocupar com a quantidade de notas existentes na máquina.

- Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas	notas de 100, uma nota de 50, uma nota de 5 e uma 
nota de 1;

- Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.

### Desafio Especial "Matriz"
Considere a função String[] quadradosDeVogais(String[] strArr) que, dada uma matriz 2D de tamanho arbitrário contendo letras (strArr), retorne todos os quadrados 2x2 formados somente por vogais dentro desta matriz. 

Por exemplo, se strArr for ["abcd", "eikr", "oufj"] a matriz será:

a b c d

e i k r

o u f j 

E existe só um quadrado 2x2 formado somente por vogais:

e i

o u

A função, neste caso, deve retornar:

["1,0"]

que é o índice do elemento superior esquerdo do quadrado de vogais.

Caso existam vários quadrados de vogais a função deverá retornar todos. Os quadrados de vogais podem se sobrepor, ou seja, dada a matriz:

a b c d

e i a r

o u e j 

Existem 2 quadrados de vogais sobrepostos:

e i

o u

E também:

i a

u e

E a função deve retornar:

["1,0", "1,1"]


Considerando o que foi exposto, 

1) Descreva, discursivamente, como resolver o problema.
2) Implemente a função quadradosDeVogais definida acima.
3) Faça a análise assíntótica de complexidade da sua solução com relação ao tempo e explique como chegou neste resultado.

## Avaliação
Seu projeto será avaliado de acordo com os seguintes critérios. 

1. Sua aplicação atende funcionalmente o que foi pedido
2. Cobertura de testes
3. Você documentou a maneira de configurar o ambiente e rodar sua aplicação na maquina do avaliador
4. Você seguiu as instruções enviadas
5. Você segue as boas práticas de programação e entrega para o Cliente
6. O código escrito é fácil de entender e manter
7. Você se preocupa com o uso do aplicativo pelo Usuário

Adicionalmente, tentaremos verificar a sua familiarização com as bibliotecas padrões (standard libs), bem como sua experiência com programação orientada a objetos a partir da estrutura de seu projeto, preocupação com o objetivo da aplicação e do seu uso pelo usuário, suporte e manutenção do código por outros desenvolvedores
