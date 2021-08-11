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