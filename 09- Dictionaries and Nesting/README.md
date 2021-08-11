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
- Nesting Lists and Dictionaries
```python
  capitals = {
    "France": "Paris",
    "Germany": "Berlin",
  }
  
  #if I wanted to nest a list in a dictionary
  travel_log = {
    "France": ["Paris", "Lille", "Dijon"],
    "Germany": ["Berlin", "Hamburg"],
  }
  
  #nesting a dictionary in a dictionary
  travel_log = {
    "France": {"cities_visited": ["Paris", "Lille", "Dijon"], "total_visits": 12},
    "Germany": {"cities_visited": ["Berlin", "Hamburg", "Stuttgart"], "total_visits": 5},
  }
  
  #nesting a dictionary in a list.
  travel_log = [
    {
      "country": "France", 
      "cities_visited": ["Paris", "Lille", "Dijon"], 
      "total_visits": 12,
    },
    {
      "country": "Germany",
      "cities_visited": ["Berlin", "Hamburg", "Stuttgart"],
      "total_visits": 5,
    },
  ]
```
### Exercises
- [Grading Program](https://replit.com/@rmdpalo/day-9-1-exercise#README.md)
- [Dictionary in List](https://replit.com/@rmdpalo/day-9-2-exercise#README.md)
