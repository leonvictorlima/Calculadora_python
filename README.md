<h1 align="center">Calculadora em Python</h1>

<h1 align="center">
  <img src="https://github.com/leonvictorlima/Calculadora_python/blob/main/imagens/calculadora.png"  width="500"/>
</h1>

Este repositório é apenas um exemplo divertido da utilidade de python. Podemos desenvolver diversas atividades com linguagem de programação, pois o que vale é nossa imaginação. Mas não se engane, este código apresenta algumas aplicações úteis, pois apresenta a utilização de funções e condicionais;

Abaixo encontra-se o código do modelo e seu total conteúdo está disponível neste mesmo repositório aqui no #Github

```python
# -*- coding: utf-8 -*-
"""
Created on Thu Sep  3 11:33:46 2020

@author: Leon Victor 
"""

#Objetivo: Criar uma calculadora para efetuar operações básicas;

print("\n1 - Soma\n 2 - Subtração\n 3 - Multiplicação\n 4 - Divisão")

opcao= int(input("Entre com a opção na calculadora: "))

# Define as equações de nossa calculadora

def soma(arg01, arg02):
        return arg01 + arg02
    
def subtracao(num01, num02):
        return num01 - num02

def multiplicacao(arg01, arg02):
        return arg01 * arg02

def divisao(arg01, arg02):
        return arg01/arg02

# Seleciona o modo que foi escolhido, ou seja, soma, subtração, multiplicacao ou divisao;

if opcao == 1:
    arg01 = int(input("Entre com o primeiro valor: "))
    arg02 = int(input("Entre com o segundo valor: "))
    print("O valor da soma é: "+ str(soma(arg01,arg02)))

elif opcao == 2:
    arg01 = int(input("Entre com o primeiro valor: "))
    arg02 = int(input("Entre com o segundo valor: "))
    print("O valor da subtração é: "+ str(subtracao(arg01,arg02)))

elif opcao == 3:
    arg01 = int(input("Entre com o primeiro valor: "))
    arg02 = int(input("Entre com o segundo valor: "))
    print("O valor da subtração é: "+ str(multiplicacao(arg01,arg02)))

elif opcao == 4:
    arg01 = int(input("Entre com o primeiro valor: "))
    arg02 = int(input("Entre com o segundo valor: "))
    print("O valor da subtração é: "+ str(divisao(arg01,arg02)))

else:
    print("Valor inválido, tente novamente.")


```
