# RP11
RP1 inventory


lbs = int(input("How many pounds?"))
roast_level = input("Medium or Dark?")
medium = ("lbs * 1.15")
dark = ("lbs * 1.25")


# THis is sample code for inventory choices
RP1_inventory = {
 'RP1.1': 'blend1',
 'RP1.2': 'Blend2',
 'RP1.3': 'Blend3',
 'RP1.4': ['7 lbs', '5 lbs', '10 lbs'],
 'RP1.5':{'RP1.05': '1000'}
         }
         
 #Second sample library idea/notes/calculations
 
 RP1_inventory = {

#10 lbs        = YIELD 8.5 lbs after roasted (15% volume loss)
#Medium Roast  = .15 loss after roasting
#Dark Roast    =.25 loss after roasting

 'RP1Brazil':80,
 
 'RP1Guatamula':50,
 
 'RP1Uganda':50,
 
 'RP1Vietnam':50
        
}

MED  = 0.85
Dark = 0.75

Bitcoin = 57980.58
My_Bitcoin = Bitcoin_Holdings * Bitcoin

print("You have {BTC:3.2f} of Brazil Roast.".format(BTC=My_Bitcoin))
print("You have {BTC:3.2f} of Guatumala Roast.".format(BTC=My_Bitcoin))
print("You have {BTC:3.2f} of Uganda Roast.".format(BTC=My_Bitcoin))
print("You have {BTC:3.2f} of Vietnam Roast.".format(BTC=My_Bitcoin))

print(RP1_inventory)


