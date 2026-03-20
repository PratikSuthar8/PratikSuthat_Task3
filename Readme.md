# 🎯 CSS Selectors Assignment

This project demonstrates the practical use of **CSS selectors**, including element, class, ID, and structural pseudo-class selectors.

The main focus of this assignment is to **apply styling without unnecessary use of classes or IDs**, especially for anchor (`<a>`) elements.

---

## 📌 Objective

- Understand and apply different types of CSS selectors
- Use **structural selectors** instead of extra classes/IDs
- Write clean and maintainable CSS
- Strengthen understanding of DOM-based styling

---

## 🧠 Concepts Covered

### 1. Element Selectors

Used to style all elements of a specific type.

```css id="c1"
body {
	background-color: orange;
}

p {
	color: white;
}
```

---

### 2. Class Selectors

```css id="c2"
.head {
	color: darkblue;
}
```

---

### 3. ID Selectors

```css id="c3"
#bglime {
	background-color: lime;
	font-size: 40px;
}
```

---

### 4. Descendant Selectors

```css id="c4"
#bglime span {
	color: red;
}

p span {
	color: black;
	font-size: 25px;
}
```

---

### 5. Structural Pseudo-Class Selectors (Important Part)

```css id="c5"
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

These selectors allow styling elements based on their **position in the DOM**, without adding extra classes or IDs.

---

## 🚀 Key Implementation

- Anchor (`<a>`) tags are styled **without using class or id**
- Styling is achieved using:
    - `:first-child`
    - `:last-child`
    - `:nth-child()`

---

## 📂 Project Structure

```bash id="c6"
.
├── index.html
├── style.css
```

---

## 🌐 How to Run

1. Download or clone the repository
2. Open `index.html` in any browser

---

## 💡 Learning Outcome

This assignment helped in understanding:

- How CSS selectors work in real scenarios
- How to avoid overusing classes and IDs
- Writing efficient and clean CSS
- Using DOM structure for precise styling

---

## 📌 Conclusion

CSS provides powerful selectors that allow developers to style elements efficiently.
Using structural selectors reduces dependency on extra classes and leads to cleaner code.

---
