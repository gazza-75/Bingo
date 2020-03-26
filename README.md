# Bingo

A simple Bingo game that runs number 1-99 to play using UK mobile numbers

To install you need include pygame libraries:
python3 -m pip install -U pygame --user

Players use their UK mobile number to play this gives them 5 numbers to work with eg:
07325763241 would transform into 73-25-76-32-41 dropping the leading zero
If you have a number that repeats numbers eg:
07323232323 this transforms to 73-23-23-23-23 you would add +1 to each duplicate until you had 73-23-24-25-26
