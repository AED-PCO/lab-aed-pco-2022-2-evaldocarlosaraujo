Problema: 
Alguns números de quatro algarismos possuem uma característica particular. Se separamos esse número em dois grupos 
e os somarmos encontramos um outro número cujo quadrado é exatamente igual ao número fornecido anteriormente. 
Veja o exemplo: Número = 3025 

Separando o número em dois grupos de dois algarismos temos o 30 e o 25. 
A soma de 30 com 25 é igual a 55
O Quadrado de 55 é igual a 3025.
 
Faça um programa que mostre os números de 1000 a 9999 que possuem essa característica.

Solução: 
Dados tres variaveis num1, num2 e resultado para armazenar os calculos do problema, foi feito a divisão 
por 100 dos numeros onde o num1 recebe o resultado da divisão inteira, o num2 recebe o resto da divisão 
e o resultado recebe a soma desses numeros da operação ao quadrado, após isso o resultado é comparado 
com o numero armazenado a variavel local "i" e no caso se a condição for verdadeira imprime na tela os 
numeros que atendem o requisito como mostrado no print a seguir.