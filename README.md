### Chating – Responsive Landing Page (HTML & SCSS)
Chating Landing Page is a modern, responsive marketing website built with semantic HTML5 and structured SCSS architecture. It replicates a real-world SaaS-style landing page, providing a clean hero section, structured feature blocks, call-to-action areas, and a well-organized footer layout.

The project demonstrates modern frontend development best practices, focusing on:

**Clean architecture:** logical separation of layout sections (navbar, hero, features, footer) with structured and maintainable SCSS organization.

**Responsive design:** mobile-first implementation with scalable breakpoints to ensure seamless user experience across mobile, tablet, and desktop devices.

**Maintainable styling workflow:** use of SCSS for nesting, modular structure, and reusable styling patterns.

**Performance efficiency:** lightweight markup and optimized CSS output for fast rendering and smooth layout performance.

**UI consistency & visual hierarchy:** structured spacing, clear typography hierarchy, and reusable component patterns inspired by modern SaaS interfaces.

This landing page showcases a professional frontend workflow commonly used in production-ready marketing websites, emphasizing clean code structure, scalability, and responsive design principles.

### 🛠️ Technologies Used


- **HTML5** – semantic and structured markup
- **SCSS (Sass)** – modular and maintainable styling architecture
- **CSS3** – compiled styling output
- **Responsive Design** – mobile-first layout implementation
- **VS Code Live Server** (optional) – local development workflow

### Demo / Screenshot

![Chating Landing Page](assets/images/preview.png)

### Project Structure

```
├── index.html                    # Main entry point of the landing page
├── assets/                       # Static resources
│   ├── images/                   # Project images and screenshots
│   └── icons/                    # UI icons
└── styles/
    ├── style.scss                # Source SCSS file (editable)
    ├── style.css                 # Compiled production CSS
    └── style.css.map             # Source map for debugging (SCSS → CSS mapping)
```

### Features

- Responsive layout
- Mobile-first approach
- SCSS architecture
- Clean and maintainable structure

### Backend Features

This project is a static frontend landing page and does not include a backend layer.

All functionality is focused on UI structure, responsive layout, and SCSS architecture.

### Technical Highlights

- **Mobile-First Architecture** – Base styles are designed for smaller screens and progressively enhanced for larger devices.
- **Structured SCSS Workflow** – Clean nesting and modular styling for improved maintainability.
- **Separation of Concerns** – Clear distinction between HTML structure and styling layers.
- **Optimized CSS Output** – Compiled SCSS ensures production-ready stylesheet performance.
- **Source Map Support** – `style.css.map` enables efficient debugging in browser DevTools.
- **Scalable Folder Structure** – Organized layout suitable for small-to-medium scale frontend projects.
- **Semantic HTML5 Markup** – Improved accessibility and structural clarity.

### Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/mirzahab85/chating-landing-page-scss.git
```

### 2️⃣ Navigate into the project folder
```bash
cd chating-landing-page-scss
```

### 3️⃣ Open in your code editor

You can open the project in VS Code and run it using Live Server
or simply open index.html in your browser.

### SCSS Compilation (Optional)

If you want to compile SCSS manually, install Sass first:

```bash
npm install -g sass
```

Run watch mode:
```bash
sass --watch styles/style.scss:styles/style.css
```

This will automatically compile SCSS into CSS on every change.
