# 1º Código - Arrecadação de Doações

Descrição:
Este programa coleta doações e calcula o valor total arrecadado, a quantidade de pessoas que doaram e a média de doação por pessoa. O processo de arrecadação termina quando o total arrecadado atinge R$7500 ou quando 100 doadores contribuíram.

Fluxo do programa:
Inicializa valortotal = 0 e pessoas = 0.
Em um loop do-while, solicita um valor de doação e adiciona ao total.
O loop continua enquanto o total arrecadado for menor que R$7500 e menos de 100 pessoas tiverem doado.
Após o loop, calcula e exibe a média de doação por pessoa.
Se R$7500 for atingido antes de 100 pessoas doarem, exibe uma mensagem informando o sucesso da arrecadação.
Caso contrário, exibe uma mensagem informando que o número máximo de doadores foi atingido sem alcançar a meta.

# 2º Código - Impressão de uma Tabela

Descrição:
Este programa imprime uma tabela com duas colunas: a primeira variando de 1 a 10, e a segunda contendo valores decrementados a partir de y = 21.

Fluxo do programa:
Define y = 21.
Utiliza um loop for para iterar x de 1 a 10.
Em cada iteração, imprime x e y - x, onde y-x gera a segunda coluna.
O programa finaliza após imprimir todos os valores.
Saída esperada:
1    20
2    19
3    18
...
10   11

# 3º Código - Contagem Decrescente

Descrição:
Este programa solicita ao usuário um número entre 5 e 20, validando a entrada. Em seguida, ele imprime uma contagem regressiva começando do número inserido até 0.

Fluxo do programa:
Solicita um número dentro do intervalo [5, 20] e valida a entrada com um do-while.
Define sum = input e inicia um loop for que percorre de 0 até input.
Em cada iteração, imprime x e sum, onde sum decrementa a cada passo.
O programa exibe uma sequência decrescente paralela à contagem crescente.
Saída esperada (exemplo para input = 7):
0    7
1    6
2    5
3    4
4    3
5    2
6    1
7    0

# 4º Código - Contadores i e j com Multiplicação

Descrição:
Este programa solicita um número entre 10 e 50, depois imprime duas variáveis (i e j) aumentando i de 0 até input e j de 0 até input * 2, em incrementos de 5.

Fluxo do programa:
Solicita um número entre 10 e 50 e valida a entrada.
Define conta = input * 2, que serve como limite para j.
Utiliza um do-while para exibir i e j, incrementando:
i++ (incremento de 1)
j = j + 5 (incremento de 5)
O loop continua enquanto i <= input e j <= conta.
Saída esperada (exemplo para input = 10):
i = 0      j = 0
i = 1      j = 5
i = 2      j = 10
i = 3      j = 15
...
i = 10     j = 50
Se input = 15, o j pararia em 30, pois j <= conta (30).
