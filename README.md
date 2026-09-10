# 🎨 HTML & CSS Practice

A beginner-friendly collection of HTML and CSS practice pages focused on building familiar UI components and learning practical CSS styling.

## 🗺️ Visual Repository Map

```mermaid
flowchart TB
    R["🎨 HTML & CSS Practice"] --> B["🔘 Buttons"]
    R --> P["🛍️ Product UI"]
    R --> I["✨ Interactions"]
    R --> L["📐 Layout & Spacing"]
    R --> N["📄 Navigation"]

    B --> B1["buttons.html"]
    P --> P1["website.html"]
    I --> I1["3DClick.html"]
    L --> L1["margin&padding.html"]
    L --> L2["strech.html"]
    N --> N1["pagination.html"]
```

## 📁 Repository Files

| File | Focus |
|---|---|
| `3DClick.html` | 3D button interaction |
| `buttons.html` | 10 styled UI buttons |
| `margin&padding.html` | CSS spacing and box model |
| `pagination.html` | Pagination UI |
| `strech.html` | CSS sizing/stretch behavior |
| `website.html` | Amazon-style product card |
| `README.md` | Documentation |

These are the files currently listed in the repository. citeturn0view0

---

# 🔘 `buttons.html` — Button Gallery

The repository contains 10 recreated button styles inspired by familiar UI designs: Subscribe, Join, Tweet, Request now, Add to Cart, Sign up, Apply, Save, Get started, and Download. citeturn0view0

```mermaid
flowchart TB
    A["🔘 Button Gallery"] --> B["Subscribe"]
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

### 🖱️ Interaction Model

```mermaid
flowchart LR
    A["Normal"] --> B["Hover"]
    B --> C["Active"]
    A --> D["Base color / size"]
    B --> E["Opacity / color / shadow"]
    C --> F["Pressed / darker state"]
```

The existing repository documents hover and active behavior including opacity changes, color changes, borders, and shadows. citeturn0view0

---

# 🛍️ `website.html` — Product Card

Creates an Amazon-style product card with a product link, title, price, delivery information, Add to Cart, and Buy now buttons. citeturn0view0

```mermaid
flowchart TD
    A["🛍️ Product Card"] --> B["Amazon Link"]
    B --> C["Product Title"]
    C --> D["Price + Stock"]
    D --> E["Delivery Note"]
    E --> F["Add to Cart"]
    F --> G["Buy now"]
```

The two action buttons use different colors and swap their yellow/orange hover behavior. citeturn0view0

---

# ✨ `3DClick.html` — 3D Click Effect

Practice page for creating a 3D-style click/press interaction. citeturn0view0

```mermaid
flowchart LR
    A["Button"] --> B["Normal"]
    B --> C["Hover"]
    C --> D["Press"]
    D --> E["3D Effect"]
    E --> F["Release"]
```

---

# 📦 `margin&padding.html` — CSS Box Model

Practice page for understanding CSS margin and padding. citeturn0view0

```mermaid
flowchart TB
    A["CSS Box Model"] --> B["Content"]
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
│  │  │  │CONTENT │  │  │  │
│  │  │  └────────┘  │  │  │
│  │  └──────────────┘  │  │
│  └────────────────────┘  │
└──────────────────────────┘
```

---

# 📄 `pagination.html` — Pagination

Practice page for building and styling pagination controls. citeturn0view0

```mermaid
flowchart LR
    A["Previous"] --> B["1"]
    B --> C["2"]
    C --> D["3"]
    D --> E["4"]
    E --> F["5"]
    F --> G["Next"]
```

---

# 📐 `strech.html` — Sizing & Stretch

Practice page focused on CSS sizing and stretch/layout behavior. citeturn0view0

```mermaid
flowchart TD
    A["Container"] --> B["Available Space"]
    B --> C["Width"]
    C --> D["Height"]
    D --> E["Stretch / Layout"]
```

---

# 🎨 CSS Concepts Practiced

```mermaid
mindmap
    root((HTML & CSS))
        Buttons
            Colors
            Border radius
            Hover
            Active
            Shadows
        Box Model
            Width
            Height
            Margin
            Padding
            Border
        Interaction
            Opacity
            Color changes
            Shadows
        Components
            Buttons
            Product cards
            Pagination
            3D effects
```

The repository documentation specifically covers reusable button classes, hover/active states, fixed dimensions, border radius, colors, opacity, background-color changes, and box shadows. citeturn0view0

---

# 🔄 Learning Progression

```mermaid
flowchart LR
    A["HTML Structure"] --> B["CSS Styling"]
    B --> C["Typography"]
    C --> D["Box Model"]
    D --> E["Buttons"]
    E --> F["Hover & Active"]
    F --> G["UI Components"]
    G --> H["Interactive Effects"]
```

---

# 🧠 Skills Practiced

- HTML structure
- CSS classes
- Typography
- Colors
- Width and height
- Margin and padding
- Borders
- Border radius
- Buttons
- Links
- Hover effects
- Active effects
- Opacity
- Box shadows
- Pagination
- Product-card design
- Basic UI interactions

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

# 🚀 Run Locally

### 1. Clone

```bash
git clone https://github.com/Betha-hemanth/HTML-and-CSS.git
```

### 2. Open

```bash
cd HTML-and-CSS
```

### 3. Choose a page

```text
3DClick.html
buttons.html
margin&padding.html
pagination.html
strech.html
website.html
```

### 4. Run

Open the HTML file in a browser, or use VS Code Live Server.

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
├── website.html
│
└── README.md
```

---

# 🎯 Learning Goal

```mermaid
flowchart LR
    A["Learn Concept"] --> B["Write HTML"]
    B --> C["Style with CSS"]
    C --> D["Add Interaction"]
    D --> E["Build UI"]
    E --> F["Practice & Improve"]
```

The goal is to learn HTML and CSS through hands-on recreation of UI components rather than theory alone. citeturn0view0

---

# 🔮 Future Improvements

- Flexbox
- CSS Grid
- Responsive design
- Media queries
- Navigation bars
- Forms
- Login pages
- Landing pages
- Responsive cards
- CSS animations
- More interactive components
- JavaScript interactions

---

# 👨‍💻 Author

**Betha Hemanth**

HTML & CSS Practice Repository

⭐ If this repository helps you learn HTML and CSS, consider giving it a star!
