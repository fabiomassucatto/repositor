��#   r e p o s i t o r 
 
 "repositorio de projetos de aprendizado"
import os
dicionario={}
while True:
 opção=int(input("0-sair 1-adicionar item  2-mostrar item"))
 if opção == 0:
     print(dicionario)
     break
 elif opção == 1:
    nome=input("qual o nome do produto?")
    valor=int(input("qual valor do produto"))
    dicionario[nome]=valor
