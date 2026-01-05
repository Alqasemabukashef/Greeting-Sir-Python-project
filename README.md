# Greeting-Sir-Python-project

##Create a Python program that greets you with Good Morning, Good Afternoon, and Good Evening. Your program should use time module to get the current hour.

## Here is a code  
"""
## Solution 1
```
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
```
__________________________________________
## Solution 2
```

import time
timestamp = time.strftime('%H:%M:%S')
print(timestamp)
hour = int(time.strftime('%H'))
hour = int(input(" Enter hour:  "))
print(hour)

if (0 <= hour <12  ):
    print( "Good Morning Sir!")

elif(12 <= hour < 16  ):
    print( "Good Afternoon Sir!")

elif(16 <= hour < 21  ):
    print( "Good Evening Sir!")
 
else:
   print("Good Night Sir!")
```





