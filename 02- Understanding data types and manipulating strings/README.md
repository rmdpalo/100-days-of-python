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
- [Sum of two numbers.](https://replit.com/@rmdpalo/day-2-1-exercise#README.md)
- [BMI Calculator](https://replit.com/@rmdpalo/day-2-2-exercise#README.md)
- [Your Life in Weeks](https://replit.com/@rmdpalo/day-2-3-exercise#README.md)
