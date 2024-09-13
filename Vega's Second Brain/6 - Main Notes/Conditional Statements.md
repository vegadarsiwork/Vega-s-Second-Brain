
2024-09-11 14:10

Status:

Tags: [[NIAT]] [[Definitions]] [[Python]]

________________________________________________________________________



# Conditional Statements in Python

## Block of Code

- A **block of code** is a sequence of instructions that are executed in order.
- Python executes code line by line, following the sequence provided by the programmer.

## Condition

- A **condition** is an expression that results in either `True` or `False`.
- Conditions are the basis of decision-making in code.

**Examples:**

```python
2 < 3  # True 
a == b  # False (if a and b are not equal) 
True    # This is already a boolean value
````
`

## Conditional Statement

- A **Conditional Statement** allows you to execute a block of code only when a specific condition is `True`.

## Conditional Block

- A **Conditional Block** is a block of code that only executes if a condition is `True`.

## Indentation

- **Indentation** refers to the space(s) in front of the conditional block.
- Indentation is crucial in Python to define blocks of code.
- The standard practice is to use **four spaces** for indentation.

## Possible Mistakes with Indentation

- Each statement inside a conditional block must have the **same indentation**.
- Mixing tabs and spaces or inconsistent spacing will lead to errors.

### Incorrect Example:

```python
if 2 < 3:     
	print("Two is less than three")       
		print("This line has incorrect indentation")  # Wrong
```

### Correct Example:

```python
if 2 < 3:   
	print("Two is less than three") 
	print("This line has correct indentation")  # Correct
```

---

## `if-else` Syntax

- An **if-else** conditional statement allows you to execute one block of code if the condition is `True` and another block if the condition is `False`.

### Syntax:

```python
if condition:    
	# Block of code if condition is True
else:    
	# Block of code if condition is False
```

### Example:

```python
age = 18  
if age >= 18:     
	print("You are an adult.") 
else:     
	print("You are not an adult.")
```

**Output:**

`You are an adult.`

---

## Possible Mistakes in `if-else`

1. **The `else` Statement Must Follow `if`:**
    
    - The `else` block must directly follow the `if` block without any code in between.
    
    **Incorrect Example:**
    
	```python
	if age >= 18:   
	      print("You are an adult.")  
	      
	      # This comment or any code here would cause an error 
	      
	    else:    
			print("You are not an adult.")
	```
    
2. **`else` Cannot Exist Without `if`:**
    
    - You cannot use `else` on its own without an accompanying `if` block.
    
    **Incorrect Example:**
    
	```python
	else:     print("You are not an adult.") 
	     # Error: missing an `if` block
	```  

---

## Using `elif` (Else If)

- **`elif`** allows you to check multiple conditions. It’s used when there are more than two possible outcomes.

### Example:

```python
age = 16 
if age >= 18:    
	print("You are an adult.") 
elif age >= 13:    
	print("You are a teenager.") 
else:     
	print("You are a child.")
```

**Output:**

`You are a teenager.`

---

### Key Points to Remember:

- **Indentation** is essential in defining code blocks.
- Always use consistent spacing (preferably four spaces) to avoid syntax errors.
- The `else` block must directly follow the `if` block, without any intervening code.
- Use `elif` for multiple conditions instead of nesting multiple `if` blocks.







# References

