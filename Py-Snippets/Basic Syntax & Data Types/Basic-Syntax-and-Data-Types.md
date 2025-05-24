Let’s start with **Basic Syntax & Data Types** in Python. This is one of the most important foundations.

---

## 🧱 1. Python Syntax

### ✅ Print Statement

```python
print("Hello, World!")
```

* `print()` is used to display output.

### ✅ Comments

```python
# This is a single-line comment

"""
This is a 
multi-line comment
"""
```

---

## 🔠 2. Variables and Data Types

### ✅ Declaring Variables (no need to define type)

```python
name = "Audumbar"   # string
age = 25            # integer
height = 5.9        # float
is_active = True    # boolean
```

### ✅ Type Checking

```python
print(type(name))   # <class 'str'>
print(type(age))    # <class 'int'>
```

---

## 🔄 3. Type Conversion

### ✅ Convert Between Types

```python
age = 25
height = float(age)     # int to float
print(height)           # 25.0

num_str = "100"
num = int(num_str)      # str to int
print(num)              # 100
```

### ⚠️ Invalid Conversion

```python
text = "hello"
num = int(text)  # ❌ Error: invalid literal
```

---

## 🧪 Simple Exercise:

Try this in your Python editor:

```python
# Declare your name, age, and if you're a student
name = "Audumbar"
age = 25
is_student = True

# Print them
print("Name:", name)
print("Age:", age)
print("Is Student:", is_student)

# Print the types of each
print("Type of name:", type(name))
print("Type of age:", type(age))
print("Type of is_student:", type(is_student))
```

---

You’ve done a great job so far! Here’s a short quiz on **Python Basic Syntax & Data Types**. Try answering without running the code first to test your understanding.

---

### 🧠 **Quiz:**

**1. What will be the output of the following code?**

```python
x = 10
y = "10"
print(x + int(y))
```

A. `"1010"`
B. `20`
C. `TypeError`
D. `10int`

---

**2. Which of the following is a valid variable name in Python?**

A. `2name`
B. `name_2`
C. `my-name`
D. `class`

---

**3. What is the data type of the result of this expression?**

```python
result = 10 / 2
print(type(result))
```

A. `int`
B. `float`
C. `str`
D. `bool`

---

**4. What will this code print?**

```python
name = "Audumbar"
age = 24
print("Name: " + name + ", Age: " + str(age))
```

A. `Name: Audumbar, Age: 24`
B. `Name: Audumbar, Age: age`
C. `Error`
D. `Audumbar 24`

---

**5. Which of these is used to add a multi-line comment in Python?**

A. `// comment //`
B. `/* comment */`
C. `''' comment '''`
D. `# comment`

---


