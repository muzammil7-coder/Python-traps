# Python Traps
A collection of tricky Python behaviors, common pitfalls, and gotchas that can confuse beginners and even intermediate programmers.

## Description
This repository demonstrates unusual or surprising behavior in Python, including how certain functions, operators, or data structures might behave unexpectedly.

Coming soon 🔥
all of you will see the good python traps. 
Stay tuned!!!!


## Contents
- Examples of tricky Python code
- Explanations of why they behave that way
- Tips to avoid common mistakes

## Example Trap
```python
# Mutable default argument trap
def append_to_list(value, my_list=[]):
    my_list.append(value)
    return my_list

print(append_to_list(1))  # Output: [1]
print(append_to_list(2))  # Output: [1, 2]  <- unexpected!
