n1 = 0
n2 = 0
resultado = 0
operação = ''

n1 = int(input('Digite o numero 1: '))
operação = input('Digite a operação: ')
n2 = int(input('Digite o numero 2: '))

if  operação == '-':
  resultado = n1 - n2
elif  operação == '+':
  resultado = n1 + n2
elif  operação == '/':
  resultado = n1 / n2
elif  operação == '*':
  resultado = n1 * n2

print(str(n1) + ' ' + str(operação) + ' ' + str(n2) + '=' + str(resultado))
