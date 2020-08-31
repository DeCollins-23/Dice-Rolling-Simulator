# Dice-Rolling-Simulator
The program simulates a four sided rolling dice and randomly picks a number on the dice that is between 1 and 6. It iterates continuously as long as the condition is true.


def verify(number):
  number=int()
  w=2
  x=3
  y=3
  z=4
  dice=[w,x,y,z]
  length=len(dice)
  while True:
    for number in range(length):
      if (number>1 and number<6):
        return 3
      else:
        return 2
    else:
      return 5
  else:
    return 4

value=print("Enter dice number\n:")
print(random.randint(2,5)) 






















