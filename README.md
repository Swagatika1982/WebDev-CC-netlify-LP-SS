# WebDev-CC-netlify-LP-SS
Desktop-first documentation-style landing page inspired by the **Mintlify** website 
# Mintlify-Inspired Landing Page (HTML + CSS)

Desktop-first documentation-style landing page inspired by the **Mintlify** website layout and content structure.

> ✅ **Constraints followed**
- HTML + CSS only
- No JavaScript
- No TailwindCSS
- Desktop-only (no responsive rules)

---

## Sections Recreated

This project recreates the following sections (structure + layout patterns):

1. **Top Navigation Bar**
   - Logo area
   - Primary navigation links
   - Primary CTA button (and optional secondary link)

2. **Hero Section**
   - Main headline
   - Short supporting description
   - Email input + CTA button
   - Large hero illustration / screenshot area (image placeholder)

3. **Documentation Preview Section**
   - Static sidebar navigation (docs-style)
   - Main content area
   - Content cards + code block preview

4. **Trusted By / Logos Row**
   - Horizontal row of company logos (placeholders or provided assets)

5. **Feature Highlights**
   - Two-column feature blocks (text + visual placeholder)
   - Alternating layout (left/right)

6. **Intelligent Assistant / UI Preview**
   - Large UI mock section with description
   - Stats/benefit blocks beside the mock image

7. **Enterprise Features**
   - Title + short intro
   - Grid of enterprise feature blocks (security, compliance, etc.)

8. **Case Studies / Customer Stories**
   - Card-based layout with image thumbnails
   - Title, short text, and “Read story” style CTA

9. **Final Call-To-Action**
   - Strong closing headline
   - Two CTA buttons (primary + outline)

10. **Footer**
   - Multi-column links (Product / Resources / Company / Legal)
   - Branding + short tagline
   - Copyright row

---

## Fonts Used

- **Primary font:** Inter  
  Loaded via Google Fonts in `index.html`.

Fallback stack:
`Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif`

---

## Colors Used

These values are defined as CSS variables in `styles.css` under `:root`.

### Core
- **Background:** `#ffffff`
- **Primary Text:** `#0b1220`
- **Muted Text:** `#5b667a`

### Surfaces + Borders
- **Border:** `#e6eaf2`
- **Surface:** `#f7f9fc`
- **Surface 2:** `#f2f5fb`

### Primary Actions
- **Primary Button / Dark:** `#0b1220`
- **Primary Hover:** `#111a2e`

### Accent / Utility
- **Focus ring:** `rgba(11, 18, 32, 0.12)`
- **GET method chip (green):**
  - Background: `#e9fbf0`
  - Border: `#c8f2d8`
  - Text: `#0f7a3a`

> Note: You can swap these to match brand guidelines (e.g., from Brandfetch) without changing the layout.

---

## Project Structure

```txt
.
├── index.html
├── styles.css
└── assets/
    ├── logo.svg
    ├── hero-illustration.png
    ├── assistant-ui.png
    ├── feature-1.png
    ├── feature-2.png
    ├── story-1.png
    ├── story-2.png
    ├── story-3.png
    ├── logo-1.svg
    ├── logo-2.svg
    └── ...



How to Run

Download or clone this repository.

Open index.html in your browser (Chrome recommended).

Ensure all images are placed in the assets/ folder with the correct filenames.







