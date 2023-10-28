# Jogo-Do-Dado-Em-Python
Jogo Do Dado Em Python

import random

dado2 = 0
dado3 = 0
dado4 = 0
dado5 = 0
dado6 = 0
dado7 = 0
dado8 = 0
dado9  = 0
dado10 = 0
dado11 = 0
dado12 = 0

for i in range(5):
    dado1 = random.randint (1,6)
    dado2 = random.randint (1,6)
    soma = dado1 + dado2

if soma == 2:
        dado2+= 1
elif soma == 3:
        dado3+= 1
elif soma == 4:
        dado4 += 1
elif soma == 4:
        dado4 += 1
elif soma == 5:
        dado5 += 1
elif soma == 6:
        dado6 += 1
elif soma == 7:
        dado7 += 1
elif soma == 8:
        dado8 += 1
elif soma == 9:
        dado9 += 1
elif soma == 10:
        dado10 += 1
elif soma == 11:
        dado11 += 1
elif soma == 12:
        dado12 += 1


print('2: ' + str(dado2))
print('3: ' + str(dado3))
print('4: ' + str(dado4))
print('5: ' + str(dado5))
print('6: ' + str(dado6))
print('7: ' + str(dado7))
print('8: ' + str(dado8))
print('9: ' + str(dado9))
print('10: ' + str(dado10))
print('11: ' + str(dado11))
print('12: ' + str(dado12))

