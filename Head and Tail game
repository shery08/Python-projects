c = 0
p = 0
r = 0
import random
print ("Heads & Tails game:")
print ("===================")
N = input ("\nWhat is your Name? ", )
print ("\nHey " + N + "!! This is a simple game which we were used to play in our chilhood.\n\nRules:\n 1)First computer will bat.\n 2)You can choose any number between 1 to 6.\n 3)You cannot choose numbers greater than 6 or smaller than 1.\n 4)When computer will bat, you have to guess the number to out the computer.\n 5)When you bat, if computer guessed your chosen number you would be out.\nSo try to guess computer's number as soon as possible when you bowl and try to avoid number to be guessed when you bat.")
print ("\nComputer is batting now.")
while (c == 0) : #when computer bats
  w = random.randint(1,6)
  a = -1
  while (a <= 0 or a > 6):
    a = input ("\nGuess a number: ", )
    a = eval (a)
    if (a <= 0 or a > 6):
      print ("Remember! You cannot guess numbers greater than 6 or smaller than 1.")
  if a == w :
    s = p + 1
    print ("\nBingo! You made the correct guess..\nThe computer had scored ", p ,"runs.\n\nMeans you have to score atleast " , s , "runs.") 
    c = c + 1
  else :
     print ("\nComputer chose ", w ,"run(s).")
     p = p + w
     print ("Computer had scored a total of " , p , "run(s).")
print ("\nNow its your turn to bat!")
print ("Remember! Try to avoid number to be guessed.")
while (c == 1 and p >= r):
  x = random.randint(1,6)
  b = -1
  while (b <= 0 or b > 6):
    b = input ("\nMake a score: ", )
    b = eval (b)
    if (b <= 0 or b > 6):
      print ("Remember! You cannot choose number greater than 6 or smaller than 1.")
  if  b == x:
    print ("Alas! You got out! You had scored ", r ,"runs.")
    c = c + 1
  else:
    print ("\nComputer guessed ", x ,"run(s).")
    r = r + b
    print ( b ," runs added to your total score. You have score a Total of ", r ,"run(s).")
    if r < s :
      m = s - r
      print ("You need ", m ," more run(s).")
if ( r == p ):
  print ("The match had been drawn!!")
if ( r > p ):
  print ("\nCongratulations " + N + "! You have defeated the computer..😎")
