# Aula 1 - Instalação da Linguagem Python e Introdução a variáveis

## Python
A linguagem Python foi desenvolvida por Guido van Rossum no ano de 1991. Sendo muito utilizada para:
* Desenvolvimento web (server-side)
* Desenvolvimento de software
* Matemática, Ciência de Dados, Estatística
* Machine Learning

Python é uma linguagem que trabalha em diversos sistemas operacionais (Linux, Windows, Mac, etc.). Possui uma sintaxe simples, utilizando como base a língua inglesa e foi desenvolvida com o intuito de fácil interpretação.

Hoje, em 2024, o Python é a linguagem mais utilizada no mundo. Possui muitas bibliotecas e frameworks para auxiliar no desenvolvimento.

## Instalação

Acessar a página: www.python.org 
Passo a passo:  www.python.org.br/instalacao-windows 

Instalação da IDE Visual Studio Code: wwww.code.visualstudio.com/download
Instalação da IDE PyCharm: www.jetbrains.com/pt-br/pycharm

#### Extensões do Visual Studio Code
* Python
* autoDocstring 
* Python Extension Pack
* Visual Studio IntelliCode

## Começando com Python

Nosso primeiro código: Hello World!
~~~python
print("Hello World!!")
~~~ 

#### Entendendo as variáveis
* String: Cadeia de caracteres
* Int: Números inteiros
* Float: Armazena valores reais ou flutuantes, que contêm casas decimais. 
* Double: Parecido com o float, mas é capaz de armazenar um número maior de casas decimais.

Criando uma variável do tipo Int:
~~~python
x = 5
~~~

Criando uma variável do tipo String:
~~~python
x = "DeMolay"
~~~

Criando uma variável do tipo Float:
~~~python
x = 3.0
~~~

Realizando uma conta:
~~~python
x = 4
y = 5
m = x + y
print(m)
~~~

Descobrindo o tipo da variável:
~~~python
x = 5
y = "Cap. Londrina"
print(type(x))
print(type(y))
~~~ 

Case-sensitive:
~~~python 
a = 4
A = "Sally"
# A will not overwrite a
~~~

## Atividade:
Faça um programa que você deve informar seu nome, idade, cargo preferido, data de iniciação e quantos reais você tem na sua conta(Favor mentir nessa informação kkk). O programa deve informar o TIPO de cada informação no final do programa.