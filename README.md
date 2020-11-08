# Making-Of-Reminder-in-Python
I have made a reminder in python, in which user will enter the reminder and time after which he/she has to be reminded. Then, after that time he/she will get reminded.


import datetime
reminder=input("Enter the Reminder")
time_=int(input("After how much time you want to be reminded?/ Please enter the time in hours."))
time_=time_*3600
time.sleep(time_)
print(reminder)
