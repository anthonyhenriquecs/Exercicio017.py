# Exercicio017.py
#Faça um programa que leia o comprimento do cateto oposto e do cateto adjacente de um triângulo retângulo. Calcule e mostre o comprimento da hipotenusa.
#co = float(input('digite o cateto oposto: '))
#ca = float(input('digite o cateto adjacente: '))
#hi = (co ** 2 + ca ** 2) ** (1/2)
#print('A hipotenusa vai medir {:.2f}'.format(hi))

import math
co = float(input('digite o cateto oposto: '))
ca = float(input('Digite o cateto adjaceente: '))
hi = math.hypot(co,ca)
print('sua hipotenusa sera: {:.2f}'.format(hi))
