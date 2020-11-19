# 100-days-of-python

## Projects
- [Day 1 Project - Team Name Generator](https://repl.it/join/butaniba-rmdpalo)

### Day 1 - Working with Variables in Python to Manage Data
Learned: 
- print() function, prints whatever is contained into the console, could be any data type or if you enter a variable it will print the value. "Hello World!" 
  - like in C \n creates a newline.
  - concatenation adding strings together _print("Ha" + "ha")_ will print "Haha"
- input() function, prompts the user for input.
  - _print("Hello " + input("What is your name?"))
    - will ask "What is your name?"
    - once a user inputs an answer, it will print "Hello Miguel"
  - len() function, gives us the length of a given string.
    - len("Miguel") will return 6.
- Declaring a variable in python: just name it meaningfully followed by a = and the value.
  - name = "Miguel"
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
- type() function, returns the data type of whatever is inputted.
- str() function, turns the input into a string data type.
- float() function, turns the input into a floating point number.
- Mathematical Operations in Python.
  - division in python will always turn the numbers into a floating point number.
- Number Manipulation
  - round(), rounds input into the nearest whole number.
    - adding a second argument will determine the number of places you want to round it to.
    ```python 
      print(round(8 / 3, 2)) #will return 2.67
    ```
   - // this is the floor division operator, will return an integer for division.
    - floored means that it won't round but simply chop off whatever is not a whole number.
    
