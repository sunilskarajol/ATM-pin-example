# ATM PIN EXAMPLE
pin="1234"
trials=1 
while trials<=3:
    input_pin=input(f"trial-{trials} pin>>")
    trials+=1
    if input_pin==pin:
        print("correct")
        break
    else:
        print("incorrect")
