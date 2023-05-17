 CalendarDisplay
Python Program to Display Calendar
 Program to display calendar of the given year and month

 importing calendar module
import calendar

yy = 2023  # year
mm =  5   # month
dd = 17  # day
 To take month and year input from the user
 yy = int(input("Enter year: "))
 mm = int(input("Enter month: "))
 dd = int(input("Enter day: "))
 display the calendar
print(calendar.month(yy, mm))
