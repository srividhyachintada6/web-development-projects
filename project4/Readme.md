# 📊 My Weekly Coding Dashboard

A simple HTML project for tracking my **coding practice, learning progress, and weekly goals**.

This is my **fourth HTML project** in my web development learning journey.

Instead of creating a basic student marks table, I created a small **developer-focused dashboard** to understand how tables can be used to organize real-world information.

---

## 🎯 Project Goal

The goal of this project is to learn how to create and structure tables in HTML.

I also practiced more advanced table features such as:

* Table captions
* Table headers
* Table body
* Table footer
* Merging columns
* Merging rows
* Combining tables with links

---

## 🛠️ Technologies Used

* HTML5
* VS Code
* Web Browser

---

# 📚 HTML Concepts Learned

## 1. Basic Table

The `<table>` element creates a table.

```html
<table border="1">

</table>
```

---

## 2. Table Row — `<tr>`

`<tr>` creates a row in a table.

```html
<tr>
    <td>Monday</td>
    <td>1 hour</td>
</tr>
```

---

## 3. Table Header — `<th>`

`<th>` represents a heading in a table.

```html
<th>Day</th>
<th>Java</th>
<th>DSA</th>
```

Table headings are normally displayed as bold text by the browser.

---

## 4. Table Data — `<td>`

`<td>` represents normal data inside a table.

```html
<td>Monday</td>
<td>1 hour</td>
```

---

# 🏗️ Table Structure

A basic table follows this structure:

```text
<table>
    │
    ├── <tr> → Row
    │      ├── <th> → Heading
    │      └── <td> → Data
    │
    └── </tr>
</table>
```

---

# 5. Table Caption — `<caption>`

`<caption>` gives a title or description to the table.

```html
<caption>
    My Coding Practice - This Week
</caption>
```

This makes the purpose of the table easier to understand.

---

# 6. Table Head — `<thead>`

`<thead>` contains the header section of a table.

```html
<thead>

    <tr>
        <th>Day</th>
        <th>Java</th>
        <th>DSA</th>
    </tr>

</thead>
```

---

# 7. Table Body — `<tbody>`

`<tbody>` contains the main data.

```html
<tbody>

    <tr>
        <td>Monday</td>
        <td>1 hour</td>
        <td>1 hour</td>
    </tr>

</tbody>
```

---

# 8. Table Footer — `<tfoot>`

`<tfoot>` is used for summary or total information.

```html
<tfoot>

    <tr>
        <th colspan="4">Total Practice Time</th>
        <th>19 Hours</th>
    </tr>

</tfoot>
```

---

# ⭐ Advanced Table Concepts

## 9. `colspan`

`colspan` allows a cell to span across multiple columns.

```html
<th colspan="4">
    Total Practice Time
</th>
```

Here, the cell occupies **4 columns**.

### Visual idea

```text
┌───────────────────────────────┐
│      Total Practice Time      │
└───────────────────────────────┘
       ← 4 columns →
```

---

## 10. `rowspan`

`rowspan` allows a cell to span across multiple rows.

```html
<td rowspan="2">
    Programming
</td>
```

The cell occupies **2 rows**.

### Visual idea

```text
┌──────────────┬──────────────┐
│ Programming  │ Java         │
│              ├──────────────┤
│              │ Collections  │
└──────────────┴──────────────┘
       ↑
    2 rows
```

---

# 🧠 What I Learned

After completing this project, I learned:

* How to create HTML tables
* How to create table rows
* How to create table headings
* How to add table data
* How to add a table caption
* How to divide a table into header, body, and footer
* How `colspan` works
* How `rowspan` works
* How to merge table cells
* How to organize structured information
* How tables can be used for real-world dashboards
* How to combine tables with hyperlinks

---

# 🔍 Important Difference

### `<th>`

Used for **headings**.

```html
<th>Java</th>
```

### `<td>`

Used for **data**.

```html
<td>1 hour</td>
```

### `<tr>`

Used to create a **row**.

```html
<tr>
    ...
</tr>
```

---

# 🌎 Real-World Uses of Tables

HTML tables can be useful for displaying:

* Coding progress
* Employee information
* Product comparisons
* Schedules
* Reports
* Pricing
* Results
* Statistics
* Leaderboards
* Data dashboards

---

# 📈 My HTML Learning Progress

```text
Project 1
My Developer Journey
        ↓
Headings + Paragraphs + HR
        ↓
Project 2
My Developer Profile
        ↓
Images + Links + Attributes
        ↓
Project 3
My Developer Learning Roadmap
        ↓
Lists + Nested Lists + Description Lists
        ↓
Project 4
My Weekly Coding Dashboard
        ↓
Tables + Rows + Columns
+ Caption
+ THEAD
+ TBODY
+ TFOOT
+ COLSPAN
+ ROWSPAN
```

---

# 🎯 Practice Challenge

After completing the project, try making these changes yourself:

### Challenge 1

Add **Saturday and Sunday** to the coding table.

### Challenge 2

Add a new column:

```text
Problems Solved
```

### Challenge 3

Create a new table called:

```text
My Project Progress
```

with:

* Project
* Technology
* Status
* GitHub Link

### Challenge 4 — ⭐

Create a table where one category uses `rowspan` and another heading uses `colspan`.

Try doing these **without copying the solution**.

---

# 🔮 Next Project

The next HTML concept I will learn is:

**HTML Forms**

I will learn how websites collect information from users using:

* Text input
* Email input
* Password input
* Radio buttons
* Checkboxes
* Dropdowns
* Textareas
* Submit buttons

---

## 👩‍💻 Learning Philosophy

**Learn → Practice → Build → Improve 🚀**
