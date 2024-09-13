
2024-09-13 15:32

Status:

Tags: [[NIAT]] [[Definitions]] [[Bootstrap]]

________________________________________________________________________



# Bootstrap - Flexbox Properties

## 1. Flexbox Container
- The Bootstrap class `d-flex` defines a **Flexbox Container**.
- Direct child elements of the Flexbox Container are called **flex items**.
- **Note:** Wrapping HTML elements in the Flexbox Container is required to apply other flex properties.

### Example:

```html
<div class="d-flex">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

- The `div` with `d-flex` is the Flexbox Container.
- The inner `div` is a **flex item** because it is directly inside the Flexbox Container.
- The `h1`, `p`, and `button` are not flex items since they are nested inside the flex item.

---

## 2. Flex Direction
The **Flex Direction** property specifies how flex items are arranged inside the Flexbox Container.

| Class Name    | Description                           |
|---------------|---------------------------------------|
| `flex-row`    | Items are arranged horizontally (default). |
| `flex-column` | Items are arranged vertically.        |

### 2.1 `flex-row` (Horizontal Direction)
This is the default direction, arranging flex items horizontally.

```html
<div class="d-flex flex-row">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

### 2.2 `flex-column` (Vertical Direction)
This class arranges flex items vertically.

```html
<div class="d-flex flex-column">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

---

## 3. Justify Content
The **Justify Content** property aligns flex items along the flex direction (either horizontally or vertically).

| Class Name                 | Description                                              |
|----------------------------|----------------------------------------------------------|
| `justify-content-start`     | Aligns flex items at the start (left/top).               |
| `justify-content-center`    | Centers the flex items.                                  |
| `justify-content-end`       | Aligns flex items at the end (right/bottom).             |
| `justify-content-between`   | Distributes space between flex items.                    |

### 3.1 `justify-content-start`
Aligns items to the start of the container, based on the flex direction.

```html
<div class="d-flex flex-column justify-content-start">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

- In **flex-row**, items align left.
- In **flex-column**, items align top.

### 3.2 `justify-content-center`
Centers the flex items.

```html
<div class="d-flex flex-column justify-content-center">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

### 3.3 `justify-content-end`
Aligns flex items to the end.

```html
<div class="d-flex flex-column justify-content-end">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

- In **flex-row**, items align right.
- In **flex-column**, items align bottom.

### 3.4 `justify-content-between`
Provides equal space between flex items.

```html
<div class="d-flex flex-column justify-content-between">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

---

## Complete Example

### HTML:

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  </head>
  <body>
    <div class="bg-container d-flex flex-column justify-content-end">
      <div class="tourism-card">
        <h1 class="main-heading">Tourism</h1>
        <p class="paragraph">Plan your trip.</p>
        <button class="button">Get Started</button>
      </div>
    </div>
  </body>
</html>
```

### CSS:

```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

.bg-container {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
  height: 100vh;
  background-size: cover;
}

.tourism-card {
  text-align: center;
  background-color: white;
  padding: 5px;
  border-top-left-radius: 25px;
  border-top-right-radius: 25px;
}

.main-heading, .paragraph {
  font-family: 'Roboto';
}

.button {
  color: white;
  background-color: #25b1cc;
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 20px;
}
```

---

## Try it out

Use the following code snippet to play around with **flex-direction** and **justify-content**:

```html
<div class="d-flex flex-column justify-content-between box-container">
  <div class="box box-orange"><p>Box 1</p></div>
  <div class="box box-green"><p>Box 2</p></div>
</div>
```

### CSS:

```css
.box {
  width: 100px;
  height: 100px;
  color: white;
}

.box-orange {
  background-color: orange;
}

.box-green {
  background-color: green;
}

.box-container {
  width: 100vw;
  height: 100vh;
}
```

Experiment with changing the `flex-direction` and `justify-content` classes to see how the layout changes.





# References

