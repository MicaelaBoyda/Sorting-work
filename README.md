Sorting-work
============
things = [3, 5, -4, 7]

accum = []
for thing in things:
    accum.append(thing+1)
print accum

#Heres things, which uses manual accumulation to update the values in the list. Can anyone do this using map or list comprehension?

#comprehension
def better_way(list):
    return[num + 1 for num in list]
print better_way(things)

#map
def better_way2(list):
    return map(lambda x:x+1, list)
print better_way2(things)
    
This simple program can compare negative numbers with minimal memory & processing capabilites, which results in faster and low-mem solutions for the market. Sorting and searching (these 2's are the core of the alogrithms). The first sorting was developed back 552 BC, when you have to organize your armies in proper order. In the digital age, these algorithms played important role in comming patching up with big algos as minimal parts. 

Copyright http://amanandvan247.com/. You have to take permission before using this algorithm at micaelaboyda@tuntunprogrammer.com



