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