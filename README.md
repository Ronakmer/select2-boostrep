```markdown
# Select2-like Dropdown with Search

A lightweight, Bootstrap-styled custom dropdown component inspired by [Select2](https://select2.org/), featuring live search, keyboard navigation, and a user-friendly UI—all in pure HTML, CSS, and JavaScript (no jQuery dependency).

## 🚀 Demo

👉 [Live Demo](https://ronakmer.github.io/select2-boostrep/)

The dropdown allows you to:

* Search for options dynamically
* Navigate using keyboard arrows
* Select via mouse or Enter key
* View selected value below the dropdown

## 📁 File Structure

```

├── index.html  ← Main HTML file with integrated styles and script

````

## 🧩 Features

* ✅ Pure HTML, CSS, and JavaScript (no jQuery or Select2 library)
* ✅ Bootstrap 5 compatible
* 🔍 Live search with instant filtering
* 🎯 Keyboard navigation (Up/Down/Enter/Esc)
* 🖱 Mouse interaction supported
* 💡 Accessible focus states and ARIA-like behavior
* 🧼 Auto-close on outside click

## 🔧 How to Use

### 1. Include Bootstrap

In the `<head>`:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
````

At the bottom of the `<body>`:

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
```

### 2. HTML Structure

Use the pre-defined structure in `index.html`. Key components include:

* A hidden input to store the selected value
* Custom styled `.select2-selection` div to simulate the dropdown
* A `.select2-search__field` input for live search
* Filterable `.select2-results__option` elements

### 3. JavaScript Behavior

Included script handles:

* Opening/closing dropdown
* Searching and filtering
* Highlighting and navigating options
* Selecting values and displaying results

You can add new options dynamically by appending them to `.select2-results__options` and calling the `updateFilteredOptions()` function.

## ✨ Customization

You can easily:

* Update the list of options
* Change styling via the `.select2-*` class selectors
* Integrate into forms by using the hidden input's value

## 📄 License

MIT License. Free to use and modify.

---

Let me know if you’d like a downloadable `.zip` version, deployment help, or instructions to make it work with backend frameworks like Django or Flask.

```
