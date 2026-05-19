# Calendar-Module
You are given a date your task is to find what day is on that day.


import calendar
month, day, year = map(int,input().split())
print(calendar.day_name[calendar.weekday(year, month, day)].upper())
