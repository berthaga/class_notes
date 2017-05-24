variables are nothing but reserved memory locations to store values

Types of values
numbers(int-signed integers, long-represented in octal and hexadecimal, float-decimal numbers, complex)
tuples
strings---anything that starts with a quotation and ends with a quotation
dictionary

list-----starts and ends with a square bracket which contains different values seperated by commars.
NB: list is a type of variables

car="toyota"  ...... setting a variable
counter=100  ...... setting a variable
miles=99.2   ...... setting a variable
worker=programmer=student="bertha" .....assigning different variables to the same value
worker,programmer,student="alex","betty","kwesi" ....assigning the different variables to their perspective values
worker=student..... the output for worker is now kwesi, student is still kwesi
print worker,programmer........ the output will be alex betty
food="jollof watche"
food[5]----the output is f. NB: f is in the 5th position in the jollof watche string

>>> time=raw_input("what time is it ?:")
what time is it ?:Hello world time
>>> time
'Hello world time'
>>> print time
Hello world time
>>> time[6]
'w'
>>> print time[6]
w
>>> print time[6:11]
world
>>>
python_class=["bertha","alex","suley","samra","kwesi","solomon"]----an example of list. 
>>> python_class
['bertha', 'alex', 'suley', 'samra', 'kwesi', 'solomon']
>>> print python_class
['bertha', 'alex', 'suley', 'samra', 'kwesi', 'solomon']
>>> food=["banku","rice"]
>>> print python_class,food
['bertha', 'alex', 'suley', 'samra', 'kwesi', 'solomon'] ['banku', 'rice']
>>> python_class+food
['bertha', 'alex', 'suley', 'samra', 'kwesi', 'solomon', 'banku', 'rice']
>>> food*2
['banku', 'rice', 'banku', 'rice']
>>> del food....... it deletes the variable food