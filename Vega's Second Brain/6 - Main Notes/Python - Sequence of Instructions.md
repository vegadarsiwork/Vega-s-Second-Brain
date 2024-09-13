
2024-09-03 10:07

Status:

Tags: [[NIAT]] [[Definitions]] [[Python]]

________________________________________________________________________



# Python - Sequence of Instructions

### **Expressions**

An expression is a combination of values, variables, and operators that Python can evaluate.

**Examples:**

- **`a + b`**: Adds the values of `a` and `b`.
- **`a - 2`**: Subtracts 2 from `a`.
- **`5 * 4 / 2`**: Multiplies 5 by 4, then divides by 2.

---

### **String Concatenation and Repetition**

#### **Concatenation**

Concatenation joins two or more strings using the `+` operator.

**Example:**
`a = "1" + "2"`

**Output:**  
`12`  
_Note_: The result is `"12"`, not `3`, because it's a string operation.

#### **Repetition**

Repetition repeats a string using the `*` operator.

**Example:**
`b = "Hello" * 3`

**Output:**  
`HelloHelloHello`

### **TypeError: String and Integer Addition**

If you try to add a string and an integer, Python raises a `TypeError`.

**Example:**
`a = "Hello" + 5  # This causes an error`

To fix it, convert the integer to a string:
`a = "Hello" + str(5)`

**Output:**  
`Hello5`

### Length of String

`len()` returns the number of characters in a given string

```python
username = "Rahul"
length = len(username)
print (length)
```


### **Taking Input From the User**

`input()` allows you to take input from the user as a string.

**Example 1:**
`name = input("Enter your name: ") print("Hello, " + name)`

**Input:**  
`John`

**Output:**  
`Hello, John`

**Example 2:**
`age = input("Enter your age: ") print("You are " + age + " years old.")`

**Input:**  
`25`

**Output:**  
`You are 25 years old.`

_Note:_ `input()` always returns a string. Even if the user enters a number, it's treated as a string. This allows easy concatenation with other strings.

EOFError: EOF when reading a line
This happens when the input column is empty.

### **String Indexing**

You can access individual characters in a string using their index (positions start from 0).

**Example:**
`word = "Python" print(word[0])  # Outputs 'P'`

**IndexError:**  
Using an index larger than the string length will cause an error.
`print(word[10])  # Results in IndexError`


---
# References

