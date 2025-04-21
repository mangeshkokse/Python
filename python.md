# PYTHON

# Q What is python ?
- Python is a high-level, interpreted programming language known for its simplicity and readability. It’s widely used for:
  - Web development (e.g., Django, Flask)
  - Data analysis and machine learning (e.g., Pandas, NumPy, TensorFlow)
  - Automation and scripting
  - Software development
  - Cybersecurity and networking.

# Q. What is a Module in Python?
- A module in Python is simply a file containing Python code (with a .py extension) that you can import and reuse in other Python files.
- Modules help you organize your code, avoid repetition, and keep things clean and manageable.

## Types of Modules:
1. **Built-in modules** – Already available (No need to install) (`e.g., os, sys, math`)
2. **Third-party modules** – External module need to Installed via pip (`e.g., requests, numpy`)
3. **User-defined modules** – Your own created `.py` files
    
# Q. What is pip in python ?
- `pip` stands for **"Pip Installs Packages"**. It’s the default package manager for Python, used to install and manage external libraries and dependencies.

## What can pip do?
- Install packages from `PyPI`
- Uninstall packages
- Upgrade packages
- List installed packages

```bash
pip install <packages-name>
```

# Q. What is print in Python?
- The `print()` function in Python displays output to the console.
- It’s one of the most basic and commonly used functions, especially for debugging or showing results.
```python
print("Hello, World!")
Hello, World!
```
- You can print:
  - Strings → `print("Hi")`
  - Numbers → `print(123)`
  - Variables →
    ```python
    name = "Alice"
    print(name)
    OR
    print("Name:", name)
    ```
    
# Q. What is a Parenthesis () in Python?
- Parentheses `()` in Python are used in several important ways:
  1.  Function Calls
  ```python
  print("Hello")  # 'print' is the function, "Hello" is the argument
  ```
  2. Function Definitions
  ```python
  def greet(name):
    print("Hello", name)
  ```
  3. Tuples
  ```python
  my_tuple = (1, 2, 3)
  ```
  4. Grouping in Expressions
  ```python
  result = (2 + 3) * 4  # Without (), it would be 2 + (3*4)
  ```

# Q. What are Comments in Python?
- Comments are lines in Python code that the Python interpreter ignores. They’re used to explain the code, make notes, or disable parts of the code for testing.
  1. **Single-line Comment:**
  - Use the `#` symbol.
  ```python
  # This is a comment
  print("Hello")  # This prints a message
  ```
  2. **Multi-line Comment (Convention):**
  - There’s no special multi-line comment syntax in Python, but you can use triple quotes `(''' or """)` as a workaround.
  ```python
  """
  This is a
  multi-line comment
  """
  print("Hi")
  ```
# Q. What is an Escape Sequence Character in Python?
- An escape sequence in Python is a special character combination starting with a backslash `(\)` used to represent characters that are difficult or impossible to type directly.

**Common Escape Sequences:**
```markdown
### Common Escape Sequences in Python

| Escape | Meaning               | Example                      | Output            |
|--------|------------------------|------------------------------|--------------------|
| `\n`   | New line              | `print("Hello\nWorld")`      | Hello <br> World   |
| `\t`   | Tab (horizontal space)| `print("Name:\tAlice")`      | Name: Alice        |
| `\\`   | Backslash             | `print("C:\\Users\\")`       | C:\Users\          |
| `\'`   | Single quote          | `print('It\'s fine')`        | It's fine          |
| `\"`   | Double quote          | `print("He said, \"Hi\"")`   | He said, "Hi"      |
| `\r`   | Carriage return       | Moves to start of line       | -                  |
| `\b`   | Backspace             | Deletes the last character   | -                  |
```
```python
print("Line1\nLine2\tTabbed")
Line1
Line2	Tabbed
```

# Q. What is a Variable in Python?
- A variable in Python is a name that stores a value. Think of it as a container that holds data for later use.
```python 
name = "Alice"
age = 25
```
  1. `name` is a variable holding the string `"Alice"`
  2. `age` is a variable holding the number `25`
- You don’t need to declare the type (Python is dynamically typed).
- Variables can hold different types: numbers, strings, lists, etc.
- Variable names should be descriptive and cannot start with a number.
```python
city = "New York"
print("I live in", city)

I live in New York
```

# Q. What is a Data Type in Python?
- A data type in Python tells you what kind of value a variable holds — like a number, text, list, etc.
- Python is dynamically typed, so you don’t need to declare the type — Python figures it out automatically.
```markdown
### Common Data Types in Python

| Type       | Example           | Description                      |
|------------|-------------------|----------------------------------|
| `int`      | `x = 10`          | Integer (whole number)           |
| `float`    | `x = 3.14`        | Decimal number                   |
| `str`      | `x = "Hello"`     | String (text)                    |
| `bool`     | `x = True`        | Boolean (True or False)          |
| `list`     | `x = [1, 2, 3]`   | Ordered, changeable collection   |
| `tuple`    | `x = (1, 2, 3)`   | Ordered, unchangeable collection |
| `dict`     | `x = {"a": 1}`    | Key-value pairs                  |
| `set`      | `x = {1, 2, 3}`   | Unordered, unique values         |
| `NoneType` | `x = None`        | Represents no value              |
```
```python
x = 42
print(type(x))  # Output: <class 'int'>  # It will show class of data type.
```

# Q. What is an Operator in Python?
- An operator in Python is a symbol or keyword used to perform operations on variables and values — like math, comparison, logic, etc.
```markdown
### Types of Operators in Python

| Type            | Example                          | Description                              |
|-----------------|----------------------------------|------------------------------------------|
| **Arithmetic**  | `+`, `-`, `*`, `/`, `%`, `**`, `//` | Basic math operations                  |
| **Assignment**  | `=`, `+=`, `-=`, `*=`, `/=`      | Assign or update values                 |
| **Comparison**  | `==`, `!=`, `>`, `<`, `>=`, `<=` | Compare two values (True/False)         |
| **Logical**     | `and`, `or`, `not`               | Combine multiple conditions              |
| **Bitwise**     | `&`, `|`, `^`, `~`, `<<`, `>>`   | Work at the binary (bit) level          |
| **Membership**  | `in`, `not in`                   | Check if a value exists in a sequence   |
| **Identity**    | `is`, `is not`                   | Check if two variables point to same object |
```
```python
a = 10
b = 5

print(a + b)    # 15 (Arithmetic)
print(a > b)    # True (Comparison)
print(a != b)   # True (Comparison)
print(a > 0 and b > 0)  # True (Logical)
```
# Expirement 
```python
a = 12
b = 5

print("The value of", a, "+", b, "is:", a + b)
print("The value of", a, "-", b, "is:", a - b)
print("The value of", a, "*", b, "is:", a * b)
print("The value of", a, "/", b, "is:", a / b)

The value of 12 + 5 is: 17
The value of 12 - 5 is: 7
The value of 12 * 5 is: 60
The value of 12 / 5 is: 2.4
```

# Q. What is Typecasting in Python?
- Typecasting means converting one data type into another in Python, like turning a string into an integer or a float into a string.
```markdown
### Common Typecasting Functions in Python

| Function   | Converts to | Example         | Result          |
|------------|-------------|------------------|------------------|
| `int()`    | Integer      | `int("10")`       | `10`             |
| `float()`  | Float        | `float("5.6")`    | `5.6`            |
| `str()`    | String       | `str(25)`         | `"25"`           |
| `bool()`   | Boolean      | `bool(0)`         | `False`          |
| `list()`   | List         | `list("abc")`     | `['a', 'b', 'c']` |
```
**Example**
```python
# Typecasting example: converting string to integer

x = "50"           # x is a string
y = int(x)         # typecast to integer

print(x, type(x))  # Output: 50 <class 'str'>
print(y, type(y))  # Output: 50 <class 'int'>
print(y + 10)      # Output: 60
# Output
50 <class 'str'>
50 <class 'int'>
60
```
## Note: Practice "Taking user input" by trying multiple examples or experimenting with ChatGPT.

# Q.  What is input() in Python?
- In Python, `input()` is a built-in function used to take input from the user via the keyboard.
```python
# variable = input("Enter something: ")
name = input("Enter your name: ")
print("Hello,", name)

Enter your name: Mangesh
Hello, Mangesh
```
- The message inside quotes is shown as a prompt.
- The input is always returned as a string, so you may need to convert it using `int()`, `float()`, etc.
```python
a = input("Enter first number: ")
b = input("Enter second number: ")

print(a + b)     # wrong  syntax
print(int(a) + int(b))
```

# Q. what is string in python.
- A string is a sequence of characters enclosed in single `(')`, double `(")`, or triple quotes `(''' / """)`.
```python
s1 = 'Hello'
s2 = "World"
s3 = '''Multi-line
string'''
```
```markdown
## String Basics

| Property     | Description                              | Example                    |
|--------------|------------------------------------------|----------------------------|
| Type         | `str` (string type)                      | `type("Hi")` → `<class 'str'>` |
| Indexing     | Access characters using index `[]`       | `"Python"[0]` → `'P'`      |
| Slicing      | Extract substring                        | `"Python"[0:3]` → `'Pyt'`  |
| Length       | Count characters                         | `len("Hello")` → `5`       |
```
```python
a = "Hello"
b = "World"
print(a + " " + b)      # Concatenation → "Hello World"
print(a * 3)            # Repetition → "HelloHelloHello"
```
```markdown
## Useful String Methods

| Method            | Description                            | Example                                |
|-------------------|----------------------------------------|----------------------------------------|
| `lower()`         | Converts to lowercase                  | `"HELLO".lower()` → `'hello'`          |
| `upper()`         | Converts to uppercase                  | `"hi".upper()` → `'HI'`                |
| `strip()`         | Removes whitespace                     | `"  hi  ".strip()` → `'hi'`            |
| `replace()`       | Replaces part of the string            | `"hi".replace("h", "H")` → `'Hi'`      |
| `split()`         | Splits string into list                | `"a,b,c".split(",")` → `['a', 'b', 'c']` |
| `find()`          | Finds first index of a substring       | `"hello".find("l")` → `2`              |
| `startswith()`    | Checks if string starts with substring | `"hello".startswith("he")` → `True`    |
| `endswith()`      | Checks if string ends with substring   | `"hello".endswith("o")` → `True`       |
-------------------------------------------------------------------------------------------------------

## Escape Characters

| Escape | Meaning        |
|--------|----------------|
| `\n`   | New line       |
| `\t`   | Tab space      |
| `\\`   | Backslash      |
| `\'`   | Single quote   |
| `\"`   | Double quote   |
---------------------------
```





