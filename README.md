# 01/18/2015
# Capstone project
# Benefit and Cost Function

import math

def benefit(x):
    return math.log(x)

def cost(y):
    return 2*y
    
def profit(z):
    return benefit(z)-cost(z)

print profit(5)


