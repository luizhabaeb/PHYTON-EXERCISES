# PHYTON-EXERCISES
Exercícios da matéria de Algoritmos e Lógica Programação - Prof. Fernando Masanori - FATEC SÃO JOSÉ DOS CAMPOS/SP
- [LISTA II](##LISTAII)

##LISTA II
- A. Faça um Programa que peça os três lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno.

- [Resolução ↓]

a = int(input('Lado A: '))

b = int(input('Lado B: '))

c = int(input('Lado C: '))

if a > b + c or b > a + c or c > b + a:
    
    print ('Não é um triângulo, pois um dos lados é maior que a soma dos outros')

elif a == b == c:
    
    print ('É um triângulo Equilátero.')

elif a == b or b == c or a == c:
    
    print ('É um triângulo Isósceles')

else:
    
    print ('É um triângulo Escaleno')

- B. Determine se um ano é bissexto. Verifique no Google como fazer isso...

- [Resolução ↓]

ano = int(input('Qual ano deseja saber se é Bissexto?: '))

if (ano % 4 == 0 and ano % 100 != 0) or (ano % 400 == 0):
    
    print ('Este é um ano Bissexto!')

else:
    
    print ('Não é um ano Bissexto!')

- C. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de
seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do
estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você
faça um programa que leia a variável peso (peso de peixes) e verifique se há excesso. Se houver, gravar na
variável excesso e na variável multa o valor da multa que João deverá pagar. Caso contrário mostrar tais
variáveis com o conteúdo ZERO.

- [Resolução ↓]

p = int(input('Peso dos peixes: '))

    if p > 50:
    
    excesso = p - 50
    multa = excesso * 4

else:
    
    multa = excesso = 0

print ('Multa de R$ %.2f' %multa)

print ('Excesso: %.2f' %excesso)
