# currencey-converter

import time
print ("Welcome to the currency converter.")
time.sleep (1)
Choice1 = input ("What currency would you like to convert from? (GBP or USD) ")
if Choice1 == "GBP":
  GBP = float(input("Input your amount in Pounds. £"))
  USD = (GBP * 1.3887)
  Choice1 = input("Do you want that in USD? ")
  if Choice1 == "yes" or "Yes" or "y":
    print ("£",GBP, "is equal to:")
    print ("$", USD)
  elif Choice1 == "no" and "No" and "n" and "NO":
    print ("Thank you for using my code! ")
###################################################
elif Choice1 == "USD":
  USD = float(input("Input your amount in Dollars. $"))
  GBP = (USD * 0.72009793)
  Choice2 = input("Do you want that in GBP? ")
  if Choice2 == "yes" and "Yes" and "y":
    print ("$",USD, "is equal to:")
    print ("£", GBP)
  elif Choice2 == "no" and "No" and "n" and "NO":
    print ("Thank you for using my code! ")
