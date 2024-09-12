
2024-09-12 15:21

Status:

Tags: [[NIAT]] [[Definitions]] [[Bootstrap]]

________________________________________________________________________



# Introduction to Bootstrap

## 1. Reusability of CSS Rulesets

- CSS rulesets allow for the reuse of styles across multiple elements.
- Example:
    
    css
    
    `.button {   width: 138px;   height: 36px;   border-width: 0px;   border-radius: 10px; }`
    
    html
    
    `<button class="button">Get Started</button> <button class="button">Visit Now</button>`
    

## 2. Multiple Class Names in HTML

- Multiple classes can be applied to an element by separating class names with spaces.
- Example:
    
    html
    
    `<button class="button button-green">Get Started</button>`
    
    css
    
    `.button {   width: 138px;   height: 36px;   border-radius: 10px; } .button-green {   background-color: #8cc63f; }`
    

# 3. **Bootstrap Overview**

- Bootstrap is a collection of **predefined HTML, CSS, and JavaScript components** like buttons, cards, and more.

## 3.1 How to Use Bootstrap

- To use Bootstrap, add the **BootstrapCDN** code to your HTML `<head>`:
    
    html
    
    `<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" /> <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script> <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script> <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>`
    

## 3.2 Predefined Styles in Bootstrap

- Bootstrap provides predefined button styles with the `.btn` class.
- Example:
    
    html
    
    `<button class="btn btn-primary">Get Started</button>`
    
- Bootstrap has different button styles like:
    - `.btn-primary`
    - `.btn-secondary`
    - `.btn-success`
    - `.btn-danger`

##### 3.2.2 **Outline Buttons**

- Use `btn-outline-*` for buttons without a background color.
    
    html
    
    `<button class="btn btn-outline-primary">Get Started</button>`
    

##### 3.2.3 **Text Colors**

- Use Bootstrap's predefined text color classes:
    
    html
    
    Copy code
    
    `<p class="text-primary">Tourism</p> <p class="text-success">Tourism</p>`
    

## 3.2.4 Text Transform

- To change the case of the text, Bootstrap provides:
    - `.text-uppercase` (Uppercase)
    - `.text-capitalize` (Capitalize)
    - `.text-lowercase` (Lowercase)

## 3.2.5 Background Colors

- Bootstrap provides background color classes:
    
    html
    
    `<div class="bg-primary"><p>Tourism</p></div> <div class="bg-danger"><p>Tourism</p></div>`
    

---

### 4. **Important Notes**

## 4.1 Warning: Bootstrap Class Names in CSS

- Avoid using predefined Bootstrap class names in custom CSS, as this may produce **unexpected results**.

## 4.2 Do's and Don'ts

- **Do**:
    
    css
    
    `.button {   border-radius: 5px;   background-color: blue;   color: white; }`
    
    html
    
    `<button class="button">Get Started</button>`
    
- **Don't**:
    
    css
    
    `.btn {   border-radius: 5px;   background-color: blue;   color: white; }`
    
    html
    
    `<button class="btn">Get Started</button>`





# References

