# working-with-dates-times

here i will specify how to use all this dates and times formats

YYYY, MM, DD, HH, MM, SS
1996, 04, 16, 15, 45, 55

this represents 3:45pm and 55 seconds on april 16 1996

the order and syntax foe this is
year four digits
mounth 0-11
day 1-31
hour 0-23
minutes 0-59
seconds o-59
milliseconds 0-999

another way to format the date and time is like this MM DD, YYYY HH:MM:SS
apr 16 1996 15:45:55

you can omit the time portion if you do not need it

in this example you can see a date being set in the past
if you try to find the difference between two dates you will and up with result in milliseconds
to get the difference in days/weeks/years you divide
this number by the number of milliseconds in a day/week/year
here the number is divided by 31,556,900,000-the number of milliseconds in a year (that is not a leap year)...
