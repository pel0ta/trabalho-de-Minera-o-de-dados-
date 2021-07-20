# trabalho-de-Mineração-de-dados-
## Trabalho final de Mineração de dados
### Introdução 
A minha base de dados foi a Adult, que consite em dizer se a pessoa vai
receber <=50k por ano .Os tratamentos dos dados foi pegar a media para
atributos ordinais e pegar a moda para atributos nominas, o algoritmo foi
coeficiente de jaccard.

Numero total de instâncias: 32.561, sendo 7.841 casos negativos e 24.720
positivos. Serão 3.256 duplas de teste e 29.305 de treino.
Número de variáveis: 14 mais a classe.
As variáveis consistem em:
* age
* workclass
* fnlwgt
* education:
* education-num
* marital-status
* occupation
* relationship
* race
* sex
* capital-gain
* capital-loss
* hours-per-week
* native-country

O algoritmo de classificação KNN é o algoritmo usado, sendo K =
3 e K = 57, isso significa que pegaremos os 3 ou os 57 vizinhos mais
próximos, e olhando a classe deles, pegando a classe que mais se
repetiu entre eles, ou seja, a moda.
### O Algoritimo foi desenvolvido na linguagem R 
