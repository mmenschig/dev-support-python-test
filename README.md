# dev-support-python-test
A repository for testing

# Table of Contents
1. Naming Conventions
2. Docstrings

1. Naming Conventions
* 1.1 Function and variable names should be lowercase, with words separated by underscores to improve readability. 
```python

# bad
addTogether(num1, num2):
  return num1 + num2
  
# good
add_together(num1, num2):
  return num1 + num2
```

* 1.2 Class names should normally use the CapWords convention.
```python

# bad
class user_handler:
  # do something
  
# good 
class UserHandler:
  # do something
```

* 1.3 Always use `self` as the first argument for instance methods and `cls` for class methods.
* 1.4 ... more
