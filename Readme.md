# 🎨 HTML & CSS Practice

A beginner-friendly collection of **HTML and CSS practice projects** focused on learning web development through hands-on exercises.

This repository contains practice pages covering **text styling, buttons, layouts, spacing, pagination, product cards, hover effects, active states, and CSS interactions**.

---

## 🗺️ Repository Overview

```mermaid
flowchart TB
    R["🎨 HTML & CSS Practice"]

    R --> T["📝 Text Styling"]
    R --> B["🔘 Buttons"]
    R --> P["🛍️ Product UI"]
    R --> I["✨ Interactions"]
    R --> L["📐 Layout & Spacing"]
    R --> N["📄 Pagination"]

    T --> T1["text.html"]
    T --> T2["text2.html"]
    T --> T3["text3.html"]
    T --> T4["text4.html"]

    B --> B1["buttons.html"]
    P --> P1["website.html"]
    I --> I1["3DClick.html"]
    L --> L1["margin&padding.html"]
    L --> L2["strech.html"]
    N --> N1["pagination.html"]
```

---

# 📁 Repository Structure

The repository currently contains HTML pages and their corresponding CSS files.

```text
HTML-and-CSS/
│
├── 3DClick.html
├── 3Dclick.css
│
├── buttons.html
├── buttons.css
│
├── margin&padding.html
├── margin&padding.css
│
├── pagination.html
├── pagination.css
│
├── strech.html
├── strech.css
│
├── text.html
├── text.css
│
├── text2.html
├── text2.css
│
├── text3.html
├── text3.css
│
├── text4.html
├── text4.css
│
├── website.html
├── website.css
│
└── README.md
```

---

# 📝 Text Styling Practice

The repository contains four text-focused practice pages:

* `text.html`
* `text2.html`
* `text3.html`
* `text4.html`

These exercises are used to practice different aspects of **HTML text structure and CSS text styling**.

```mermaid
flowchart LR
    A["HTML Text"] --> B["Text Structure"]
    B --> C["CSS Styling"]
    C --> D["Typography"]
    D --> E["Layout"]
```

### Concepts Practiced

* Text elements
* Font styling
* Font size
* Text color
* Text alignment
* Spacing
* Paragraph styling
* CSS classes
* External CSS files

---

# 🔘 `buttons.html` — Button Gallery

`buttons.html` contains **10 recreated button styles** inspired by familiar interfaces such as YouTube, LinkedIn, GitHub, Amazon, Bootstrap, Uber and Twitter.

```mermaid
flowchart TB
    A["🔘 Button Gallery"]

    A --> B["Subscribe"]
    A --> C["Join"]
    A --> D["Tweet"]
    A --> E["Request now"]
    A --> F["Add to Cart"]
    A --> G["Sign up"]
    A --> H["Apply"]
    A --> I["Save"]
    A --> J["Get started"]
    A --> K["Download"]
```

## Button Styles

| Button      | Class               | Main Concept             |
| ----------- | ------------------- | ------------------------ |
| Subscribe   | `.subscribe-button` | Color & opacity          |
| Join        | `.join-button`      | Border & hover           |
| Tweet       | `.tweet-button`     | Border radius & shadow   |
| Request now | `.uber-button`      | Dark button styling      |
| Add to Cart | `.amazon-button`    | Background colors        |
| Sign up     | `.github-button`    | Green button & shadow    |
| Apply       | `.linkedin-button`  | Brand-style button       |
| Save        | `.link-button`      | Outline button           |
| Get started | `.bootstrap-button` | Purple button            |
| Download    | `.boot-button`      | Outline-to-filled effect |

The button styles demonstrate different **hover and active states**, including opacity changes, color changes, border changes and shadows.

---

# 🖱️ Button Interaction Model

```mermaid
flowchart LR
    A["Normal"] --> B["Hover"]
    B --> C["Active"]

    A --> D["Base Style"]
    B --> E["Color / Opacity / Shadow"]
    C --> F["Pressed State"]
```

### Interaction concepts

* `:hover`
* `:active`
* `opacity`
* `background-color`
* `color`
* `border`
* `border-radius`
* `box-shadow`
* `transition`

---

# 🛍️ `website.html` — Product Card

`website.html` contains an **Amazon-style product card** with a product link, title, price, delivery information and purchase buttons.

```mermaid
flowchart TD
    A["🛍️ Product Card"]
    A --> B["Amazon Link"]
    B --> C["Product Title"]
    C --> D["Price & Stock"]
    D --> E["Delivery Information"]
    E --> F["Add to Cart"]
    F --> G["Buy Now"]
```

### Product Card Components

* Amazon product link
* Product title
* Product price
* Stock information
* Delivery information
* Add to Cart button
* Buy Now button

The project also demonstrates interactive button color changes between **Add to Cart** and **Buy Now**.

---

# ✨ `3DClick.html` — 3D Click Effect

Practice page for creating a **3D-style button click interaction** using HTML and CSS.

```mermaid
flowchart LR
    A["Button"] --> B["Normal"]
    B --> C["Hover"]
    C --> D["Click / Press"]
    D --> E["3D Effect"]
    E --> F["Release"]
```

### Concepts

* Button styling
* Hover states
* Active states
* CSS positioning
* Shadows
* Click/press effects
* Transitions

---

# 📦 `margin&padding.html` — CSS Box Model

This page focuses on understanding the **CSS Box Model**, especially margin and padding.

```mermaid
flowchart TB
    A["CSS Box Model"]
    A --> B["Content"]
    B --> C["Padding"]
    C --> D["Border"]
    D --> E["Margin"]
```

```text
┌──────────────────────────┐
│          MARGIN          │
│  ┌────────────────────┐  │
│  │       BORDER       │  │
│  │  ┌──────────────┐  │  │
│  │  │   PADDING    │  │  │
│  │  │  ┌────────┐  │  │  │
│  │  │  │ CONTENT│  │  │  │
│  │  │  └────────┘  │  │  │
│  │  └──────────────┘  │  │
│  └────────────────────┘  │
└──────────────────────────┘
```

### Concepts

* Content
* Padding
* Border
* Margin
* Width
* Height
* Spacing

---

# 📄 `pagination.html` — Pagination

Practice page for creating and styling pagination controls.

```mermaid
flowchart LR
    A["Previous"] --> B["1"]
    B --> C["2"]
    C --> D["3"]
    D --> E["4"]
    E --> F["5"]
    F --> G["Next"]
```

### Concepts

* Navigation
* Links
* Spacing
* Borders
* Hover effects
* Active page styling
* Button-like navigation

---

# 📐 `strech.html` — Sizing & Stretch

Practice page focused on **CSS sizing and layout behavior**.

```mermaid
flowchart TD
    A["Container"] --> B["Available Space"]
    B --> C["Width"]
    C --> D["Height"]
    D --> E["Stretch / Layout"]
```

### Concepts

* Width
* Height
* Available space
* Element sizing
* Layout behavior
* CSS dimensions

---

# 🎨 CSS Concepts Practiced

```mermaid
mindmap
    root((HTML & CSS))
        HTML
            Elements
            Classes
            Links
            Structure
        CSS
            Colors
            Typography
            Width
            Height
            Margin
            Padding
            Borders
            Border Radius
        Interactions
            Hover
            Active
            Opacity
            Shadows
            Transitions
        Components
            Buttons
            Product Cards
            Pagination
            Text Sections
            3D Effects
```

---

# 🧠 Skills Practiced

### HTML

* HTML document structure
* Headings
* Paragraphs
* Links
* Buttons
* Classes
* Basic UI structure

### CSS

* Selectors
* Classes
* Colors
* Typography
* Font size
* Width & height
* Margin
* Padding
* Borders
* Border radius
* Background colors
* Opacity
* Box shadows
* Hover states
* Active states
* Transitions

### UI Development

* Button components
* Product cards
* Pagination
* Text layouts
* Interactive elements
* 3D button effects

---

# 🛠️ Technologies

```text
HTML5
CSS3
VS Code
Web Browser
Git
GitHub
```

---

# 🔄 Learning Progression

```mermaid
flowchart LR
    A["HTML Structure"]
    --> B["Text & Typography"]
    --> C["CSS Styling"]
    --> D["Box Model"]
    --> E["Buttons"]
    --> F["Hover & Active"]
    --> G["UI Components"]
    --> H["Interactive Effects"]
```

The repository follows a practical learning approach: understand a concept, recreate it with HTML/CSS, and experiment with styling and interactions.

---

# 🚀 Run Locally

## 1. Clone the Repository

```bash
git clone https://github.com/Betha-hemanth/HTML-and-CSS.git
```

## 2. Open the Project

```bash
cd HTML-and-CSS
```

## 3. Open an HTML File

Choose any practice page:

```text
3DClick.html
buttons.html
margin&padding.html
pagination.html
strech.html
text.html
text2.html
text3.html
text4.html
website.html
```

## 4. Run

Open the HTML file directly in a web browser.

You can also use **VS Code Live Server** for automatic browser refresh.

---

# 📂 Project Categories

```text
HTML-and-CSS/
│
├── 🔘 Buttons
│   ├── buttons.html
│   └── buttons.css
│
├── 📝 Text Styling
│   ├── text.html
│   ├── text.css
│   ├── text2.html
│   ├── text2.css
│   ├── text3.html
│   ├── text3.css
│   ├── text4.html
│   └── text4.css
│
├── 🛍️ Product UI
│   ├── website.html
│   └── website.css
│
├── 📦 Box Model
│   ├── margin&padding.html
│   └── margin&padding.css
│
├── 📄 Pagination
│   ├── pagination.html
│   └── pagination.css
│
├── 📐 Layout
│   ├── strech.html
│   └── strech.css
│
├── ✨ 3D Interaction
│   ├── 3DClick.html
│   └── 3Dclick.css
│
└── README.md
```

---

# 🎯 Learning Goal

```mermaid
flowchart LR
    A["Learn Concept"]
    --> B["Write HTML"]
    --> C["Style with CSS"]
    --> D["Add Interaction"]
    --> E["Build UI"]
    --> F["Practice"]
    --> G["Improve"]
```

The main goal of this repository is to **learn HTML and CSS through practical implementation** rather than theory alone.

By recreating familiar UI patterns, the project builds a foundation for creating more advanced web interfaces.

---

# 🔮 Future Improvements

The repository can be expanded with:

* Flexbox
* CSS Grid
* Responsive design
* Media queries
* Navigation bars
* Forms
* Login pages
* Registration pages
* Landing pages
* Responsive cards
* CSS animations
* CSS transitions
* JavaScript interactions
* Responsive navigation
* Mobile-first layouts
* More reusable UI components

---

# 👨‍💻 Author

**Betha Hemanth**

B.Tech — Computer Science Engineering

HTML & CSS Practice Repository

---

## ⭐ Support

If this repository helps you learn **HTML and CSS**, consider giving it a ⭐ on GitHub!


