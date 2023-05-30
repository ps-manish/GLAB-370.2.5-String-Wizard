# GLAB-370.2.5-String-Wizard


## Welcome to the "String Wizard: Enchanting String Manipulation with Functions" Guided Lab! 🚀

In this 30-minute guided lab, we'll embark on an exciting coding adventure that combines the power of **functions**, **dictionaries**, and **string manipulation** in Python. Get ready to unleash your creativity and master the art of working with strings!

### Prerequisites

Before we begin, make sure you have the following:

- Basic knowledge of Python syntax.
- A Python interpreter or an integrated development environment (IDE) installed on your machine.

### Table of Contents

- [Step 1: Introduction](#step-1-introduction)
- [Step 2: Creating the Function](#step-2-creating-the-function)
- [Step 3: Manipulating Strings](#step-3-manipulating-strings)
- [Step 4: Applying the Function](#step-4-applying-the-function)
- [Step 5: Challenge](#step-5-challenge)
- [Step 6: Conclusion](#step-6-conclusion)

### Step 1: Introduction

Let's dive into the enchanting world of **string manipulation** and create a powerful function that can process dictionaries and lists while performing captivating operations on strings. Get ready to wield the magic of Python and weave spells with strings!

### Step 2: Creating the Function

To begin our journey, we'll create a function that takes a dictionary and a list as input parameters. The function will manipulate the strings within the dictionary based on the elements in the list.

```python
# Example:
def process_strings(dictionary, string_list):
    for key in dictionary:
        if key in string_list:
            dictionary[key] = dictionary[key].upper()
        else:
            dictionary[key] = dictionary[key].lower()

# This is just an example of a function. Feel free to modify it according to your specific needs.
```

### Step 3: Manipulating Strings

Now, let's explore the fascinating world of string manipulation within our function. We'll use the power of string methods to transform and manipulate the strings based on the provided list.

```python
# Example:
def process_strings(dictionary, string_list):
    for key in dictionary:
        if key in string_list:
            dictionary[key] = dictionary[key].upper()
        else:
            dictionary[key] = dictionary[key].lower()
```

### Step 4: Applying the Function

With our function defined, let's apply it to a dictionary and list to witness the magical transformation of strings!

```python
# Example:
my_dict = {
    "name": "Alice",
    "age": "25",
    "occupation": "Engineer"
}

my_list = ["name", "occupation"]

process_strings(my_dict, my_list)
print(my_dict)
```

### Step 5: Challenge

Now it's time for an exciting challenge! Modify the `process_strings` function to also replace spaces in the strings with underscores "_". Test the function with a dictionary and list of your choice, and observe the mesmerizing transformation of the strings.

### Step 6: Conclusion

Congratulations on completing the "String Wizard: Enchanting String Manipulation with Functions" guided lab! You've mastered the art of string manipulation and harnessed the power of functions to process dictionaries and lists in Python.

Remember to keep practicing and exploring new concepts. String manipulation is a versatile skill that opens endless possibilities for creative projects and practical applications!

Feel free to reach out if you have any questions. May your future coding adventures be filled with magical string transformations! 🎉
