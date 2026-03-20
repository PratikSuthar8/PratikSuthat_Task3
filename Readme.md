# 🎯 CSS Selectors Assignment

This project demonstrates the use of different **CSS selectors** to style HTML elements effectively.

The focus of this assignment is to:

- Use proper HTML structure (`header`, `section`)
- Apply CSS without unnecessary classes and IDs
- Style elements based on **DOM structure and position**

---

## 📌 Objective

- Understand and implement:
    - Element selectors
    - Class selectors
    - ID selectors
    - Descendant selectors
    - Structural pseudo-class selectors

- Style `<a>` tags **without using class or id**

---

## 🧾 HTML Structure

The document is divided into:

- **Header Section**
    - Contains headings (`h1`, `h2`, `h4`)
    - Uses class `.head`
    - `h2` includes an `id="bglime"` and a nested `<span>`

- **Content Section**
    - Paragraphs with and without ID
    - Nested `<span>` inside paragraph

- **List Section**
    - Unordered list (`ul`) with links
    - Ordered list (`ol`) with styled items

---

## 🎨 CSS Concepts Used

### 1. Element Selectors

```css
body {
	background-color: orange;
}

p {
	color: white;
}
```

---

### 2. Class Selector

```css
.head {
	color: darkblue;
}
```

---

### 3. ID Selector

```css
#bglime {
	background-color: lime;
	font-size: 40px;
}
```

---

### 4. Descendant Selectors

```css
#bglime span {
	color: red;
}

p span {
	color: black;
	font-size: 25px;
}
```

---

### 5. Structural Selectors (Important)

```css
ul li:first-child a {
	background-color: lime;
}

ul li:last-child a {
	background-color: darkblue;
	color: white;
}

ol li:nth-child(2) {
	color: blue;
}

ol li:nth-child(3) {
	color: red;
}
```

These selectors are used to style elements based on their **position in the DOM**, without adding extra classes or IDs.

---

## 🚀 Key Implementation

- `<a>` tags are styled **without class or id**
- Styling is achieved using:
    - `:first-child`
    - `:last-child`
    - `:nth-child()`

---

## 📂 Project Structure

```bash
.
├── index.html
├── style.css
```

---

## 🌐 How to Run

1. Open the project folder
2. Open `index.html` in any browser

---

## 💡 Learning Outcome

- Better understanding of CSS selector hierarchy
- Ability to style elements using **structure instead of extra attributes**
- Writing cleaner and more maintainable CSS
- Improved semantic HTML usage

---

## 📌 Conclusion

This assignment demonstrates that CSS selectors can be used efficiently to target elements based on structure, reducing dependency on additional classes and IDs.

---
