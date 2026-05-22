# 🌐 Full Stack Web Development Journey
> A structured learning repository documenting my progress from HTML basics to Full Stack development.

---

## ✅ Phase 1: HTML — COMPLETED

I have successfully completed the **HTML** phase of my web development journey!  
Below is a summary of all concepts covered:

| File | Concept Covered |
|------|----------------|
| `helloworld.html` | Basic HTML structure, DOCTYPE, head & body |
| `anchortag.html` | Anchor tags, hyperlinks, `href`, `target` |
| `list.html` | Ordered & unordered lists, nested lists |
| `form.html` | HTML Forms, input types, labels, buttons |
| `table_in_html.html` | Tables, `thead`, `tbody`, `tr`, `td`, `colspan` |
| `subscript_and_superscript.html` | `<sub>` and `<sup>` tags |
| `basicportfolio.html` | Building a basic portfolio page with HTML |
| `portfolio_using_semantictag.html` | Semantic HTML5 tags (`<header>`, `<section>`, `<footer>`, `<nav>`) |
| `practiceq1.html` | Practice exercise set 1 |
| `practiceq2.html` | Practice exercise set 2 |

---

## 📚 Topics Mastered in HTML

- ✅ Basic HTML structure & boilerplate
- ✅ Text formatting tags (`<h1>`–`<h6>`, `<p>`, `<strong>`, `<em>`)
- ✅ Anchor tags & hyperlinks
- ✅ Ordered & unordered lists
- ✅ HTML Forms & input elements
- ✅ Tables with `colspan` and `rowspan`
- ✅ Subscript & Superscript
- ✅ Semantic HTML5 elements
- ✅ Basic Portfolio page using pure HTML

---

## ✅ Phase 2: CSS — COMPLETED

I have successfully completed the **CSS** phase of my web development journey!  
Below is a summary of all concepts covered:

### 🎨 CSS Basics
- ✅ Basic format of CSS — Selector & Declaration
- ✅ How to include style — Inline, Internal, External
- ✅ Linking HTML with CSS file
- ✅ Color Property & Background-Color Property
- ✅ Color Systems — Named Color, RGB, Hexadecimal
- ✅ Alpha Channel & Opacity

### ✍️ Text Properties
- ✅ `text-align` (left, right, center, justify)
- ✅ `font-weight` (normal, bold, lighter, boo)
- ✅ `text-decoration` (underline, overline, line-through)
- ✅ `line-height` (px)
- ✅ `letter-spacing` (px)
- ✅ `font-size` (px, %, em, rem, ch, vh)
- ✅ `font-family` (Arial)
- ✅ `uppercase`

### 🎯 Selectors
- ✅ Element Selector
- ✅ ID Selector (`#id`)
- ✅ Class Selector (`.class`)
- ✅ Descendant Selector
- ✅ Adjacent Sibling Combinator
- ✅ Child Combinator
- ✅ Attribute Selector
- ✅ Selector Specificity (Priority)
- ✅ Inheritance in CSS

### 🔲 Pseudo Classes & Elements
- ✅ `:hover`, `:active`, `:checked`, `:nth-of-type`
- ✅ `::first-letter`, `::first-line`, `::selection`

### 📦 Box Model
- ✅ Height & Width
- ✅ Border (width, style, color)
- ✅ Padding (left, right, top, bottom)
- ✅ Margin (left, right, top, bottom)
- ✅ Border Sides
- ✅ Border Radius
- ✅ Box Shadow

### 📐 Display & Positioning
- ✅ Inline vs Block elements
- ✅ `display` — block, inline, none, flex, grid
- ✅ Units in CSS — px, cm, rem, %
- ✅ Position — static, relative, absolute, fixed
- ✅ Background Image
- ✅ Creating a Card hover effect
- ✅ Creating a Simple Smiley Face

### 🔀 CSS Transitions & Transforms
- ✅ CSS Transition (duration, delay)
- ✅ CSS Transform — Rotate, Scale, Translate, Skew

### 💪 Flexbox
- ✅ Flex Box & Flex Model
- ✅ Flex Box Direction — row, row-reverse, column, column-reverse
- ✅ Justify Content — flex-start, flex-end, center, space-between, space-around, space-evenly
- ✅ Align Items
- ✅ Align Content
- ✅ Align Self
- ✅ Flex Size

### 🔳 Grid
- ✅ Grid basics — `grid-template-columns`, `gap`, `justify-content`
- ✅ CSS Grid for card layouts

---

## 🗂️ CSS Projects Built

### 📰 Project 1 — Newspaper Style Article Page
**Files:** `newspaper-style-artical-page.html` + `newspaper-style-artical-page.css`  
**Date:** May 17, 2026

A multi-column newspaper-style article layout built from scratch using pure CSS.

**Key CSS Concepts Applied:**
| Concept | Usage |
|---------|-------|
| Flexbox | Header layout — logo centered, nav buttons on right |
| `position: absolute` | Centering logo & date using `left: 50%` + `translateX(-50%)` |
| `display: inline-block` | Multi-column article layout (3 columns per row) |
| `border-right` | Column dividers like a real newspaper |
| `float: left` on `img` | Image wraps with text beside it |
| `::first-letter` | Drop cap effect — large red first letter |
| `::first-line` | Bold italic styling on first line of paragraphs |
| `::selection` | Custom text highlight color |
| `p::first-line` | Editorial typographic detail |
| CSS Transitions | Nav button `translateY(-3px)` on hover |
| `button:hover` | Yellow highlight + box-shadow + lift effect |
| `font-family: Georgia, serif` | Classic newspaper typography |

**Highlights:**
- Newspaper header with centered masthead logo using absolute positioning trick
- 3-column article grid using `inline-block` + `border-right` dividers
- Drop cap (`::first-letter`) giving authentic editorial feel
- Custom `::selection` highlight in red
- Hover-lift effect on navigation buttons

---

### 🎓 Project 2 — Student Portal Dashboard
**Files:** `student_portal.html` + `student_portal.css`  
**Date:** May 19, 2026

A fully functional student portal dashboard UI with a top navbar and a 3×2 card grid layout.

**Key CSS Concepts Applied:**
| Concept | Usage |
|---------|-------|
| CSS Grid | `grid-template-columns: repeat(3, 240px)` — 3-column card layout |
| Flexbox | Navbar (`.one`) layout with space-between |
| `margin-left: auto` | Pushing buttons to right side of navbar |
| `flex-direction: column` | Cards stack content vertically |
| `object-fit: contain` | Images fit neatly inside card without distortion |
| `nth-of-type` | Targeting specific buttons inside `.one` |
| `transition` | Smooth card hover animation |
| `transform: translateY(-5px)` | Cards lift on hover |
| `box-shadow` | Green glow on card hover |
| `border-radius` | Rounded card corners |
| `filter: brightness(0) invert(1)` | Making logout icon white |

**Highlights:**
- Dark navy (`#2B3E50`) top strip acting as a professional navbar
- Responsive 3-column card grid centered on screen
- Cards with image, description text, `<hr>` divider, and dark footer label
- Smooth green glow + lift animation on card hover
- Red logout button with icon filter technique

---

### 😊 Project 3 — CSS Smiley Face
**Files:** `smily_face.html` + `smily_face.css`  
**Date:** May 17, 2026

A pure CSS drawing of a smiley face using `border-radius` and `position: absolute`.

**Key CSS Concepts Applied:**
| Concept | Usage |
|---------|-------|
| `border-radius: 50%` | Creating circular face and eyes |
| `position: relative/absolute` | Placing eyes and mouth inside the face |
| `border-radius: 0 0 100px 100px` | Semicircle mouth shape |
| Flexbox on `body` | Centering the face perfectly on screen |
| `height: 100vh` | Full viewport height centering |

**Highlights:**
- Yellowgreen circular face with precise eye and mouth positioning
- Mouth created using asymmetric `border-radius` — bottom-only curve
- Perfect viewport centering using `display: flex` on body

---

### 🚦 Project 4 — Traffic Light in CSS
**Files:** `traffic_light_in_css.html` + `traffic_light_in_css.css`  
**Date:** May 12, 2026

A CSS traffic light simulation.

**Key CSS Concepts Applied:** `border-radius`, `position`, `background-color`, box model

---

### 🎨 Project 5 — CSS Practice Exercises
**Files:** `css_practice_q1.html`, `css_practice_q2.html` + respective CSS files  
**Date:** May 10, 2026

Practice questions covering selectors, box model, and styling fundamentals.

---

### 🔗 Project 6 — Types of Selectors
**Files:** `types_of_selectors.html` + `types_of_selectors.css`  
**Date:** May 11, 2026

Hands-on practice with element, class, ID, descendant, child, sibling, and attribute selectors.

---

### 🧬 Project 7 — Inheritance in CSS
**Files:** `inheritance_in_css.html` + `inheritance_in_css.css`  
**Date:** May 11, 2026

Demonstrated how CSS properties cascade and inherit from parent to child elements.

---

### 🎭 Project 8 — Pseudo Class and Elements
**Files:** `pseudo_class_and_element.html` + `pseudo_class_and_element.css`  
**Date:** May 11, 2026

Practical usage of `:hover`, `:active`, `:nth-of-type`, `::first-letter`, `::first-line`, `::selection`.

---

## 🚀 Current Phase: JavaScript — In Progress

Now moving into **JavaScript** to add interactivity and logic to web pages.

### Upcoming in JavaScript:
- [ ] Variables, Data Types & Operators
- [ ] Conditionals & Loops
- [ ] Functions & Scope
- [ ] DOM Manipulation
- [ ] Events & Event Listeners
- [ ] Arrays & Objects
- [ ] ES6+ Features (Arrow functions, Spread, Destructuring)
- [ ] Fetch API & Async/Await
- [ ] JavaScript Projects

---

## 🗺️ Full Learning Roadmap

```
HTML  ✅  →  CSS  ✅  →  JavaScript  🔄  →  React  ⏳  →  Node.js  ⏳  →  Full Stack  🎯
```

---

## 💡 About Me

I am **Surya Prakash**, a B.Tech IT student at KIIT University with a passion for both  
**AI/ML** and **Full Stack Web Development**. This repository tracks my web dev learning journey from scratch.

- 🔗 GitHub: [github.com/SURYAPRAKASH9199](https://github.com/SURYAPRAKASH9199)
- 💼 LinkedIn: [linkedin.com/in/surya-prakash-08320734a](https://www.linkedin.com/in/surya-prakash-08320734a)

---

## 📌 Note

This repository is actively maintained and updated as I learn new concepts.  
Each commit reflects real progress — no shortcuts, just consistent daily learning.

---

⭐ *If you find this helpful or want to follow my journey, feel free to star the repo and give feedback!*
