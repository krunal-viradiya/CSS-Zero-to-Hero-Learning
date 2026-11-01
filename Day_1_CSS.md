# Day 1: Introduction to CSS & The Basics 🎨

Welcome to **Day 1** of our **Zero to Hero CSS** series!

Today, we start right from the ground up: understanding what CSS is, how browsers apply styles, and how you can change the visual appearance of any web page.

---

## 1. What is CSS?

* **Full Form:** **C**ascading **S**tyle **S**heets
* **Purpose:** If HTML is the skeleton (structure) of a website, CSS is its skin, clothing, and styling.
* HTML defines **what** content appears on the page (text, buttons, images), while CSS controls **how** that content looks (colors, layouts, fonts, spacing, animations).

```text
+--------------------+      +--------------------+
|     HTML Only      | ---> |   HTML + CSS       |
| Plain, raw text    |      | Colors, alignment, |
| Black & white      |      | Beautiful layout   |
+--------------------+      +--------------------+
```

---

## 2. CSS Syntax

Every CSS rule consists of two main parts: a **Selector** and a **Declaration Block**.

```css
selector {
  property: value;
}
```

* **Selector:** Points to the HTML element you want to style (e.g., `h1`, `p`, `button`).
* **Property:** The style attribute you want to change (e.g., `color`, `font-size`, `background-color`).
* **Value:** The new setting you want to assign (e.g., `crimson`, `20px`, `royalblue`).

### Example:
```css
h1 {
  color: crimson;
  font-size: 32px;
}
```

---

## 3. Three Ways to Add CSS to HTML

There are three primary ways to link and apply CSS to an HTML document:

### A. Inline CSS (Directly inside an HTML element)
Applied using the `style` attribute inside a specific tag. Useful for quick tests or email templates, but discouraged for larger projects.

```html
<h1 style="color: blue; text-align: center;">Hello World</h1>
```

### B. Internal CSS (For a single page)
Defined inside a `<style>` tag within the `<head>` section of your HTML document.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Internal CSS Demo</title>
  <style>
    p {
      color: darkgreen;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <p>This paragraph is styled using internal CSS.</p>
</body>
</html>
```

### C. External CSS (Recommended & Industry Standard ⭐)
CSS is written in a separate `.css` file (e.g., `style.css`) and linked in the HTML `<head>` using the `<link>` tag. This keeps code clean, organized, and reusable across multiple pages.

**`index.html`:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>External CSS Demo</title>
  <!-- Link external stylesheet -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to CSS!</h1>
</body>
</html>
```

**`style.css`:**
```css
h1 {
  color: royalblue;
}
```

---

## 4. Fundamental CSS Properties to Learn First

| Property | What It Does | Example |
| :--- | :--- | :--- |
| `color` | Changes text color | `color: #333333;` |
| `background-color` | Sets background color of an element | `background-color: #f4f4f4;` |
| `font-size` | Controls the size of the text | `font-size: 18px;` |
| `font-family` | Changes typography/typeface | `font-family: Arial, sans-serif;` |
| `text-align` | Aligns text horizontally (`left`, `center`, `right`) | `text-align: center;` |

---

## 5. Day 1 Mini Project: Profile Card 🛠️

Create a folder on your computer named `css-day-1` and make two files inside it:
1. `index.html`
2. `style.css`

### Step 1: `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Day 1 - Profile Card</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="card">
    <h1>Hello, I'm Learning CSS!</h1>
    <p>Today marks Day 1 of my Zero to Hero CSS journey on GitHub.</p>
    <button>Connect With Me</button>
  </div>

</body>
</html>
```

### Step 2: `style.css`
```css
body {
  background-color: #f0f2f5;
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
}

h1 {
  color: #1a73e8;
  font-size: 28px;
}

p {
  color: #555555;
  font-size: 16px;
}

button {
  background-color: #1a73e8;
  color: #ffffff;
  padding: 10px 20px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}
```

---

## Day 1 Summary Checklist ✅
- [ ] Understand the role of CSS alongside HTML.
- [ ] Master the syntax: `selector`, `property`, and `value`.
- [ ] Practice the differences between Inline, Internal, and External CSS.
- [ ] Successfully link `style.css` to `index.html` using the `<link>` tag.