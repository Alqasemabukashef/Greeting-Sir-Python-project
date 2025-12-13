# Greeting-Sir-Python-project

##Create a Python program that greets you with Good Morning, Good Afternoon, and Good Evening. Your program should use time module to get the current hour.

## Here a code  
"""

import time
import datetime
timestamp = time.strftime('%H:%M:%S')
print(timestamp)


timestamp = time.strftime("%H")
print(timestamp)

timestamp = time.strftime("%M")
print(timestamp)
timestamp = time.strftime("%S")
print(timestamp)

current_time = datetime.datetime.now()

hour = current_time.hour

if ( 5 <= hour < 12 ):
    print("Good Moring!")
elif ( 12 <= hour < 18 ):
    print("Good Afternoon!")
else:
    print("Good Evening!")






"""
