
2024-09-06 10:09

Status:

Tags: [[NIAT]] [[Definitions]] [[Python]]

________________________________________________________________________



# Python - Logical Operators


Logical operators perform operations on Boolean values, returning `True` or `False`.

#### **Operators:**

- **`and`**: True if both values are True.
- **`or`**: True if at least one value is True.
- **`not`**: Returns the opposite of the given Boolean value.

---

### **Logical AND Operator (`and`)**

- **Description**: Returns `True` only if _both_ Boolean values are `True`, otherwise returns `False`.

**Example:**
`print(True and True)  # Output: True print(True and False) # Output: False`

| A     | B     | A and B |
| ----- | ----- | ------- |
| True  | True  | True    |
| True  | False | False   |
| False | True  | False   |
| False | False | False   |

---

### **Logical OR Operator (`or`)**

- **Description**: Returns `True` if _any one_ of the Boolean values is `True`, otherwise returns `False`.

**Example:**
`print(True or False)  # Output: True print(False or False) # Output: False`

| A     | B     | A or B |
| ----- | ----- | ------ |
| True  | True  | True   |
| True  | False | True   |
| False | True  | True   |
| False | False | False  |

---

### **Logical NOT Operator (`not`)**

- **Description**: Returns the opposite of the given Boolean value.

**Example:**
`print(not True)  # Output: False print(not False) # Output: True`

| A     | not A |
| ----- | ----- |
| True  | False |
| False | True  |

---

### **Summary**

- **`and`**: True if _both_ conditions are true.
- **`or`**: True if _any one_ condition is true.
- **`not`**: Reverses the Boolean value.




# References

