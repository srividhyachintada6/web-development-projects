
# 🌍 Project 7 — Wanderly Travel Website

A travel destination website built using HTML and CSS.

The main focus is learning the CSS Box Model, Flexbox,
card layouts, spacing, and responsive design.

## Technologies Used

- HTML5
- CSS3

## Project Structure

```text
project7-wanderly/
├── index.html
├── style.css
└── README.md
````

## CSS Concepts Learned

### 1. CSS Box Model

Every element is made up of content, padding, border,
and margin.

```css
.destination-card {
    padding: 22px;
    border: 1px solid #e2e8f0;
    margin: 10px;
}
```

### 2. box-sizing

Includes padding and border within an element's
specified width and height.

```css
* {
    box-sizing: border-box;
}
```

### 3. Flexbox

Used to arrange destination cards in a flexible layout.

```css
.destination-container {
    display: flex;
    justify-content: center;
    align-items: stretch;
    gap: 25px;
    flex-wrap: wrap;
}
```

### 4. Flex Direction

Changes the direction of flex items.

```css
.navbar {
    display: flex;
    flex-direction: column;
}
```

### 5. Width and Max-Width

Controls the size of elements and prevents content
from becoming too wide.

```css
.destination-card {
    width: 320px;
}

.destinations {
    max-width: 1200px;
}
```

### 6. Card Styling

Combines background, border, rounded corners,
and shadow to create destination cards.

```css
.destination-card {
    background-color: white;
    border-radius: 14px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
}
```

### 7. Hover and Transform

Adds a movement effect when hovering over a card.

```css
.destination-card:hover {
    transform: translateY(-8px);
}
```

### 8. Media Queries

Adjusts the layout for smaller screens.

```css
@media (max-width: 600px) {
    .destination-card {
        width: 100%;
    }
}
```

## What I Practiced

* CSS Box Model
* Margin and padding
* Border and box shadow
* Flexbox alignment
* Gap and flex-wrap
* Width and max-width
* Card layouts
* Hover effects
* Media queries

## ➡️Practice Challenges

1. Add two more destinations.
2. Change the card width and spacing.
3. Change the layout using `flex-direction`.
4. Add a different hover effect.
5. Change the mobile breakpoint and test the layout.
