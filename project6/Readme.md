
# Project 6 — Brew & Bite Café

A simple café menu website built using **HTML and CSS**.

The main focus of this project is practicing CSS styling,
spacing, cards, buttons, hover effects, and a basic Flexbox layout.

---

## Technologies Used

- HTML5
- CSS3

---

## Project Structure


project6-cafe-menu/
│
├── index.html
└── style.css


---

# CSS Concepts Used

## 1. External CSS

CSS is connected to HTML using:

```html
<link rel="stylesheet" href="style.css">
```

This keeps the HTML structure and CSS styling separate.

---

## 2. CSS Selectors

Element selectors:

```css
body {
    margin: 0;
}
```

Class selectors:

```css
.menu-card {
    background-color: white;
}
```

ID selectors:

```css
#coffee {
    padding: 40px;
}
```

---

## 3. Colors

CSS is used to change text and background colors.

```css
header {
    background-color: #4b2e2e;
    color: white;
}
```

---

## 4. Fonts and Text

```css
header h1 {
    font-size: 36px;
}

.menu-card p {
    line-height: 1.5;
}
```

Used to control:

* Font size
* Text color
* Font weight
* Line height
* Text alignment

---

## 5. Margin and Padding

Margin creates space outside an element.

```css
header h1 {
    margin: 0;
}
```

Padding creates space inside an element.

```css
.menu-card {
    padding: 25px;
}
```

---

## 6. Border Radius

Used to create rounded corners.

```css
.menu-card {
    border-radius: 12px;
}
```

---

## 7. Box Shadow

Used to give cards a raised appearance.

```css
.menu-card {
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}
```

---

## 8. Display: Flex

Flexbox is used to arrange the menu cards horizontally.

```css
.menu-container {
    display: flex;
}
```

---

## 9. justify-content

Used to control the horizontal alignment of flex items.

```css
.menu-container {
    justify-content: center;
}
```

---

## 10. gap

Used to create space between menu cards.

```css
.menu-container {
    gap: 25px;
}
```

---

## 11. flex-wrap

Allows the cards to move to the next line when there is
not enough horizontal space.

```css
.menu-container {
    flex-wrap: wrap;
}
```

---

## 12. Hover Effect

The `:hover` pseudo-class changes the appearance
when the mouse moves over an element.

```css
button:hover {
    background-color: #704545;
}
```

The menu cards also use:

```css
.menu-card:hover {
    transform: translateY(-5px);
}
```

---

## 13. Button Styling

Buttons are styled using CSS properties.

```css
button {
    background-color: #4b2e2e;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 6px;
}
```

---

## 14. Card Design

The menu items are designed as cards using:

```css
.menu-card {
    background-color: white;
    width: 250px;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}
```

This combines multiple CSS concepts together.

---

# Main CSS Concepts


Selectors
   ↓
Colors
   ↓
Typography
   ↓
Margin & Padding
   ↓
Borders & Shadows
   ↓
Flexbox
   ↓
Hover Effects
   ↓
Card Layout

