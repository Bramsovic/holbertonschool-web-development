**HTML Advanced Project**\\

---

## Description

In this first project of the **HTML Advanced** series, you will build the HTML structure of a web page from a Figma design file. No CSS or styling—just pure, semantic, and W3C-compliant HTML. You will focus on understanding and applying HTML fundamentals, semantic sectioning, and validation.

> **Manual QA review** must be requested when you’ve completed the project.

---

## Learning Objectives

By the end of this project, you should be able to explain, without Google:

* What is HTML and its role in web development.
* How to translate a wireframe into an HTML page.
* What a markup language is.
* The Document Object Model (DOM) and its structure.
* The difference between elements (tags) and attributes.
* The purpose of each HTML tag used in this project.

---

## Resources

Read or watch the following to prepare:

* **Learn to Code HTML & CSS** (up to and including “Creating Lists”)
* **Introduction to HTML** *(Holberton School resources)*
* **MDN Web Docs** on HTML foundational concepts

---

## Requirements

* All files must end with a single newline character.
* A **README.md** file at the root of the project folder is **mandatory**.
* No external libraries or frameworks: only plain HTML, CSS, and JavaScript are allowed. **No** NodeJS, React, Vue, Bootstrap, etc.
* Code must validate without errors or warnings using the **W3C HTML Validator**.

---

## Project Structure

```
holbertonschool-web-development/
└── html_advanced/
    ├── index.html       # Main HTML file
    └── README.md        # This file
```

---

## Tasks Overview

### 0. README and Objectives (mandatory)

* Write this **README.md** with clear objectives, resources, and instructions.

### 1. Header (mandatory, 5 pts)

* Create the basic HTML skeleton (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`).
* In `<body>`, add a `<header>` containing:

  * A link wrapping a logo image.
  * A container with three navigation links.

### 2. Banner (mandatory, 11 pts)

* Add a `<main>` with a `<section>` for the banner.
* Inside the section:

  * **Block 1**: `<h1>`, a paragraph, and a `<button>`.
  * **Block 2**: `<h2>` and a nested container with four feature blocks (each with an image, `<h3>`, and a paragraph).

### 3. Quote (mandatory, 7 pts)

* Below the banner, add a `<section>` for the quote.
* Include:

  * An image.
  * A `<blockquote>` for the quote text.
  * A caption or element for the author’s name.
  * A paragraph for additional context.

### 4. Videos (mandatory, 12 pts)

* Add a `<section>` for video content.
* Include:

  * `<h1>` for the section title.
  * A container with four video blocks (each: image, `<h2>`, paragraph).
  * An author info block: author image, `<h3>`, rating stars (images), and a score text.

### 5. Membership (mandatory, 5 pts)

* Create a `<section>` for membership plans.
* Include `<h1>` and a container with four plan blocks (each: image, `<h2>`, paragraph, `<button>`).

### 6. FAQ (mandatory, 5 pts)

* Add a `<section>` for FAQs.
* `<h1>` for the title.
* Two row containers, each containing two FAQ items (each: `<h2>` question and paragraph answer).

### 7. Footer (mandatory)

* After the main content, add a `<footer>`.
* Structure:

  * Container for centering.
  * Logo image.
  * A sub-container with three linked social icons.
  * A text note (e.g., copyright).

---

## Figma Design Access

Access the official designer file on Figma:

1. Open the [Project Page in Figma](https://www.figma.com/file/XXX) (you may need a free account).
2. Duplicate the file to your Drafts to inspect spacing, font sizes (rounded as needed), and all design details.

> **Font resources:** If fonts are missing, use `source-sans-pro` and `Spin-Cycle-OT`.

---

## Submission

1. Push your `index.html` and this `README.md` to the `html_advanced` directory of the `holbertonschool-web-development` repo on GitHub.
2. Ensure your HTML passes the W3C Validator with **no** errors or warnings.
3. Request a **Manual QA Review** in your project pipeline.

---

Good luck, and happy coding!
