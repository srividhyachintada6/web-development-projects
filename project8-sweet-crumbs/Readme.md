# Project 8 — Sweet Crumbs Bakery

A bakery website built using HTML and CSS.

**Main focus:** CSS Grid, Positioning, and Responsive Layouts.

## Technologies Used

- HTML5
- CSS3

## Project Structure

```text
project8-sweet-crumbs/
├── index.html
├── style.css
└── README.md
````

## CSS Concepts Learned

### 1. CSS Grid

Used to arrange product cards in columns.

```css
.product-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
}
```

### 2. Grid Responsive Layout

Changes the number of columns based on screen size.

```css
@media (max-width: 900px) {
    .product-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}
```

### 3. CSS Positioning

`relative` sets a positioning context, while `absolute`
positions an element relative to its positioned ancestor.

```css
.product-image {
    position: relative;
}

.product-tag {
    position: absolute;
    top: 12px;
    left: 12px;
}
```

### 4. Sticky Position

Keeps the navigation bar near the top while scrolling.

```css
.navbar {
    position: sticky;
    top: 0;
    z-index: 100;
}
```

### 5. Z-Index

Controls the stacking order of positioned elements.

```css
.navbar {
    z-index: 100;
}
```

### 6. Object-Fit

Controls how an image fills its container.

```css
.product-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### 7. CSS Variables

Stores reusable values for colors and other properties.

```css
:root {
    --primary: #a64d35;
}

button {
    background-color: var(--primary);
}
```

### 8. Transform and Transition

Adds smooth movement when hovering over product cards.

```css
.product-card {
    transition: transform 0.3s ease;
}

.product-card:hover {
    transform: translateY(-7px);
}
```

### 9. Media Queries

Adjusts the layout for mobile devices.

```css
@media (max-width: 600px) {
    .product-grid {
        grid-template-columns: 1fr;
    }
}
```

## What I Practiced

* CSS Grid and columns
* Responsive layouts
* Relative and absolute positioning
* Sticky navigation
* Z-index
* Object-fit
* CSS variables
* Transform and transition
* Media queries
