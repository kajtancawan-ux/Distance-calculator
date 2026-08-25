# Distance-calculator

https://www.programiz.com/online-compiler/4Z2GmqiAnclVj

#this code aims to help convert kilometers to miles 

 #The first line of code which is x asks for the distance in kilometers and the rest of the line calculates for kilometers to miles.
 
x = float(input("input distance in kilo meters: "))
y = 0.621371
z = x*y
print("distance in miles:",z)

#The second part asks for a second distance in kilometers, and depending on how you respond it gives another answer.

a = input("do you want another distance? yes/no: ")
if a== "yes":
    q = float(input("enter distance in kilometers: "))
    r = q*y
    print("distance in miles: ",r)
else:
    print("program ended.")
    
#if you give another distance in kilometers, it calculates for it and if none then the program ends.
    
