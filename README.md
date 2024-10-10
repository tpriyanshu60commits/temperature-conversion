# temperature-conversion
unit = input("enter the temperature unit C or F - ")
temp = int(input("enter the temperature - "))

if unit == "C":
    temp = round((9*temp)/5+32,1)
    print(f"the temperature in celcius is {temp}")
    
elif unit == "F":
    temp = round((temp-32) * 5/9 , 1)
    print(f"the temperature in fahrenheit is {temp}")
    
