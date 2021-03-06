# Learn Python the Hard Way Book 

This is a summary of [this book](https://learnpythonthehardway.org/book/) designed by us.
>The python version is 2.X .

#### Exercise 1: A Good First Program
* Just the usage of `print` function. 
<br>For example: `print "This is fun."`

#### Exercise 2: Comments And Pound Characters
* Comment sentences by putting `#` character. 
<br>For example: `print "This is not a comment." # but this is a comment`
* This is one of the Exceptions:  ` # -*-  coding: utf-8  -*-` Because this line will help you to use Unicode UTF- 8 without a problem.

#### Exercise 3: Numbers And Math
* This exercise talk about order of operations and use the programming language as a calculator. 
<br>For example `print "Wow", 25 + 30 / 6` will show like this: `Wow 30`

#### Exercise 4: Variables And Names
* Use this style for variable names: `character(s)_character(s)_character(s)`.
<br>For example: `cars`, `space_in_a_car`.

#### Exercise 5: More Variables And Printing
* You can use variables and their format characters in the print.
<br>For example: `print "%s,I get %d." % (my_name, my_age + my_height + my_weight)`

#### Exercise 6: Strings And Text
* We use `%s` for strings as the formatter.
* `%r` can be used for all type of variables, this is raw.
* You can concatenate strings with `+`.

#### Exercise 7: More Printing
* You can print strings multiple times by `*`.
<br>For example: `print "." * 10`

#### Exercise 8: Printing, Printing
* You can create formatter like this: `formatter = "%r %r %r %r"`

#### Exercise 9: Printing, Printing, Printing
* Use `\n` when you want to go to the next line.
* Use `"""` when you want to print exactly what you have typed, even when you go to the next line **without** \n.

#### Exercise 10: What Was That?
* `\t` is horizontal tab(4 spaces).
* You should use `"\\"` for printing `\`.

#### Exercise 11: Asking Questions
* Use `raw_input(prompt)` when you want to get an input from the client in the runtime.
<br>For example: `age = raw_input("> ")`. And you can cast the input to integer like this: `age = int(raw_input("> "))`

#### Exercise 12: Prompting People
* You can ask the question as the **prompt** in the **raw_input** like this: `variable = raw_input(question_string)`

#### Exercise 13: Parameters, Unpacking, Variables
* look at this:
> from sys import argv
<br><br>script, first, second, third = argv
<br><br>print "The script is called:", script
<br>print "Your first variable is:", first
<br>print "Your second variable is:", second
<br>print "Your third variable is:", third

you should give four argument when you want to run the file and python will use them.
<br>One of them is the .py file that always you write it but here you should give three more.

#### Exercise 14: Prompting And Passing
#### Exercise 15: Reading Files
#### Exercise 16: Reading And Writing Files
#### Exercise 17: More Files
#### Exercise 18: Names, Variables, Code, Functions
#### Exercise 19: Functions And Variables
#### Exercise 20: Functions And Files
#### Exercise 21: Functions Can Return Something
#### Exercise 22: What Do You Know So Far?
#### Exercise 23: Read Some Code
#### Exercise 24: More Practice
#### Exercise 25: Even More Practice
#### Exercise 26: Congratulations, Take A Test!
#### Exercise 27: Memorizing Logic
#### Exercise 28: Boolean Practice
#### Exercise 29: What If
#### Exercise 30: Else And If
#### Exercise 31: Making Decisions
#### Exercise 32: Loops And Lists
#### Exercise 33: While Loops
#### Exercise 34: Accessing Elements Of Lists
#### Exercise 35: Branches and Functions
#### Exercise 36: Designing and Debugging
#### Exercise 37: Symbol Review
#### Exercise 38: Doing Things To Lists
#### Exercise 39: Dictionaries, Oh Lovely Dictionaries
##### This section introduces a new collection in python, Dictionary.
> Dictionary exists in other languages but has different names --> ex. 'hashes'.
>
* Unlike lists, in dictionaries the key set has not to be numeral index, you can use other keys defined by yourself. <br />
Example:<br />
` stuff = {'name': 'Zed', 'age': 36, 'height': 6*12+2} `
* if you want to remove a key-value set from a dictionary you shall do as following: <br />
	`del stuff[name]` 
* the other differnece between lists and dicts is in for loops: <br />
	` for value in stuff.items() `<br />


#### Exercise 40: Modules, Classes, And Objects
> Python is an OOP language, just like java
>
* A module is a Python file with some functions or variables in it.<br />
`# this goes in module.py`<br />
`def apple():` <br />
	`		print "I AM APPLES!" `<br />

to use that module in another project: <br />
` import module` <br />
` module.apple()` <br />

* A class is a way to take a grouping of functions and data and place
them inside a container so you can access them with the '.' (dot) operator.
###### Class syntax
`class MyStuff(object):` <br />
`def __init__(self):` <br />
`self.tangerine = "And now a thousand years between"` <br />
`def apple(self):` <br />
`print "I AM CLASSY APPLES!"` <br />
###### in order to instantiate
`thing = MyStuff()` <br />
`thing.apple()` <br />
`print thing.tangerine` <br />
#### Exercise 41: Learning To Speak Object Oriented
> OOP has its special talking rules
>
* remember uasage of is-a and has-a <br />
is-a is a phrase to represent relationship between classes and objects <br />
has-a is a phrase to represent relationship between objects and attributes <br />
* composition: a car has wheels, car and wheel are separated classes but a class can contain another, this is called composition in python.
> other concepts have been discussed in advanced programing course.
>
#### Exercise 42: Is-A, Has-A, Objects, and Classes
#### Exercise 43: Gothons From Planet Percal #25
#### Exercise 44: Inheritance Vs. Composition
#### Exercise 45: You Make A Game
#### Exercise 46: A Project Skeleton
#### Exercise 47: Automated Testing
#### Exercise 48: Advanced User Input
#### Exercise 49: Making Sentences 
#### Exercise 50: Your First Website
#### Exercise 51: Getting Input From A Browser
#### Exercise 52: The Start Of Your Web Game
