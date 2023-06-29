# CodeclauseRandompassswordgenerator
#Python program for Generating a Random Password

import random
lower = "abcdefghijklmnopqrstuvwxyz"
upper = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
numbers = "0123456789"
symbols = "!@#$%^&*()[];'./,?"
string = lower + upper + numbers + symbols
length = 15
password = "".join(random.sample(string,length))
print("Your new password is: ", password)
