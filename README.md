# 🎨 HTML & CSS Practice

A beginner-friendly collection of HTML and CSS exercises for learning how to build and style common web UI components.

This repository focuses on **HTML structure, CSS styling, typography, spacing, buttons, hover/active states, pagination, sizing, 3D interactions, and simple product/course layouts**.

---

## 🗺️ Repository Overview

```mermaid
flowchart TB
    R["🎨 HTML & CSS Practice"]

    R --> T["📝 Text & Typography"]
    R --> B["🔘 Buttons"]
    R --> P["📄 Pages & UI Components"]
    R --> S["📐 CSS Layout & Spacing"]

    T --> T1["text.html"]
    T --> T2["text2.html"]
    T --> T3["text3.html"]
    T --> T4["text4.html"]

    B --> B1["buttons.html"]

    P --> P1["website.html"]
    P --> P2["pagination.html"]

    S --> S1["3DClick.html"]
    S --> S2["margin&padding.html"]
    S --> S3["strech.html"]
```

---

## 📁 Repository Files

| File | Focus |
|---|---|
| `3DClick.html` | 3D button interaction and click/press effect |
| `buttons.html` | Collection of styled UI buttons |
| `margin&padding.html` | CSS margin and padding practice |
| `pagination.html` | Pagination UI and styling |
| `strech.html` | CSS sizing and stretch/layout practice |
| `text.html` | Video-style text and promotional content |
| `text2.html` | Typography and Tahoma font styling |
| `text3.html` | Promotional/deals text layout |
| `text4.html` | HTML & CSS course card |
| `website.html` | Amazon-style product card |
| `README.md` | Repository documentation |

The repository currently contains these 11 files on the `main` branch. citeturn1view0

---

# 📝 1. Text & Typography Practice

The four text files provide a progression from basic text styling to more complete UI sections.

```mermaid
flowchart LR
    A["text.html<br/>Video + Banner"] -->
    B["text2.html<br/>Typography"] -->
    C["text3.html<br/>Promotional Layout"] -->
    D["text4.html<br/>Course Card"]
```

### `text.html`

Practices a video-style text section with a title, statistics, author, description, and promotional shopping content.

**Concepts:**
- Font family
- Font size
- Font weight
- Width
- Margins
- Line height
- Colors
- Padding
- Hover styling

### `text2.html`

Focuses on typography using a Tahoma font style.

**Concepts:**
- `font-family`
- `font-size`
- `font-weight`
- CSS classes

### `text3.html`

Creates a promotional/deals section with centered text and interactive text.

**Concepts:**
- Text alignment
- Bold text
- Italic text
- Font sizing
- Colors
- Margins
- Hover effects
- Underline effects

### `text4.html`

Creates a simple HTML & CSS course card containing a course title, beginner-to-pro text, description, and a Get Started button.

**Concepts:**
- Typography
- Spacing
- Width
- Colors
- Border radius
- Button styling

---

# 🔘 2. Button Gallery — `buttons.html`

The button page recreates 10 familiar UI button styles.

```mermaid
flowchart LR
    A["buttons.html"] --> B["Subscribe"]
    A --> C["Join"]
    A --> D["Tweet"]
    A --> E["Request now"]
    A --> F["Add to Cart"]
    A --> G["Sign up"]
    A --> H["Apply on company website"]
    A --> I["Save"]
    A --> J["Get started"]
    A --> K["Download"]
```

### Button Styles

| Button | Main Style |
|---|---|
| Subscribe | Red filled button |
| Join | Outline/filled blue button |
| Tweet | Blue pill button + shadow |
| Request now | Black filled button |
| Add to Cart | Yellow Amazon-style button |
| Sign up | Green GitHub-style button |
| Apply on company website | Blue LinkedIn-style button |
| Save | Outline button |
| Get started | Purple Bootstrap-style button |
| Download | Gray outline button |

The repository README documents the actual classes, dimensions, colors, hover behavior, and active behavior for these buttons. citeturn1view0

### 🎯 Interaction Patterns

```mermaid
flowchart TD
    A["Button"] --> B["Normal State"]
    B --> C["Hover State"]
    C --> D["Active State"]

    B --> E["Color / Size / Radius"]
    C --> F["Opacity / Color / Shadow"]
    D --> G["Pressed / Darker / Lower Opacity"]
```

---

# 🛍️ 3. Product Card — `website.html`

This exercise creates an Amazon-style product card.

```mermaid
flowchart TD
    A["🛍️ Product Card"] --> B["Amazon Link"]
    B --> C["Product Title"]
    C --> D["Price + Stock"]
    D --> E["Delivery Information"]
    E --> F["Add to Cart"]
    F --> G["Buy Now"]
```

### Concepts Practiced

- Links
- Font styling
- Product information layout
- Colors
- Button styling
- Border radius
- Hover effects
- Active effects
- Spacing

The current README describes the product as Nike Black Running Shoes and documents the Add to Cart / Buy now interactions. citeturn1view0

---

# 🧊 4. 3D Button Interaction — `3DClick.html`

This page focuses on creating a **3D-style click/press interaction**.

```mermaid
flowchart LR
    A["Normal Button"] --> B["Hover"]
    B --> C["Mouse Press"]
    C --> D["3D / Pressed Effect"]
```

### Concepts

- Button styling
- CSS positioning
- Visual depth
- Click/press interaction
- CSS transitions/effects

---

# 📦 5. Margin & Padding — `margin&padding.html`

This exercise focuses on the CSS box model and the difference between **margin** and **padding**.

```mermaid
flowchart TB
    A["CSS Box Model"] --> B["Content"]
    B --> C["Padding"]
    C --> D["Border"]
    D --> E["Margin"]
```

### Concepts

- `margin`
- `padding`
- Box model
- Element spacing
- Layout positioning

---

# 📄 6. Pagination — `pagination.html`

This page practices creating a pagination interface for navigating between pages.

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

- Links
- Inline/block layout
- Spacing
- Borders
- Hover states
- Active page styling
- Navigation UI

---

# 📐 7. Stretch & Sizing — `strech.html`

This exercise focuses on CSS sizing and stretch behavior.

```mermaid
flowchart TD
    A["Container"] --> B["Element Width"]
    B --> C["Available Space"]
    C --> D["Stretch / Size"]
```

### Concepts

- Width
- Height
- Element sizing
- Available space
- CSS layout behavior

---

# 🎨 CSS Concepts Practiced

```mermaid
mindmap
  root((HTML & CSS))
    HTML
      Headings
      Paragraphs
      Links
      Buttons
      Page structure
    Typography
      Font family
      Font size
      Font weight
      Text color
      Text alignment
    Box Model
      Margin
      Padding
      Border
      Width
      Height
      Border radius
    Interaction
      Hover
      Active
      Transitions
      Shadows
      Opacity
    UI Design
      Buttons
      Product cards
      Course cards
      Pagination
      Promotional sections
      3D effects
```

---

# 🔄 Learning Progression

```mermaid
flowchart LR
    A["HTML Basics"] --> B["Text Styling"]
    B --> C["Typography"]
    C --> D["Spacing"]
    D --> E["Buttons"]
    E --> F["Hover & Active States"]
    F --> G["Cards & Components"]
    G --> H["Pagination"]
    H --> I["3D / Advanced CSS Effects"]
```

---

# 🧠 Skills Developed

By completing this repository, you practice:

- Building HTML pages
- Writing CSS inside HTML files
- Creating reusable CSS classes
- Styling text and fonts
- Understanding the CSS box model
- Working with margin and padding
- Creating buttons
- Styling links
- Using hover and active states
- Creating shadows and visual effects
- Building product cards
- Building course cards
- Creating pagination
- Understanding basic layout and sizing
- Recreating familiar UI components

---

# 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **Visual Studio Code**
- **Web Browser**
- **Git**
- **GitHub**

No JavaScript framework or external UI framework is required for these exercises.

---

# 🚀 How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/Betha-hemanth/HTML-and-CSS.git
```

## 2. Open the Project

```bash
cd HTML-and-CSS
```

## 3. Open Any HTML File

For example:

```text
buttons.html
website.html
text.html
text2.html
text3.html
text4.html
3DClick.html
margin&padding.html
pagination.html
strech.html
```

## 4. Run in Browser

Open the selected HTML file directly in a browser.

For a better development workflow, you can use **VS Code Live Server**.

---

# 📂 Project Structure

```text
HTML-and-CSS/
│
├── 3DClick.html
├── buttons.html
├── margin&padding.html
├── pagination.html
├── strech.html
├── text.html
├── text2.html
├── text3.html
├── text4.html
├── website.html
│
└── README.md
```

---

# 🎯 Learning Goals

The main goal of this repository is to strengthen the fundamentals required before moving into more advanced frontend development.

```mermaid
flowchart LR
    A["HTML"] --> B["CSS"]
    B --> C["UI Components"]
    C --> D["Interactions"]
    D --> E["Responsive Web Development"]
    E --> F["JavaScript"]
```

---

# 🔮 Future Improvements

Possible future additions to this repository:

- Responsive layouts
- Flexbox exercises
- CSS Grid exercises
- Media queries
- More button animations
- Navigation bars
- Forms
- Login pages
- Landing pages
- Responsive cards
- JavaScript interactions

---

# 👨‍💻 Author

**Betha Hemanth**

HTML & CSS Practice Repository

---

⭐ If you find this repository useful for learning HTML and CSS, consider giving it a star!

---

## 📌 Repository

GitHub repository:  
https://github.com/Betha-hemanth/HTML-and-CSS

