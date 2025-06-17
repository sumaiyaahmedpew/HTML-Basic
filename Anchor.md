# 📄 anchor.html – Understanding the `<a>` (Anchor) Tag in HTML

This file demonstrates the usage of the `<a>` (anchor) tag, which is used to create hyperlinks that connect one page to another—either within the same site or to external resources.

---

## 🔗 Purpose of the `<a>` Tag

The anchor (`<a>`) tag is fundamental in HTML for linking documents. It allows users to:

- Navigate to external websites.
- Jump to specific sections within a document.
- Download files.
- Open links in new tabs.
- Link to other HTML files within the project.

---

## 📚 Tags Used

| Tag | Description |
|-----|-------------|
| `<a>` | Defines a hyperlink. Requires the `href` attribute to specify the destination URL. |
| `href` | Stands for "Hypertext REFerence". Used to set the target URL of the link. |
| `target="_blank"` | Opens the linked document in a new browser tab or window. |
| `<br>` | Inserts a line break for better readability between links. |

---

## 🌐 External Links

Examples in this file include hyperlinks to:

- [Google](https://www.google.com/)
- [Ostad](https://ostad.app/)
- [W3Schools – HTML](https://www.w3schools.com/html/)
- [W3Schools – CSS](https://www.w3schools.com/html/html_css.asp)
- [HackerRank C Problems](https://www.hackerrank.com/domains/c)
- [DataCamp](https://www.datacamp.com/)

These links use the `href` attribute to direct users to educational platforms and problem-solving sites.

---

## 🧭 Internal Navigation

Some links are internal, such as:

```html
<a href="list.html">List</a>
<a href="list.html" target="_blank">View List in New Tab</a>


📄 Opening in a New Tab
<a href="..." target="_blank">Link Text</a>

✅ Best Practices
- Always use descriptive link text (avoid "Click here").
- Use target="_blank" cautiously and inform users when a new tab will open.
- Ensure internal links are correctly referenced relative to the current file’s location.
