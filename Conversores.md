# Python-Aulas
num = int(input('Digite um numero inteiro: '))
print('''Escolha uma das bases de conversão: 
[1]Binario
[2]Octal
[3]Hex''')
op = int(input('Sua opção: '))
if op == 1:
  print('{} em binario é {}'.format(num,bin(num)[2:]))
elif op == 2:
  print('{} em octal é {}'.format(num,oct(num)[2:]))
elif op == 3:
  print('{} em hex é {}'.format(num,bin(num)[2:]))
else:
  print('Opção invalida, tente de novo')
