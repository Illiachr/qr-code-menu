# Project Guidelines: Giardino Verde QR Code Menu

## Tech Stack & Architecture
- Pure HTML5 + CSS3 + JS (No framework JS or Tailwind).
- Responsive layout with desktop full-screen section snap capabilities.

## Design System Rules
- **Background**: Dark graphite `#181a1a` / `#1E1E1E`.
- **Text Color**: Cream `#F7F5EC`, subtext `#D1CBBF`.
- **Accents**: Red `#C62128`, Green `#427A38`.
- **Fonts**:
  - Main headers: `Cabin Sketch`
  - Item Titles & Prices: `Shadows Into Light Two`
  - Descriptions & Notes: `Patrick Hand`

## Code Standards
1. **No Layout Hacks**: Never use transparent text (`color: transparent`) or duplicate string padding to force alignment. Use **CSS Grid** (`display: grid`) or Flexbox.
2. **Typography Scaling**:
   - Desktop headers: ~`3rem`, mobile headers: ~`2.2rem`.
   - Desktop titles: ~`1.6rem`, mobile titles: ~`1.3rem`.
3. **HTML Semantics**: Keep text-based blocks inside semantic `<p>`, `<span>`, or `<section>` tags. Prefer styled typography over static image assets for footer notices and text blocks.
4. **Fallback Values**: Use fallback values for CSS-variables

```