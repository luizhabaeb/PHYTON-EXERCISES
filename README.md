# PHYTON-EXERCISES
Exercícios da matéria de Algoritmos e Lógica Programação - Prof. Fernando Masanori - FATEC SÃO JOSÉ DOS CAMPOS/SP

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
