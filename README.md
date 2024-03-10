# pyton int,float
a = 100
print("The type of variable having value", a, " is ", type(a))

b = 20.345
print("The type of variable having value", b, " is ", type(b))

c = 10 + 3j
print("The type of variable having value", c, " is ", type(c)) 

# print String
str = 'Hello World!'
print(str)

str = 'Hello World!'
print(str[0])  

str = 'Hello World!'
print(str[2:5])   

str = 'Hello World!'
print(str[2:]) 

str = 'Hello World!'
print(str * 2) 

str = 'Hello World!'
print(str + "TEST") 

# print list indexing#
my_list = [10, 'Hello', 3.14, [1, 2, 3]]
# Accessing list elements
print(my_list[0])       
print(my_list[1])       
print(my_list[3][1])    
# Slicing the list
print(my_list[1:3])     
# Concatenating lists
new_list = my_list + [5, 6]
print(new_list)         # Defining a tuple
my_tuple = (10, 'World', 2.718, (7, 8, 9))
# Accessing tuple elements
print(my_tuple[0])      # Output: 10
print(my_tuple[1])      # Output: World
print(my_tuple[3][2])   # Output: 9
# print range()
# Using range() to create a sequence of numbers
for num in range(5):     # Generates numbers from 0 to 4
    print(num, end=' ')   
print()  # Prints a new line
# Using range() with start and stop values
for num in range(2, 8):  # Generates numbers from 2 to 7
    print(num, end=' ')   
print()  # Prints a new line
# Using range() with start, stop, and step values
for num in range(1, 10, 2):  # Generates odd numbers from 1 to 9
    print(num, end=' ')      

# Dictionaries
# Creating a dictionary
person = {
    "first_name": "John",
    "last_name": "Doe",
    "age": 30,
    "city": "New York"
}

# Accessing values using keys
print("First Name:", person["first_name"])  
print("Age:", person["age"])                

# Modifying values
person["age"] = 31
print("Updated Age:", person["age"])       

# Adding new key-value pairs
person["occupation"] = "Engineer"

# # Deleting a key-value pair
del person["city"]

# Checking if a key exists
if "occupation" in person:
    print("Occupation:", person["occupation"])  

# Iterating through keys and values
for key, value in person.items():
    print(key + ":", value)

# Clearing the dictionary
person.clear()





