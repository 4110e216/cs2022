# Python Lists

# List
Lists are used to store multiple items in a single variable.

Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.

Lists are created using square brackets:

thislist = ["apple", "banana", "cherry"]
print(thislist [0])

# Changeable
The list is changeable, meaning that we can change, add, and remove items in a list after it has been created.

thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist[0])
print(thislist[3])
print(thislist)

# List Length
To determine how many items a list has, use the len() function:

thislist = ["apple", "banana", "cherry"]
print(len(thislist))

# List Items - Data Types
List items can be of any data type:

list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]

# type()
From Python's perspective, lists are defined as objects with the data type 'list':

mylist = ["apple", "banana", "cherry"]

print(type(mylist))

# Python - Access List Items

# Access Items
List items are indexed and you can access them by referring to the index number:

thislist = ["apple", "banana", "cherry"]
print(thislist[2])

# Negative Indexing
Negative indexing means start from the end

-1 refers to the last item, -2 refers to the second last item etc.

thislist = ["apple", "banana", "cherry"]
print(thislist[-2])

# Range of Indexes
You can specify a range of indexes by specifying where to start and where to end the range.

When specifying a range, the return value will be a new list with the specified items.

thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:7])

# Range of Negative Indexes
Specify negative indexes if you want to start the search from the end of the list:

thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[-5:-2])

# Check if Item Exists
To determine if a specified item is present in a list use the in keyword:

thislist = ["apple", "banana", "cherry"]
if "banana" in thislist:
  print("Yes, 'banana' is in the fruits list")
  
# Python - Change List Items

# Change Item Value
To change the value of a specific item, refer to the index number:

thislist = ["apple", "banana", "cherry"]
thislist[2] = "strawberry"

print(thislist)

# Change a Range of Item Values
To change the value of items within a specific range, define a list with the new values, and refer to the range of index numbers where you want to insert the new values:

thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]

thislist[2:4] = ["blackcurrant", "watermelon"]

print(thislist)

# Insert Items
To insert a new list item, without replacing any of the existing values, we can use the insert() method.


The insert() method inserts an item at the specified index:
thislist = ["apple", "banana", "cherry"]

thislist.insert(2, "strawberry")

print(thislist) 

# Python - Add List Items

# Append Items
To add an item to the end of the list, use the append() method:

thislist = ["apple", "banana", "cherry"]

thislist.append("strawberry")

print(thislist)

# Insert Items
To insert a list item at a specified index, use the insert() method.

The insert() method inserts an item at the specified index:

thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "strawberry")
print(thislist)

# Extend List
To append elements from another list to the current list, use the extend() method.

thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]

thislist.extend(tropical)

print(thislist)

# Add Any Iterable
The extend() method does not have to append lists, you can add any iterable object (tuples, sets, dictionaries etc.).

thislist = ["apple", "banana", "cherry"]
thistuple = ("strawberry", "peach")

thislist.extend(thistuple)

print(thislist) 

