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
