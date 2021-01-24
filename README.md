#masks, just a boolean value for now
masks = True
#number of people
people = 3
#ventilated space, also a boolean value
ventilation = True
#distancing, boolean
distancing = True
#time, number of minutes
time = 60

print((((-1)*masks + 2) * 5 * people) + (30*((-1)*ventilation + 1))+ (20*((-1)*distancing + 1))+ (2*((time - 15)/10)))
