# Demo_Portfolio

# 🔹 1. Folder Structure (Why it’s important)

```
portfolio/
│── index.html      → Main webpage
│── css/style.css   → Design & styling
│── js/script.js    → JavaScript logic
│── images/         → Images (profile, projects)
```

👉 **Why?**

* Keeps code **clean & professional**
* Easy to maintain (frontend industry standard)
* Required for real-world projects

---

# 🔹 2. index.html (Main File)

This file **builds the structure** of your portfolio.

---

## 🧠 `<head>` Section

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
```

✔ Makes website **mobile-responsive**

```html
<link href="bootstrap.css" rel="stylesheet">
```

✔ Adds **Bootstrap** (for fast design, grid system)

```html
<link rel="stylesheet" href="css/style.css">
```

✔ Connects your custom CSS

---

## 🔹 Navbar

```html
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
```

✔ **Bootstrap Navbar**

* `fixed-top` → navbar stays on top
* `navbar-expand-lg` → responsive menu
* Links scroll to sections using IDs (`#home`, `#about`)

👉 Used in **almost every professional website**

---

## 🔹 Hero Section (First Impression)

```html
<section id="home" class="hero">
```

✔ Shows:

* Your name
* Your role (Full Stack Developer)
* Call-to-action button

```html
<h1>Hi, I'm <span>Aman Wagh</span></h1>
```

✔ `span` is styled with color to highlight your name

---

## 🔹 About Section

```html
<section id="about">
```

✔ Explains:

* Who you are
* Your tech stack
* Your goal as a developer

👉 Very important for **HR & recruiters**

---

## 🔹 Skills Section

```html
<section id="skills">
```

Each skill is inside Bootstrap grid:

```html
<div class="col-md-3 skill">React.js</div>
```

✔ `col-md-3` → 4 skills per row
✔ `.skill` → custom CSS box

Skills included:

* HTML, CSS, Bootstrap
* JavaScript, React.js
* Node.js, Express.js
* MongoDB
* C, C++

👉 Shows you are a **full-stack + programming** developer

---

## 🔹 Projects Section

```html
<section id="projects">
```

Each project uses **Bootstrap Card**

```html
<div class="card project-card">
```

✔ Card contains:

* Project name
* Tech stack
* Short description

Projects shown:

* Book Store App
* Movie Project
* Clothing Shop

👉 Matches **your real projects** (very good for interviews)

---

## 🔹 Contact Section

```html
<section id="contact">
```

✔ Displays:

* Email
* Phone number (+91 format you prefer)
* Easy for recruiters to reach you

---

## 🔹 Footer

```html
<footer>
```

✔ Professional copyright
✔ Looks complete

---

# 🎨 3. style.css (Design Logic)

---

## 🔹 Hero Styling

```css
.hero {
  height: 90vh;
  background: linear-gradient();
}
```

✔ Full screen height
✔ Gradient background = **premium look**

---

## 🔹 Section Styling

```css
.section {
  padding: 60px 0;
}
```

✔ Proper spacing
✔ Clean layout

---

## 🔹 Skills Boxes

```css
.skill {
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
```

✔ Card-like effect
✔ Modern UI

---

## 🔹 Hover Effect on Projects

```css
.project-card:hover {
  transform: scale(1.05);
}
```

✔ Smooth animation
✔ Shows frontend skill

---

# ⚙️ 4. script.js (JavaScript)

```js
console.log("Portfolio Loaded Successfully");
```

✔ Confirms JS is working
✔ Placeholder for:

* Animations
* Scroll effects
* Theme toggle
* Form validation

---

