# 📄 list.html – Lists and Grouping Content in HTML

This file demonstrates how to use list-related HTML tags and grouping elements like `<div>`, along with basic button usage.

---

## 📓 Purpose of the File

To illustrate the implementation of:
- Unordered and ordered lists
- Nested lists
- Use of the `<div>` element to group content
- Buttons for interaction

---

## 🏷️ Tags Used

| Tag        | Description                                                                 |
|------------|-----------------------------------------------------------------------------|
| `<ul>`     | Defines an unordered list (bulleted)                                        |
| `<ol>`     | Defines an ordered list (numbered)                                          |
| `<li>`     | List item, used inside both `<ul>` and `<ol>`                              |
| `<div>`    | Container for grouping related content                                      |
| `<button>` | Creates a clickable button                                                  |

---

## 🔢 List Examples

### Unordered List:
```html
<ul>
    <li>Saree</li>
    <li>3 piece</li>
    <li>Leggings</li>
    <li>T shirt</li>
    <li>Kurti</li>
    <li>Gown</li>
    <li>Borka</li>
</ul>
```
Used when the order of items is not important.

### Ordered List:
```html
<ol>
    <li>Liton Das</li>
    <li>Shakib al Hasan</li>
    <li>Tamim</li>
    <li>Shanto</li>
    <li>Taskin</li>
    <li>Mashrafi</li>
</ol>
```
Used when the order of items matters (e.g., ranking or steps).

### Nested Lists:
```html
<ul>
    <li>Salt
        <ul>
            <li>Molla Salt</li>
            <li>ACI Pure</li>
            <li>Mushkan Salt</li>
            <li>Fresh Salt</li>
        </ul>
    </li>
</ul>
```
Nested lists are useful for representing sub-categories or hierarchies.

---

## 🛏️ Grouping with `<div>`
```html
<div>
    <h3>Grocery List</h3>
    <ul>
        <li>Onion</li>
        <li>Garlic</li>
        <li>Ginger</li>
        <li>Oil</li>
        <li>Salt</li>
    </ul>
</div>
```
The `<div>` element is a block-level container used to group related HTML elements for styling or layout.

---

## 🛋️ Button Example
```html
<button>Click Me</button>
```
Represents a basic button that can be used for interaction, form submission, or triggering JavaScript actions.

---

## 🔎 Summary
This file introduces the concept of lists in HTML and how to use them semantically. It also demonstrates how to use `<div>` to group content logically and introduces the `<button>` tag for simple user interactions.

---
