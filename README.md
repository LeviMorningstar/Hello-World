# Hello-World

from math import hypot
co = float(input('Qual o valor do cateto oposto? '))
ca = float(input('Qual o valor do cateto adjacente?'))

hi = hypot(co, ca)

print('O valor da Hipotenusa é igual a {:.2f}'.format(hi))
