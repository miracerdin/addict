# addict
Addict question
Are you a cigarette addict older than 75 years old?→ age
Do you have a severe chronic disease? Variable → chronic
Is your immune system too weak? Variable → immune
Set a logical algorithm using boolean logic operators (and/or) and use if-statements with the given variables in order to print out us a message : "You are in risky group"(if True ) or "You are not in risky group" (if False).
age =  # can be assigned only True/False
chronic =  # can be assigned only True/False
immune =  # can be assigned only True/False
risk = ?

age = input("Are you a cigarette addict older than 75 years old? y/n: ")

chronic = input("Do you have a severe chronic disease? y/n: ")

immune = input("Is your immune system too weak? y/n: ")

if age == "y" or chronic == "y" or immune == "y":

    print("You are in risky group")
    
else:

    print("You are not in risky group")
