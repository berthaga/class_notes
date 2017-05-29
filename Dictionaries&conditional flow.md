27/05/2017

examples of Dictionaires
>>> food={}
>>> food['rice']='jollof'
>>> food['maize']='banku'
>>> food
{'maize': 'banku', 'rice': 'jollof'}
>>> food['vegetable']='carrot'
>>> food.keys()
['vegetable', 'maize', 'rice']
>>> print food
{'vegetable': 'carrot', 'maize': 'banku', 'rice': 'jollof'}
>>> food.vales()
>>> food.values()
['carrot', 'banku', 'jollof']
>>>

conditional flow
where a code runs based on the outcome of the first code

NB: To run a python script, first save the text file in python, go to the cmd and cd to the where the file is saved.
Then type python then the name of the python file.

#Example One
name='Bertha'
female='Bertha'
if name==female:
	print "Welcome"
else:
	print "No"


#Example Two
name='Bertha'
female='Alex'
if name==female:
	print "Welcome"
else:
	print "No"


#Example Three
name=raw_input("what is your favourite car?:")
if name=="range rover":
	print 'Tata'
else:
	print name

#Example Four
name=raw_input("what is your favourite car?:")
if name=="range rover":
	print 'Tata'
else:
	print name	
	new_Nmae=raw_input("Manufacturer?")
	print "It was manufactured by " +  new_Nmae


#Example Four
name=raw_input("what is your favourite car?:")
if name=="range rover":
	print 'It wa manufacftured by Tata'
elif name=="toyota":
	print 'It wa manufacftured by Toyota'
else:
	print "I don't know"