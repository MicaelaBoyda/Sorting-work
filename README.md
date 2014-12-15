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
    




