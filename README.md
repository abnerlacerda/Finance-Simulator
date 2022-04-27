# Finance-Simulator
 This simulator will do a simulation from contribution financer and return one balance with your contribution.

#PYTHON

s = int(input('Enter your bank balance: \n'))

a = int(input('Enter your monthly contribution:\n'))

m = int(input('Enter the number of months you want to make the contributions:\n'))

ac = 0

contador = 1

while contador <= m:
  ac = s + a + ((s+a)*0.0075885)
  s = ac
  contador = contador + 1

  
print('Final balance in ', m, 'months is R$' , s )
