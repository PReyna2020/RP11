# RP11
RP1 inventory

# THis is sample code for inventory choices
RP1_inventory = {
 'RP1.1': 'blend1',
 'RP1.2': 'Blend2',
 'RP1.3': 'Blend3',
 'RP1.4': ['7 lbs', '5 lbs', '10 lbs'],
 'RP1.5':{'RP1.05': '1000'}
         }

lbs = int(input("How many pounds?"))
roast_level = input("Medium or Dark?")
medium = ("lbs * 1.15")
dark = ("lbs * 1.25")

