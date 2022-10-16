# Python Lists
# List
thislist = ["apple", "banana", "cherry"]
print(thislist [0])

# Changeable
thislist = ["apple", "banana", "cherry", "apple", "cherry"]
print(thislist[0])
print(thislist[3])
print(thislist)

# List Length
thislist = ["apple", "banana", "cherry"]
print(len(thislist))

# List Items - Data Types
list1 = ["apple", "banana", "cherry"]
list2 = [1, 5, 7, 9, 3]
list3 = [True, False, False]

# type()
mylist = ["apple", "banana", "cherry"]

print(type(mylist))

# Python - Access List Items
# Access Items
thislist = ["apple", "banana", "cherry"]
print(thislist[2])

# Negative Indexing
thislist = ["apple", "banana", "cherry"]
print(thislist[-2])

# Range of Indexes
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[2:7])

# Range of Negative Indexes
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "melon", "mango"]
print(thislist[-5:-2])

# Check if Item Exists
thislist = ["apple", "banana", "cherry"]
if "banana" in thislist:
  print("Yes, 'banana' is in the fruits list")
  
# Python - Change List Items
# Change Item Value
thislist = ["apple", "banana", "cherry"]
thislist[2] = "strawberry"

print(thislist)

# Change a Range of Item Values
thislist = ["apple", "banana", "cherry", "orange", "kiwi", "mango"]

thislist[2:4] = ["blackcurrant", "watermelon"]

print(thislist)

# Insert Items
thislist = ["apple", "banana", "cherry"]

thislist.insert(2, "strawberry")

print(thislist) 

# Python - Add List Items
# Append Items
thislist = ["apple", "banana", "cherry"]

thislist.append("strawberry")

print(thislist)

# Insert Items
thislist = ["apple", "banana", "cherry"]
thislist.insert(2, "strawberry")
print(thislist)

# Extend List
thislist = ["apple", "banana", "cherry"]
tropical = ["mango", "pineapple", "papaya"]

thislist.extend(tropical)

print(thislist)

# Add Any Iterable
thislist = ["apple", "banana", "cherry"]
thistuple = ("strawberry", "peach")

thislist.extend(thistuple)

print(thislist) 

