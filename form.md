# 📄 form.html – HTML Form Elements Example

This file demonstrates various input elements used to build a basic HTML form. It includes text inputs, password fields, date pickers, checkboxes, buttons, and dropdown menus.

---

## 📝 Purpose of the File

To showcase different types of form controls in HTML and how they are used to collect user input in a structured and interactive way.

---

## 🏷️ Tags Used

| Tag               | Description                                                         |
| ---------------- | ------------------------------------------------------------------- |
| `<form>`         | Represents an HTML form used to collect user input                  |
| `<input>`        | Defines an input control (type can be text, password, email, etc.)  |
| `<button>`       | Creates a clickable button                                          |
| `<select>`       | Creates a drop-down list                                            |
| `<option>`       | Defines an option in a drop-down list                               |

---

## 📥 Example: Login Form

```html
<form>
    <input type="email" placeholder="Your email">
    <br><br>
    <input type="password" placeholder="password">
    <br><br>
    <input type="submit" value="Login">
</form>
```

- The `email` and `password` inputs allow users to type their credentials.
- The `submit` input sends the form data.

---

## 🧪 Example: Additional Input Types

```html
<input type="text">
<input type="checkbox">
<input type="password">
<input type="date">
<input type="file">
<input type="button" value="Submit">
<button>This is a Button</button>
```

- `text`: Basic input for general text.
- `checkbox`: Allows selection of options.
- `date`: Lets users pick a date.
- `file`: Upload a file from the system.
- `button` and `submit`: Used to trigger actions.

---

## 🔽 Example: Select Dropdown

```html
<select>
    <option value="tea">Tea</option>
    <option value="coffee">Coffee</option>
    <option value="nuts">Nuts</option>
</select>
```

- `<select>` groups options.
- `<option>` defines selectable items.

---

## 📌 Summary

This file is a practical demonstration of HTML form controls. Forms are crucial in web development for collecting user data, logging in users, uploading files, and more.

Each input type provides different functionality and enhances the interactivity of web pages.

---
