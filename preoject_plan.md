You are building a standalone, single-page static website that exactly replicates the attached poster design for CANVAC-8 by Medivet.

This page will be opened when users scan a QR code printed on the physical poster.  
It must look identical to the design, be lightweight, and optimized **only for mobile devices**.

---

### Provided materials:
1. Poster image — reference for exact layout, hierarchy, and spacing.
2. Text extraction — extract both Khmer and English text from the attached image and use it as real text (not images).
3. Fonts and assets:
   - **Khmer fonts:** Koulen, Kantumruy Pro
   - **English font:** Manrope
   - **Logo files:** located in `/images/` folder
4. Background color: `#133588`

---

### Your task:
1. **Create a single static HTML file** with linked CSS (or inline if small).  
   - Use **plain HTML and CSS only** (no frameworks, no build tools, no JS animations).
   - Design specifically for **mobile** (viewport ~ **390px × 844px**, iPhone 14 Pro).
   - Use responsive units (`vw`, `vh`, `%`, `rem`) to scale smoothly.

2. **Recreate the layout exactly** as shown in the provided poster:  
   - Match text hierarchy, alignment, and spacing.  
   - Maintain original color tones and text placement.  
   - Include Khmer and English text exactly as extracted.  
   - Use `img` tags for product pack shots and logos (from the images folder).  
   - Reproduce section background boxes, dividers, and shaded blocks precisely.

3. **Apply the following design specs:**
   - Background color: `#133588`
   - Fonts:
     - Khmer headings and subheadings: **Koulen**
     - Khmer body text: **Kantumruy Pro**
     - English text: **Manrope**
   - Text color palette:
     - White (#FFFFFF)
     - Yellow/Gold accents (sample from poster)
     - Light blue boxes and highlights (sample from poster)
   - Include consistent margins and padding for mobile readability.

4. **Meta setup:**
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <meta property="og:title" content="CANVAC-8 — Medivet Animal Health" />
   <meta property="og:description" content="DHPPiL (8 in 1 Vaccine) — 1ML" />
   <meta property="og:image" content="/images/canvac8-poster.jpg" />
   <meta name="theme-color" content="#133588" />

Do not include:
- Any scroll or hover animations
- Smooth scrolling
- Download PDF buttons
- Desktop breakpoints (mobile-only layout required)

Deliverables:
- A production-ready HTML file using the extracted text.
- A clean, well-commented CSS block or stylesheet (style.css).
- The output must visually match the attached CANVAC-8 poster 1:1 when viewed on a mobile screen.