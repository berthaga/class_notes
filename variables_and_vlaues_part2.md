26th/5/2017

print set of information using raw data

>>> data=raw_input("what is your name,age,status,why?:")
what is your name,age,status,why?:betha,10,student,learn to code
>>> print data
betha,10,student,learn to code
>>>

An example of a list 

>>> food=["banku,rice,kenkey"]
>>> print food
['banku,rice,kenkey']

creating a tuple

Tuples are just like lists. 
The differences between tuples and lists are, 
the tuples cannot be changed unlike lists and tuples use parentheses, 
whereas lists use square brackets. 
>>> cars=("toyota","benz","ford","fanta","coke")
>>> print cars[3]
fanta
>>>

creating a dictionary
Any key of the dictionary is associated (or mapped) to a value. 
The values of a dictionary can be any Python data type. 
So dictionaries are unordered key-value-pairs.

>>> food={}
>>> food["rice"]="jollof"
>>> food
{'rice': 'jollof'}
>>> food={"rice":"jollof","drink":"coke"}
>>> food
{'rice': 'jollof', 'drink': 'coke'}
>>> print food["rice"]
jollof
>>> print food
{'rice': 'jollof', 'drink': 'coke'}
>>> print food["drink"]
coke
>>>

Python Comparison Operators
These operators compare the values on either sides of them and decide the relation among them.
>>> home="ash"
>>> location="tema"
>>> home==location
False
>>> home!=location
True
>>> home=location
>>> home==location
True
>>> home!=location
False
>>>
