command = ""
command = input('Any waves out there? (y/n)_ ')


import random

class Dice:
    def roll(self):
        first = random.randint(1, 6)
        return first

dice = Dice()
print (dice.roll())

if command == ('y'):
    input('Feet, but fun! say is that trade wind heading here? y/n:')
if command == ('n'):
        print('feet but fun ..  paddle out for sure!!!')


Skateboard = ""
skateboard =input(
                  '...Some time later... Woah gnarly brah sick ride. After this burrito We should go skate, '
                  'is it about to rain? (y/n)_')
if skateboard == ('y'):
    print('what?, skunked! denied! no skate sesh dang')
elif skateboard == ('n'):
    print("Its on!!!  skate and destroy! fully!!  lets rip at skate park")
import random

while True:
    input("press enter for surf check in feet")
    d20 = random.randint(1,20)
    print(d20)
    if d20 == 1:
        print('dang brah, flat huh..  ')
    elif d20 == 20:
        print("livin da california dream")
    elif d20 == 10:
        print ("OUT THERE!!!  ...YYyyeeewwww!!!!")
