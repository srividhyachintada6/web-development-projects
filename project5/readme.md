## 🎯 Project Goal

The goal of this project is to understand the fundamentals of HTML forms.

I practiced:

* Text inputs
* Email inputs
* Password inputs
* Number inputs
* Date inputs
* URL inputs
* Radio buttons
* Checkboxes
* Dropdown menus
* Textareas
* Submit buttons
* Reset buttons
* Form validation
* Grouping form elements

---

## Technologies Used

* HTML5
* VS Code
* Web Browser

---

## Project Structure

```text
developer-internship-form/
│
└── index.html
```

---

# HTML Concepts Learned

## 1. `<form>`

The `<form>` element is used to create a form for collecting user input.

```html
<form>

    ...

</form>
```

A form can contain many different input elements.

---

## 2. `<label>`

The `<label>` element describes an input field.

```html
<label for="email">Email:</label>

<input type="email" id="email">
```

The `for` attribute connects the label to the input's `id`.

---

## 3. `<input>`

The `<input>` element allows users to enter or select information.

Examples:

```html
<input type="text">

<input type="email">

<input type="password">

<input type="number">

<input type="date">

<input type="url">
```

---

# Input Types Practiced

| Input Type | Purpose                 |
| ---------- | ----------------------- |
| `text`     | Normal text             |
| `email`    | Email address           |
| `password` | Password                |
| `number`   | Numbers                 |
| `date`     | Date selection          |
| `url`      | Website URL             |
| `radio`    | Select one option       |
| `checkbox` | Select multiple options |

---

#  Radio Buttons

Radio buttons are useful when the user should select **one option from a group**.

```html
<input type="radio" name="worktype" value="remote">
<label>Remote</label>

<input type="radio" name="worktype" value="onsite">
<label>On-site</label>
```

### Important concept

Radio buttons in the same group should use the same `name`.

```text
name="worktype"
       ↓
Remote
On-site
Hybrid
```

This allows the browser to treat them as one group.

---

# Checkboxes

Checkboxes allow users to select multiple options.

```html
<input type="checkbox" name="skills" value="java">
<label>Java</label>

<input type="checkbox" name="skills" value="react">
<label>React</label>
```

Unlike radio buttons, multiple checkboxes can be selected.

---

# Dropdown — `<select>`

The `<select>` element creates a dropdown list.

```html
<select>

    <option>B.Tech</option>
    <option>BCA</option>
    <option>MCA</option>

</select>
```

`<option>` represents an individual choice.

---

# Textarea

`<textarea>` is used for longer text.

```html
<textarea
    rows="6"
    cols="40"
    placeholder="Write your answer here..."
></textarea>
```

Useful for:

* Messages
* Feedback
* Descriptions
* Application questions

---

#  Form Attributes

## `placeholder`

Provides a hint to the user.

```html
<input
    type="text"
    placeholder="Enter your full name"
>
```

---

## `required`

Makes a field mandatory.

```html
<input
    type="email"
    required
>
```

The browser performs basic validation before submission.

---

## `name`

The `name` attribute identifies form data.

```html
<input
    type="text"
    name="fullname"
>
```

It becomes especially important when form data is sent to a backend.

---

## `value`

The `value` attribute represents the value associated with an input.

```html
<input
    type="radio"
    name="worktype"
    value="remote"
>
```

---

#  Grouping Form Elements

## `<fieldset>`

Groups related form controls together.

```html
<fieldset>

    ...

</fieldset>
```

## `<legend>`

Provides a title for the group.

```html
<fieldset>

    <legend>Personal Information</legend>

    ...

</fieldset>
```

Together:

```text
┌─────────────────────────────────┐
│ Personal Information            │
│                                 │
│ Full Name: __________           │
│ Email: ______________           │
│ Password: ___________           │
└─────────────────────────────────┘
```

---

# Buttons

## Submit Button

```html
<button type="submit">
    Submit Application
</button>
```

Used to submit the form.

## Reset Button

```html
<button type="reset">
    Clear Form
</button>
```

Used to reset the form fields.

---

# 🔍 Radio Button vs Checkbox

| Feature         | Radio                        | Checkbox          |
| --------------- | ---------------------------- | ----------------- |
| Select one      | ✅                            | ✅                 |
| Select multiple | ❌                            | ✅                 |
| Common use      | Gender, work type            | Skills, interests |
| Same `name`     | Usually required for a group | Can share a name  |

---

# 🎯 Practice Challenges

After completing the project, try these yourself.

### Challenge 1

Add a **phone number** field.

### Challenge 2

Add a **preferred internship role** dropdown:

* Frontend Developer
* Backend Developer
* Full Stack Developer
* Java Developer

### Challenge 3

Add a **resume upload** field using the appropriate HTML input type.

### Challenge 4 ⭐

Add a **portfolio URL** field and make it required.

### Challenge 5 ⭐⭐

Create a separate **Contact Form** without looking at this project.

Try to remember the structure yourself.

---

## 👩‍💻 Learning Philosophy

**Learn → Practice → Build → Improve 🚀**
