# 100-days-of-python

## Projects
_The links will take you to a repl page where you can see the code written and to run it just click the "Run" / &#9654; button at the top of the page. (I recommend you right click and open in a new tab)_
- [Day 1 - Team Name Generator](https://repl.it/join/butaniba-rmdpalo)
- [Day 2 - Tip Calculator](https://repl.it/join/jkqjrpso-rmdpalo)
- [Day 3 - Treasure Island (text based game)](https://repl.it/join/miugjtol-rmdpalo)
- [Day 4 - Rock Paper Scissors](https://repl.it/join/plbcubfm-rmdpalo)
- [Day 5 - Password Generator](https://repl.it/join/zkqfnsyx-rmdpalo)
- [Day 6 - Reeborg Maze](https://twitter.com/MigsDev/status/1334370818885709831)
- [Day 7 - Hangman Game](https://repl.it/join/ucqmzbie-rmdpalo)
- [Day 8 - Caesar Cypher](https://repl.it/join/gzgzdfld-rmdpalo)
- [Day 9 - Secret Auction]()

## Notes
### Day 1 - Working with Variables in Python to Manage Data
Learned: 
- ```print()``` function, prints whatever is contained into the console, could be any data type or if you enter a variable it will print the value. "Hello World!" 
  - like in C \n creates a newline.
  - concatenation adding strings together _print("Ha" + "ha")_ will print "Haha"
- ```input()``` function, prompts the user for input.
  - _print("Hello " + input("What is your name?"))
    - will ask "What is your name?"
    - once a user inputs an answer, it will print "Hello Miguel"
  - ```len()``` function, gives us the length of a given string.
    - len("Miguel") will return 6.
- Declaring a variable in python: just name it meaningfully followed by a = and the value.
  - name = "Miguel"
  
Exercises: 
- [Printing to the console](https://repl.it/join/rqvtmrbw-rmdpalo)
- [Debugged print functions](https://repl.it/join/hnqygxft-rmdpalo)
- [How many chars in your name](https://repl.it/join/whwambrr-rmdpalo)
- [Switching values](https://repl.it/join/lyqifhza-rmdpalo)


### Day 2 - Understanding Data Types and Manipulating Strings
Learned:
- Primitive Data Types: 
  - String _"hello"_
    - you can refer to specific elements of a string by calling its index in brackets like 
    ```python  
      name = "Miguel"
      print(name[0]) #will return M
    ```
  - Integer _1_
  - Float _1.25_
  - Boolean _True_
- ```type()``` function, returns the data type of whatever is inputted.
- ```str()``` function, turns the input into a string data type.
- ```float()``` function, turns the input into a floating point number.
- Mathematical Operations in Python.
  - division in python will always turn the numbers into a floating point number.
- Number Manipulation
  - ```round()```, rounds input into the nearest whole number.
    - adding a second argument will determine the number of places you want to round it to.
    ```python 
      print(round(8 / 3, 2)) #will return 2.67
    ```
   - // this is the floor division operator, will return an integer for division.
   ```python
     print(8 // 3) #will return 2
   ```
    - floored means that it won't round but simply chop off whatever is not a whole number.
- f-strings allow us to print things together in a string without having to convert everything
  ```python
    score = 0
    height = 1.7
    print(f"your score is {score}, your height is {height}m")
    #will return "your score is 0, your height is 1.7m
  ```
Exercises:
- [Sum of two numbers.](https://repl.it/join/jnechydl-rmdpalo)
- [BMI Calculator](https://repl.it/join/uxtoqvma-rmdpalo)
- [Your Life in Weeks](https://repl.it/join/sgixppuc-rmdpalo)
  
### Day 3 - Control Flow and Logical Operators
Learned:
- Comparison Operators
  - \>, <, >=, <=, ==, !=
- Control Flow
  - if, elif, else
- Logical Operators
  - _and_ means they all have to be true
  - _or_ means only one has to be true
  - _not_ means it should NOT be what the condition is.
- ```.lower()``` turns strings to all lowercase
  ```python 
    "Miguel".lower() #returns "miguel"
  ```
- ```.count()``` gives us the number of times a letter occurs in a string.
  ```python
    "ayaya".count("a") # returns 3
  ```
  
Exercises:
- [Odd or Even](https://repl.it/join/gvsgefkm-rmdpalo)
- [BMI Calculator 2.0](https://repl.it/join/fztvlryq-rmdpalo)
- [Leap Year?](https://repl.it/join/cvtvuslz-rmdpalo)
- [Pizza Order](https://repl.it/join/tipztwph-rmdpalo)
- [Love Calculator](https://repl.it/join/pheuasgb-rmdpalo)

### Day 4 - Randomisation and Python Lists
Learned:
- Python's Random Module [Link](https://www.askpython.com/python-modules/python-random-module-generate-random-numbers-sequences)
  - ```random.randint(a, b)``` generates a random integer between a and b (inclusive)
  - ```random.random()``` outputs a random number between 0 and 1 not including 1.
  - ```random.seed()``` python's random module uses the current timestamp as the seed, but we can set the seed ourselves using this method.
- Python Lists [Link](https://docs.python.org/3/tutorial/datastructures.html)
  - The list is a __data structure__, it's a way of organizing and storing data in Python.
  ```python
    items = [item1, item2]
  ```
  - can be any data type, can be mixed data types.
  - indexes start from 0, _items\[0]_ gives us item1
  - you can also input negative indexes -1 will give us the last element on the list, _items\[-1]_ gives us item2.
  - ```list.append(a)``` will add the inputted element to the end of the list. i.e. _items.append(item3)_
  - ```list.extend(\[])``` will add another list to the end of a list.
  - ```string.split("")``` will split a string based on what's inputted in the function. [more info](https://www.askpython.com/python/string/convert-string-to-list-in-python)
  - You can nest lists inside another list.

Exercises:
- [Coin Flip](https://repl.it/join/pvlaruqf-rmdpalo)
- [Banker Roulette, who will pay the bill?](https://repl.it/join/dfcblpkz-rmdpalo)
- [Treasure Map](https://repl.it/join/inspblyp-rmdpalo)

### Day 5 - Python Loops
Learned:
- syntax for a for loop in python:
```python
fruits = ["Apple", "Peach", "Pear"]

for fruit in fruits:
  print(fruit + " Pie")
```
- ```sum()``` gets the total sum of all elements in a list.
```python
  scores = [1, 2, 3]
  sum(scores) #will give us 6.
```
- ```max()```/```min()```, gets the highest/lowest number in a list.
```python
  scores = [1, 2, 3]
  max(scores) #will return 3
  min(scores) #will return 1
```
- using for loops with ranges
  - the arguments inputted into the range determines the start and end of the range(second digit not inclusive)
  - if a 3rd argument is inputted into a range that shows how much the range steps over each iteration.
  - if only one argument is inputted it defaults to (0, number) ```python for number in range(6) #range(0, 6)```
```python
total = 0 
for number in range(1,101): #101 because we want it to include 100
  total += number
print(total)

for number in range(0, 13, 3):
  print(number) #this will print 0, 3, 6, 9, 12.
```
- ```random.shuffle()```
  - the second parameter is optional, if not specified it uses random.random()
```python
  random.shuffle(x, random)
```
- ```"".join(list)```, joins the list with the string in the quotes in between each element
```python
  letters = ["h", "e", "y"]
  "".join(letters) #returns "hey"
```
- += actually works on lists
```python
  letters += "o" #letters becomes ["h", "e", "y", "o"]
  #works the same as
  letters.append("o")
```
Exercises:
- [Average Height Calculator](https://repl.it/join/wcthczik-rmdpalo)
- [What is the highest score?](https://repl.it/join/nijsyfsa-rmdpalo)
- [Adding all even numbers up to 100](https://repl.it/join/mdkqltqx-rmdpalo)
- [FizzBuzz](https://repl.it/join/gdvgciug-rmdpalo)

### Day 6 - Python Functions & Karel
Learned:
- [Built in python functions](https://docs.python.org/3/library/functions.html)
- Functions in Python are written such that it is ```python function_name()``` the name followed by a set of parentheses.
- If we want to define our own functions, we have to start it off with the keyword __def__ followed by the function name with parentheses and a colon.
```python
  def my_function():
    #Do this
    #Then this
    #Then finally this
```
- To call a function we just simply type the name of the function with parentheses, and if there are arguments needed, type that in between the parentheses. ```python my_function()```
- Indentation in Python, [Python Style Guide](https://www.python.org/dev/peps/pep-0008/)
  - PEP 8 style guide dictates that indentations are 4 spaces (tragic, I've been using 2 for the previous repls)
  - While loops in Python
  ```python
    number_of_cookies = 6
    while number_of_cookies > 0:
      eat_cookie()
      number_of_cookies -= 1
  ```
  - Be wary of infinite loops :)
Exercises:
- All the exercises for this day are on [Reeborg](https://reeborg.ca/index_en.html)
  - Hurdle 1
  - Hurdle 2
  - Hurdle 3

### Day 7 
Learned:
- How to import modules from other files
```python
import random 
from hangman_words import word_list //syntax for importing modules (word_list) from other files (hangman_words.py).
from hangman_art import stages, logo //multiple modules (stages and logo) from the same file (hangman_art.py).
```

### Day 8 - Function Parameters & Caesar Cipher
Learned: 
- We can add a name of a variable between the parentheses of a function to start giving it some inputs.
```python
def my_function(something):
  #Do this with (something)
```
- Parameter is the name of the data that we pass into a function.
- Argument is the actual piece of data that we pass into the function.
- functions with multiple inputs:
```python
def function_with_inputs(input1, input2):
  #Do something with input 1 and 2.
```
- Positional Arguments, the function looks at the position of the arguments and thats how they determine which is which.
```python
def greet_with_name(name, location);
  print(f"Hello {name}, how is the weather at {location}?")
greet_with_name("LA", "Miguel") #"Hello LA, how is the weather at Miguel?"
```
- Keyword Arguments, assigning the value to the keywords to be more clear, and it won't result in unexpected behavior if order is switched
```python
def greet_with_name(name, location);
  print(f"Hello {name}, how is the weather at {location}?")
greet_with_name(location="LA", name="Miguel") #"Hello LA, how is the weather at Miguel?"
```
Exercises:
- [Paint Area Calculator](https://repl.it/join/lrxgzrgd-rmdpalo)
- [Prime Number Checker](https://repl.it/join/pgxxittl-rmdpalo)

### Day 9 - Dictionaries, Nesting, and the Secret Auction
Learned:
- Dictionaries are useful because they allow us to group together and tag related pieces of information.
  - Think of Dictionaries in the form of a table. We have the keys (words) and the values (definition)
- To create a dictionary
  - We start by typing our key and vlue separated by a colon wrapped in curly braces, any subsequent pairs must be separated with a comma.
```python 
  my_dictionary = {
    "Name": "Miguel", 
    "Favorite Color": "Blue",
    "Hobby": "Coding",
  }
```
- To refer to a key value pair in python we type the name of the dictionary followed by square brackets that contain the key of the value we want
```python
  print(my_dictionary["Name"]) #prints Miguel
```
- Adding to a dictionary, somewhat similar to declaring a variable.
```python
  my_dictionary["Languages"] = "English and Filipino"
  #the key is contained in the square brackets and the value is on the right side of the =
  print(my_dictionary) #will return our dictionary with the updated key value pairs.
```
- Wiping a dictionary is the same as creating an empty dictionary
```python
  new_dictionary = {} #new, empty dictionary
  my_dictionary = {} #wiped our first dictionary
  print(my_dictionary) #will just print out empty curlies
```
- Editing an entry is the same syntax as adding a new key value pair, just use the key of the entry you want to edit.
```python
  my_dictionary["Hobby"] = "Anything but coding." #replaces the original value of this key. 
```
- Looping through a dictionary
```python
  for key in my_dictionary:
    print(key) #prints the key
    print(my_dictionary[key]) #prints the value
```




