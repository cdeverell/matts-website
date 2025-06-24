# Puāwai Tonu Website

This document provides instructions for building a simple HTML and JavaScript-based website for **Puāwai Tonu**, following a clean and readable design inspired by [QTC](https://www.qtc.org.nz/) and using a light green background for warmth and calmness.

---

## 🌱 Project Overview

- **Website Name**: `www.puawaitonu.co.nz`
- **Technology Stack**: HTML, CSS, JavaScript (no frameworks)
- **Design Goals**:
  - Minimalist and readable
  - Light green background
  - Easy to update content (via HTML file editing)

---

## 📁 Folder Structure

puawaitonu/
├── index.html
├── style.css
└── script.js




---

## 🎨 Design Notes

- Use a **light green background**: e.g., `#eaf7ea`
- Centered content with a maximum width for readability
- Use a clear sans-serif font like `"Helvetica Neue", sans-serif`
- Section headers should be clear and spaced

---

## ✏️ Instructions to Build

### 1. Create `index.html`

This is the main HTML file. It includes placeholders for all text content:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Puāwai Tonu</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Puāwai Tonu</h1>
  </header>

  <main>
    <section>
      <h2>Ko wai māua? Who are we?</h2>
      <article>
        <h3>Matt Deverell</h3>
        <p>He uri ahau nō Ingarangi...<br>Ko Matthew Christopher Bolton Deverell tōku ingoa</p>
        <p>For around 10 years I have worked as a youth worker... arā kia puāwai tonu!</p>
      </article>

      <article>
        <h3>Ash</h3>
        <p>Nō Ingarani me kōtirana ōku tīpuna...<br>Ko Ashleigh Renetta Bolton Deverell tōku ingoa</p>
        <p>For around 10 years I worked as a youth worker...over kai.</p>
      </article>
    </section>

    <section>
      <h2>What we offer</h2>
      <p>We offer online counselling (Matt), professional supervision (Ash), and couples counselling (both)...</p>
    </section>

    <section>
      <h2>What is Narrative Therapy?</h2>
      <p>I (Matt) am trained in Narrative Therapy...</p>
    </section>

    <section>
      <h2>Supervision</h2>
      <p>I (Ash) see supervision as an extension of youth work...</p>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email us at <a href="mailto:puaawaitonu@gmail.com">puaawaitonu@gmail.com</a></p>
    </section>

    <section>
      <h2>Meaning of our name</h2>
      <p>The name comes from a whakataukī and whakatauākī from Sir James Henare... Puāwai Tonu means to continue blossoming.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Puāwai Tonu</p>
  </footer>
</body>
</html>
