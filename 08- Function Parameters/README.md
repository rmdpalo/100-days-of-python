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
- [Paint Area Calculator](https://replit.com/@rmdpalo/day-8-1-exercise#README.md)
- [Prime Number Checker](https://replit.com/@rmdpalo/day-8-2-exercise#README.md)
