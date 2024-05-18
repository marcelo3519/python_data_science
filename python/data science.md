texto = 'Marcelo'
numero_inteiro = 10
numero_real = 5.6
dado_boleano = True

# print() -> mostrar ou imprimir dados no console. 

'''
comentar sem o uso #

'''
#  cont+: comenta todo texto selecionado

print(texto)
print(numero_inteiro)
print(numero_real)
print(dado_boleano)

# type() - verificar tipo de texto

print(type(texto))
print(type(numero_inteiro))
print(type(numero_real))
print(type(dado_boleano))

# concatenação == juntar textos, variaveis, resultados
 
text = type(texto)
inteiro = type(numero_inteiro)
real = type(numero_real)
boleano = type(dado_boleano)

print('Essa variavel ->', texto, 'é da', text )
print('Essa variavel ->', numero_inteiro, 'é da', inteiro )
print('Essa variavel ->', numero_real, 'é da', real )
print('Essa variavel ->', dado_boleano, 'é da', boleano )

print(f'Essa variavel ->  {texto} é da  {text} ' )
print(f'Essa variavel ->  {numero_inteiro} é da  {inteiro} ' )
print(f'Essa variavel ->  {numero_real} é da  {real} ' )
print(f'Essa variavel ->  {dado_boleano} é da  {boleano} ' )

#---------------------------------------------------------------------------------------
# constante
nome = 'Fernando'
nome = 'Jr'
print(nome)

NOME = 'Caio' # não altere
NOME = 'Karol'
print(NOME)

def nome():
    name = 'Maria'
    return name

NOME = nome()
print(NOME)

# operadores aritiméticas
print(10//10)

# entrada de dados
nome = input('digite seu nome: ')
# print(nome)

#--------------------------------------------
numero1 = int(input('>>'))
numero2 = int(input('>>'))

calcular = numero1 * numero2
print(calcular)

numero1 = int(input('>>'))
numero2 = int(input('>>'))

calcular = numero1 / numero2
print(calcular)


***CRIE UM CALCULADORA COM INPUT() PRINT() VARIÁVEIS***
 

numero1 = int(input('>>'))
numero2 = int(input('>>'))


calcular_mult = numero1 * numero2

calcular_div = numero1 // numero2

calcular_sub = numero1 - numero2

calcular_soma = numero1 + numero2

print('resultado da multiplcação:', calcular_mult )
print('resultado da divisão:', calcular_div )
print('resultado da subtração:',  calcular_sub )
print('resultado da soma:', calcular_soma) 

----------------------------------------

lista (array)
numero = 10
# lista (array)
numeros = [10,2,3,5,'a',True, 8.0]
#print a lista inteira
print(numeros)
#print um indice da lista
print(numeros[5])

#manipulando lista
lista = [10,15,3,1,5]
indice = lista[0]
indice2 = lista[1]

print(indice, indice2)

 criar lista automatico
numeros1 = list(range(1,11))
print(numeros1)

comprimento de lista ==len

lista = [10,15,3,1,5]
print(len(lista))

#add == append()
lista.append(10)
print(lista)

#transformar uma variavel em uma lista do tipo str
variavel = 'text'
lista2 = list(variavel)
print(lista2)

#criar uma lista com list()
criar_sequencia = list(range(1,101))
soma = sum(criar_sequencia)
print(criar_sequencia)
print(soma)

#max e min
menor = min(criar_sequencia)
print(menor)

maior = max(criar_sequencia)
print(maior)
 

 organizar uma sequencia
lista3 = [5685,32158,3215,6952,7842,5154,5]
organizar = sorted(lista3, reverse=True)
print(organizar)


#pop() -> remove um indice
lista3.pop(0)
print(lista3)

del lista3[0]
print(lista3)

lista3.remove(7842)


tuplas() -> são listas imutaveis e esa se parenteses.

tupla = (15,25,63,94,2)
print(tupla)
print(tupla[3])
print(tupla[-2])
#conta qual o valor que se repete
contador = tupla.count(2)

#verificar o indice do valor
indice = tupla.index(63)
print(contador, indice)

#tamanho len
print(len(tupla))

#tuple() transforma uma lista em uma tupla

#max e mim
maior = max(tupla)
menor = min(tupla)
print(maior, menor)

#ordenar 
ordenar = sorted(tupla)
print(ordenar)

sorted(tupla)
a,b,c,d,e= tupla

print(a,b,c,d,e)

conjuntos {} ou set([])

nome = {1,2,3,6,4,5,9,10}
conjunto2 = { 9,8,5,4,7}
print(nome|conjunto2)
print(nome)

intercecção = nome & conjunto2
print(intercecção)

diferenca = nome - conjunto2
print(diferenca)

dif_simetrica = nome ^ conjunto2
print(dif_simetrica)

#dicionario ou dic{}
dicionario = {
    'nome': 'marcelo',
    'idade': 46,
    'endereço': 'rua 100',
    'curso': 'python60h',
}
print(dicionario)

print(dicionario['idade'])


#desafio 

aluno1=float(input('digite todas as notas:'))
aluno2=float(input('digite todas as notas:'))
aluno3=float(input('digite todas as notas:'))

notas = n1,n2,n3,n4

media = n1+n2+n3+n4/4
nota_maior = max(notas)
nota_menor = min(notas)
print('''
'aluno1,media,nota_maior,notamenor


''')
