# weekday.py
import datetime

weekno = datetime.datetime.today().weekday()

if weekno < 5:
    print ("Yes, unfortunately today is a weekday")
else: print ("It is the weekend, yay!")
