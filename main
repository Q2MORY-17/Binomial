#Binomial counting statisitcs

import math
import time
import colorama
from colorama import Fore
colorama.init()

x = float(input("\nTotal number of trials: "))
y = float(input("Desired value for the stochastic variable: "))
z = float(input("Probability: "))

start_time = time.time()

X = float(math.factorial(x)/(math.factorial(x-y)*math.factorial(y)))*(z**y)*((1-z)**(x-y))
Y = X*100

print(Fore.LIGHTGREEN_EX+"P(Xi = %.2f)" %y,"= %.4f" %X, "\t (or %.2f" %Y, "%)\n")
print(Fore.LIGHTBLACK_EX+"Time taken: ", time.time() - start_time)
