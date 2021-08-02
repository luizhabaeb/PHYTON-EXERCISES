# PHYTON-EXERCISES
Exercícios da matéria de Algoritmos e Lógica Programação - Prof. Fernando Masanori - FATEC SÃO JOSÉ DOS CAMPOS/SP
## LISTAS DE EXERCÍCIOS - https://www.pycursos.com/python-para-zumbis/
- [Lista 2](##Lista-2)
- [Lista 3](##Lista-3)
- [Lista 4](##Lista-4)
- [Lista 6 - Coding Bat](##Lista-6-Coding-Bat)

## Lista 2
> A. Faça um Programa que peça os três lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno.

#### • [Resolução ↓]

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


> B. Determine se um ano é bissexto. Verifique no Google como fazer isso...

#### • [Resolução ↓]

ano = int(input('Qual ano deseja saber se é Bissexto?: '))

if (ano % 4 == 0 and ano % 100 != 0) or (ano % 400 == 0):
    
    print ('Este é um ano Bissexto!')

else:
    
    print ('Não é um ano Bissexto!')


> C. João Papo-de-Pescador, homem de bem, comprou um microcomputador para controlar o rendimento diário de
seu trabalho. Toda vez que ele traz um peso de peixes maior que o estabelecido pelo regulamento de pesca do
estado de São Paulo (50 quilos) deve pagar uma multa de R$ 4,00 por quilo excedente. João precisa que você
faça um programa que leia a variável peso (peso de peixes) e verifique se há excesso. Se houver, gravar na
variável excesso e na variável multa o valor da multa que João deverá pagar. Caso contrário mostrar tais
variáveis com o conteúdo ZERO.

#### • [Resolução ↓]

p = int(input('Peso dos peixes: '))

    if p > 50:
    
    excesso = p - 50
    multa = excesso * 4

else:
    
    multa = excesso = 0

print ('Multa de R$ %.2f' %multa)

print ('Excesso: %.2f' %excesso)


> D. Faça um Programa que leia três números e mostre o maior deles.

#### • [Resolução ↓]

a = int(input('Digite o 1º número: '))

b = int(input('Digite o 2º número: '))

c = int(input('Digite o 3º número: '))

if a > b and a > c:
    
    print ('Maior é o: %d' &a)
elif b > c:
    
    print ('Maior é o: %d' %b)
else:
    
    print ('Maior é o: %d' %c)


> E. Faça um Programa que leia três números e mostre o maior e o menor deles.

#### • [Resolução ↓] 

a = int(input('Digite o 1º número: '))

b = int(input('Digite o 2º número: '))

c = int(input('Digite o 3º número: '))

if a > b and a > c:
    
    print ('Maior é o: %d' %a)
elif b > c:
    
    print ('Maior é o: %d' %b)
else:
    
    print ('Maior é o: %d' %c)

if a < b and a < c:
    
    print ('Menor é o: %d' %a)
elif b < c:
    
    print ('Menor é o: %d' %b)
else:
    
    print ('Menor é o: %d' %c)


> F. Faça um Programa que pergunte quanto você ganha por hora e o número de horas trabalhadas no mês. Calcule
e mostre o total do seu salário no referido mês, sabendo se que são descontados 11% para o Imposto de Renda,
8% para o INSS e 5% para o sindicato, faça um programa que nos dê o salário bruto, quanto pagou ao INSS, quanto pagou ao sindicato
e  o salário líquido. Observe que Salário Bruto - Descontos = Salário Líquido. Calcule os descontos e o salário líquido, conforme a tabela abaixo:
a.+ Salário Bruto : R$
b.- IR (11%) : R$
c.- INSS (8%) : R$
d.- Sindicato ( 5%) : R$
e.= Salário Liquido : R$

#### • [Resolução ↓]

S = float(input('Salário por hora: '))

H = int(input('Horas trabalhadas: '))

BRUTO = S * H

IR = BRUTO * 0.11

INSS = BRUTO *0.08

SINDICATO = BRUTO *0.05

LIQUIDO = BRUTO - IR - INSS - SINDICATO

print ('+Salário Bruto:\t\t R$ %10.2f' %BRUTO)

print ('-IR:\t\t\t R$ %10.2f' %IR)

print ('-INSS:\t\t\t R$ %10.2f' %INSS)

print ('-Sindicato:\t\t R$ %10.2f' %SINDICATO)

print ('=Salário Líquido:\t R$ %2.f' %LIQUIDO)

## Lista 3
- esta é uma frase com intuito de teste de formatação
teste
teste
teste

## Lista 4
- esta é uma frase com intuito de teste de formatação
teste
teste
teste

## Lista 6 Coding Bat
- esta é uma frase com intuito de teste de formatação
teste
teste
teste
