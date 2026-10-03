# 📜 Jatin Hemraj Joshi — Retro Editorial Resume & CV Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0%20KB%20%7C%20Pure%20CSS-success?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-orange?style=for-the-badge)
![Semantic HTML](https://img.shields.io/badge/HTML-Semantic%20Structure-0F766E?style=for-the-badge)
![Design](https://img.shields.io/badge/Design-Retro%20Editorial-D84A28?style=for-the-badge)

> 📰 **A recruiter-focused, single-page technical resume website that combines vintage editorial print aesthetics with modern responsive web design.**

This project is a handcrafted **Resume & Curriculum Vitae website** created for **Jatin Hemraj Joshi**. The interface takes inspiration from vintage newspaper layouts, analog print materials, editorial typography, postage-stamp compositions, typewriter metadata, and modern portfolio presentation techniques.

The website is intentionally built with **pure Semantic HTML5 and modern CSS3**, without JavaScript-driven interactions or external CSS frameworks. Theme switching, the mobile navigation state, hover interactions, card movement, visual transitions, and other UI states are handled through CSS wherever possible.

---

## 🌐 Live Demonstration & Links

- 🔗 **Live Website:** [jj-portfolio-website.netlify.app](https://jj-portfolio-website.netlify.app/)
- 📦 **GitHub Repository:** [Repository](https://github.com/your-username/retro-editorial-resume)
- 👤 **Developer:** Jatin Hemraj Joshi
- 📍 **Location:** Pune, Maharashtra, India

> 💡 Replace the placeholder GitHub URL with the actual repository URL before publishing the project publicly.

---

## ✨ Project Overview

The goal of this project is to transform a traditional resume into an **interactive digital CV** while keeping the information highly scannable for recruiters, hiring managers, and other visitors.

Instead of following a conventional corporate resume layout, the website uses a distinctive **retro-editorial visual language**:

- 📰 Newspaper-inspired composition
- 📜 Warm parchment-inspired surfaces
- 🔴 Terracotta and crimson accent systems
- ✒️ Editorial serif typography
- ⌨️ Typewriter-style metadata
- 🖼️ Vintage portrait treatment
- 🃏 Layered and overlapping card layouts
- 🌗 Light and dark visual themes
- 📱 Mobile-first responsive behavior
- ♿ Semantic and accessibility-conscious HTML
- 🔍 SEO-friendly document structure

The result is a resume experience that feels more like a carefully designed editorial publication than a traditional online CV.

---

## 🎯 Project Goals

The primary objectives of the project are:

1. 🧑‍💻 Present professional information in a polished digital format.
2. 📰 Experiment with editorial and retro-print-inspired web design.
3. 🧱 Practice semantic HTML5 document architecture.
4. 🎨 Build a reusable CSS design-token system.
5. 🌗 Implement light and dark visual themes without JavaScript.
6. 📱 Create a responsive experience across mobile, tablet, and desktop devices.
7. ⚡ Keep the implementation lightweight and dependency-free.
8. ♿ Follow accessibility-conscious markup and interaction patterns.
9. 🔍 Structure the page so search engines can understand its content.
10. 💼 Create a practical resume website suitable for professional presentation.

---

## 🧩 Core Features

### 📰 1. Retro Editorial Visual System

The entire interface follows a cohesive vintage editorial direction inspired by printed newspapers, magazines, posters, and analog paper documents.

Key visual details include:

- Aged-paper background tones
- Editorial framing and borders
- Double-line visual treatments
- Large serif display typography
- Typewriter-inspired metadata
- Vintage labels and issue numbers
- Terracotta/crimson visual accents
- Newspaper-style information hierarchy

---

### 🌗 2. Dual Theme System

The website supports two distinct visual modes:

#### 📜 Warm Editorial — Light Mode

A warm paper-inspired theme designed to feel tactile, classic, and editorial.

- Background: `#EBE7DE`
- Surface: `#E2DDD5`
- Card: `#FAF6F0`
- Primary Text: `#141414`
- Muted Text: `#4A4039`
- Accent: `#D84A28`

#### 🌑 Crimson Noir — Dark Mode

A high-contrast dark theme that transforms the editorial aesthetic into a modern cinematic interface.

- Background: `#090A0F`
- Surface: `#14171F`
- Card: `#12151D`
- Primary Text: `#FFFFFF`
- Muted Text: `#8F96A3`
- Accent: `#DC2626`

Both themes use the same semantic design tokens, allowing the visual system to remain consistent while the atmosphere changes significantly.

---

## 🃏 Interactive CSS Card Deck

One of the project's signature visual effects is the overlapping card/deck interaction.

The cards intentionally overlap one another to reproduce the appearance of physical paper cards or printed tickets stacked together.

On hover, the active card can:

- ⬆️ Lift from the surface
- 🔄 Rotate slightly
- ➡️ Shift neighboring cards
- ✨ Reveal additional visual hierarchy
- 🖱️ Respond smoothly to pointer interaction

The interaction is implemented using CSS transitions and transforms rather than JavaScript animation logic.

---

## 📱 Responsive Navigation

The navigation system is designed with a **mobile-first approach**.

On smaller screens:

- The navigation links collapse into a mobile drawer.
- A three-line hamburger control is displayed.
- The icon transitions into an X/cross state.
- Navigation visibility is controlled using CSS state selectors.
- Layout spacing adapts to smaller viewport widths.

On larger screens, the navigation returns to a horizontal editorial header layout.

---

## 📜 Native Scrolling Experience

The project uses the browser's native scrolling engine while visually hiding the standard vertical scrollbar track.

This provides:

- 🖱️ Mouse-wheel scrolling
- 👆 Touch scrolling
- 💻 Trackpad scrolling
- ⌨️ Keyboard navigation
- ♿ Native browser scroll behavior

The scrollbar is visually minimized without replacing the browser's native scrolling mechanism with a custom JavaScript scroll engine.

---

## ♿ Accessibility Considerations

Accessibility is considered at the HTML and interaction level.

The project uses semantic elements such as:

```html
<header>
<nav>
<main>
<section>
<article>
<figure>
<address>
<footer>
```

Additional considerations include:

- 🏷️ Descriptive headings
- 🧭 Logical document hierarchy
- 🖼️ Alternative text for meaningful images
- 📝 Proper form labeling where applicable
- 🔗 Descriptive links
- 🎯 Visible interactive states
- 🎨 Theme-aware text contrast
- 📱 Responsive content presentation
- ⌨️ Native browser interaction wherever possible

> **Note:** Accessibility conformance should always be verified with automated and manual testing for a formal WCAG claim. This README describes the project's accessibility-oriented implementation rather than guaranteeing certification.

---

## 🔍 SEO-Friendly Architecture

The page is structured to provide a clean foundation for search engine discovery and professional sharing.

Recommended SEO elements used or supported by the project include:

- Meaningful `<title>` element
- Meta description
- Semantic HTML5 landmarks
- Logical heading hierarchy
- Descriptive image `alt` attributes
- Descriptive anchor text
- Human-readable page content
- Mobile-responsive layout
- Clean document structure
- Relevant personal/professional keywords

Example metadata structure:

```html
<title>Jatin Hemraj Joshi — Web Developer | Resume & CV</title>
<meta
  name="description"
  content="Explore the resume, skills, experience, projects, education, and professional profile of Jatin Hemraj Joshi."
/>
```

---

## 🎨 Design Tokens

The project uses CSS custom properties to keep colors and visual values centralized.

### Light / Dark Theme Token Overview

| Token | 📜 Light Mode | 🌑 Dark Mode | Purpose |
|---|---|---|---|
| `--bg-canvas` | `#EBE7DE` | `#090A0F` | Main page background |
| `--bg-surface` | `#E2DDD5` | `#14171F` | Secondary surfaces |
| `--bg-card` | `#FAF6F0` | `#12151D` | Card backgrounds |
| `--text-main` | `#141414` | `#FFFFFF` | Primary text |
| `--text-muted` | `#4A4039` | `#8F96A3` | Secondary text |
| `--accent-primary` | `#D84A28` | `#DC2626` | Accent / CTA / highlights |
| `--border-vintage` | `#141414` | `rgba(255,255,255,.22)` | Borders and frames |

Centralizing these values makes the visual system easier to maintain and extend.

---

## ✒️ Typography System

Typography is an important part of the editorial identity.

### 📰 Display Typography

**Playfair Display** is used for large editorial headings and prominent resume titles.

Its high-contrast serif structure creates a traditional magazine/newspaper character.

### ⌨️ Metadata Typography

**Space Mono** is used for:

- Issue numbers
- Metadata
- Dates
- Labels
- Technical information
- Small editorial annotations

### 🧑‍💻 Body Typography

**Plus Jakarta Sans** provides a modern sans-serif reading experience for longer descriptions and professional information.

This creates a deliberate contrast between:

> **Editorial display typography + modern digital readability**

---

## 🏗️ Semantic HTML Architecture

The website follows a structured document model rather than using generic `<div>` elements for every component.

A simplified architecture looks like this:

```text
<body>
│
├── Header
│   ├── Brand / Identity
│   ├── Navigation
│   └── Theme Controls
│
├── Main
│   ├── Hero / Profile
│   ├── About
│   ├── Experience
│   ├── Education
│   ├── Skills
│   ├── Projects
│   ├── Achievements / Additional Information
│   └── Contact
│
└── Footer
    ├── Social Links
    ├── Contact Information
    └── Copyright
```

This structure improves maintainability, accessibility, content hierarchy, and future extensibility.

---

## 📂 Project Structure

```text
retro-resume/
│
├── index.html          # Semantic HTML5 document and resume content
├── style.css           # Complete CSS3 design system and responsive styling
└── README.md           # Project documentation
```

If additional assets are introduced later, the recommended structure is:

```text
retro-resume/
│
├── index.html
├── style.css
├── README.md
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
│
└── screenshots/
```

---

## 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| 🧱 HTML5 | Semantic document structure and content |
| 🎨 CSS3 | Layout, responsive design, animations, themes |
| 📐 CSS Grid | Structured multi-column layouts |
| 📦 Flexbox | Component alignment and navigation |
| 🎭 CSS Custom Properties | Design tokens and theme management |
| ✨ CSS Transforms | Card movement and micro-interactions |
| 🌀 CSS Transitions | Smooth UI state changes |
| 📱 Media Queries | Responsive behavior |
| 🔤 Web Fonts | Editorial typography |

### 🚫 Intentionally Not Used

- ❌ React
- ❌ Vue
- ❌ Angular
- ❌ Bootstrap
- ❌ Tailwind CSS
- ❌ jQuery
- ❌ JavaScript runtime
- ❌ Large UI component libraries

The project is intentionally kept lightweight to demonstrate what can be achieved using the fundamentals of modern web development.

---

## ⚡ Performance Philosophy

The project follows a lightweight architecture so that the browser has very little runtime work to perform.

Performance-conscious decisions include:

- 🚫 No JavaScript application runtime
- 🚫 No large frontend framework
- 🚫 No CSS framework dependency
- 🧩 Small number of source files
- 🎨 CSS-based interactions
- 📱 Responsive layout without duplicated markup
- 🧠 Native browser capabilities wherever possible

For production deployment, images should also be compressed and served in modern formats such as **WebP** or **AVIF** when appropriate.

---

## 🚀 Getting Started

Because this is a static HTML/CSS project, there is no package manager or build process required.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/retro-editorial-resume.git
```

### 2️⃣ Open the Project

```bash
cd retro-editorial-resume
```

### 3️⃣ Run Locally

The simplest option is to open `index.html` directly in your browser.

For a better development workflow, use a local static server such as VS Code Live Server or another static HTTP server.

Example with Python:

```bash
python3 -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

---

## 🌍 Deployment

This project can be deployed to almost any static hosting platform.

Recommended options include:

- ▲ Vercel
- 🌐 Netlify
- 🟧 GitHub Pages
- ☁️ Cloudflare Pages

### Netlify Deployment

1. Push the project to GitHub.
2. Open Netlify.
3. Import the GitHub repository.
4. Select the repository.
5. Since the project has no build step, leave the build command empty.
6. Set the publish directory to the project root if required.
7. Deploy the site.

The project is then available through a public HTTPS URL.

---

## 🧪 Testing Checklist

Before considering the project production-ready, test the following:

### 📱 Responsive Testing

- [ ] Mobile portrait
- [ ] Mobile landscape
- [ ] Tablet
- [ ] Laptop
- [ ] Desktop
- [ ] Large desktop screens

### 🌗 Theme Testing

- [ ] Light theme renders correctly
- [ ] Dark theme renders correctly
- [ ] Text remains readable in both themes
- [ ] Cards maintain sufficient contrast
- [ ] Borders remain visible
- [ ] Interactive elements remain identifiable

### 🧭 Navigation Testing

- [ ] All navigation links work
- [ ] Mobile menu opens correctly
- [ ] Mobile menu closes correctly
- [ ] Hamburger transforms correctly
- [ ] Anchor scrolling works

### ♿ Accessibility Testing

- [ ] Keyboard navigation works
- [ ] Focus states are visible
- [ ] Images have appropriate alt text
- [ ] Headings follow a logical hierarchy
- [ ] Form controls have labels
- [ ] Links have descriptive text

### 🔍 SEO Testing

- [ ] Page title is descriptive
- [ ] Meta description is present
- [ ] Heading hierarchy is logical
- [ ] Images use useful alt text
- [ ] Important content is present in HTML
- [ ] Canonical URL is configured when appropriate
- [ ] `robots.txt` and sitemap are added when needed

### ⚡ Performance Testing

- [ ] Images are compressed
- [ ] Unused CSS is removed
- [ ] Fonts are optimized
- [ ] Lighthouse audit is reviewed
- [ ] No unnecessary dependencies are loaded

---

## 🧠 What This Project Demonstrates

This project demonstrates practical knowledge of:

- 🧱 Semantic HTML5
- 🎨 Modern CSS architecture
- 📐 Flexbox and CSS Grid
- 📱 Responsive web design
- 🌗 CSS theme systems
- ✨ CSS animations and transitions
- 🃏 Advanced hover interactions
- 📰 Editorial visual design
- ♿ Accessibility-oriented markup
- 🔍 SEO-friendly structure
- ⚡ Lightweight static-site architecture
- 🧹 Clean and maintainable frontend code

It is especially useful as a demonstration that a visually sophisticated interface does not necessarily require a JavaScript framework.

---

## 🔮 Future Improvements

Potential future iterations could include:

- [ ] Add downloadable PDF resume
- [ ] Add print-specific CSS for physical CV generation
- [ ] Add Open Graph and Twitter/X metadata
- [ ] Add JSON-LD structured data for a Person/Portfolio profile
- [ ] Add a dedicated project case-study page
- [ ] Add an accessible contact form backed by a serverless endpoint
- [ ] Add automated HTML/CSS validation to CI
- [ ] Add Lighthouse performance/accessibility checks to CI
- [ ] Add optimized WebP/AVIF image assets
- [ ] Add a custom 404 page
- [ ] Add a sitemap and robots.txt
- [ ] Add privacy-friendly analytics if required

---

## 📸 Screenshots

For a professional GitHub presentation, screenshots can be added here:

```text
screenshots/
├── desktop-light.png
├── desktop-dark.png
├── mobile-light.png
└── mobile-dark.png
```

Then embed them using Markdown:

```md
![Desktop Light Theme](./screenshots/desktop-light.png)
![Desktop Dark Theme](./screenshots/desktop-dark.png)
```

---

## 📄 License

This project is primarily a personal portfolio/resume project created by **Jatin Hemraj Joshi**.

If you reuse the design, content, images, or other project assets, make sure you have the appropriate rights or permissions for those assets.

---

## 👨‍💻 Author

### Jatin Hemraj Joshi

**Web Developer | Frontend • Backend • PWA • App Development**

I enjoy building modern, responsive, interactive web experiences and exploring creative frontend design techniques using the web platform.

- 🌐 **Portfolio:** [jj-portfolio-website.netlify.app](https://jj-portfolio-website.netlify.app/)
- 💻 **GitHub:** [GitHub Profile](https://github.com/your-username)
- 📍 **Based in:** Pune, Maharashtra, India

---

## ⭐ Support the Project

If you found this project useful or inspiring:

- ⭐ Star the repository
- 🍴 Fork the project
- 💬 Share feedback
- 🧑‍💻 Explore the source code
- 🚀 Use the ideas in your own projects

---

## 💬 Final Note

> **Good resumes communicate information. Great digital resumes communicate identity.**

This project was designed to combine both: a clear professional resume structure with a distinctive visual identity that makes the experience memorable without sacrificing readability, responsiveness, accessibility, or maintainability.

---

<div align="center">

### 📰 Built with HTML5 & CSS3 · Designed with Intent · Crafted by Jatin Hemraj Joshi

**© 2026 Jatin Hemraj Joshi. All rights reserved.**

</div>
