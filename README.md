# Programa qual é o dia da semana?!

Programa criado para ver qual é o dia da semana de acordo com os números de 1 à 7. Programa feito com os especificadores if-else e switch.

Nesse caso, você começa declarando a variável dia do tipo int para armazenar o número do dia da semana. Depois, você decide que hoje é terça-feira e atribui o valor 3 para a variável dia.

O programa então verifica a variável dia usando uma série de instruções if-else-if. Primeiramente, ele verifica se dia é igual a 1. Se for, imprime "Domingo". Como dia é 3, ele continua verificando cada condição else if. Quando ele chega à condição else if (dia == 3), esta é verdadeira, então o programa imprime "Terça-feira". Se dia não for igual a nenhum dos valores de 1 a 7, o else final imprimirá "Dia inválido".

Embora esse método funcione, ele pode se tornar difícil de ler e manter se houver muitas condições. Vamos simplificar isso usando a estrutura switch.

Assim como antes, você declara a variável dia do tipo int para armazenar o número do dia da semana e atribui o valor 3 para indicar que hoje é terça-feira.

A variável dia é usada como controle para o switch. Cada case verifica um valor específico da variável dia. Quando dia é 1, o programa imprime "Domingo". Quando dia é 2, imprime "Segunda-feira". Quando dia é 3, imprime "Terça-feira", e assim por diante.
