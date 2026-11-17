# Siddharth Kumar — Personal Portfolio Website
### Modern Educational-Platform & Finance Aesthetic (Inspired by AfterBoards)

This website is an academic submission demonstrating mastery of semantic **HTML5** and modern **CSS3**. It represents Siddharth Kumar's academic background, campus leadership, competitive achievements, and professional qualifications.

---

## Quick Start (How to View)
1. Navigate into the `siddharth-portfolio/` folder.
2. Double-click **`index.html`** or right-click and select **Open with Google Chrome**.
3. **No installation required**: No Node.js, no npm, no build step, no server. Works immediately through standard `file://` protocol.

---

## Project Structure
```
siddharth-portfolio/
│
├── index.html                 # 01 / Home: Hero, Multidisciplinary Intro, At a Glance, Areas of Interest, Development Preview, Achievements, Contact CTA
├── about.html                 # 02 / About: Multidisciplinary Bio, My Approach, Personal Interests (Voice & Languages), Editorial Philosophy Quote
├── education.html             # 03 / Education: Timeline (IIM Bangalore BBA & GGDSD College BA Econ Hons), Academic Focus Areas
├── experience.html            # 04 / Experience: Campus Leadership (Enactus SD College Sub-Head), Student Council (Sports Minister), Chess Medals
├── development.html           # 05 / Professional Development: Qualifications (US CMA, FRM, IBM Data Science, IIBF AML/KYC, MOS Excel), Applied Skills, Future Interests
│
├── css/
│   └── style.css              # Shared Master Stylesheet (CSS Variables, Grid, Flexbox, Typography Scale, Media Queries, Subtle Animations)
│
└── assets/
    ├── images/
    │   └── portrait-placeholder.svg  # Custom SVG geometric portrait frame with SK seal & finance tags
    └── icons/
        ├── analytics.svg      # Quantitative analysis icon
        ├── arrow-right.svg    # Smooth directional UI icon
        ├── badge.svg          # Honours & distinction badge icon
        ├── bank.svg           # Commercial banking icon
        ├── check.svg          # Verified checkmark icon
        ├── chess-bronze.svg   # State tournament bronze medal icon
        ├── chess-gold.svg     # State tournament gold medal icon
        ├── data-science.svg   # Computational network icon
        ├── education.svg      # Academic mortarboard icon
        ├── excel.svg          # Spreadsheet & modeling icon
        ├── in-progress.svg    # Active study & progress icon
        ├── leadership.svg     # Shield & governance icon
        ├── location.svg       # Location pin icon
        ├── mail.svg           # Mail contact icon
        ├── mic.svg            # Voice & broadcasting icon
        └── phone.svg          # Telephone icon
```

---

## Portrait Photo
The home page features your official portrait photograph (`assets/images/siddharth-portrait.jpg`), beautifully framed with:
- Subtle rounded corners (`--radius-lg`)
- Light beige border and warm ivory/white gradient background
- Floating terracotta `SK.` monogram seal
- Hover lift interaction and smooth zoom transition
- Bottom metadata caption: `FINANCE • ECONOMICS • BUSINESS | CHANDIGARH, IN`

---

## Design System Specifications

### 1. Color Palette
- **Midnight Navy (`#172B4D`)**: Primary headings, navigation branding, and global dark footer.
- **Warm Ivory (`#F5F1E8`)**: Hero section backdrop, editorial quote boxes, and alternating content sections.
- **Pure White (`#FFFFFF`)**: High-contrast cards and reading surfaces.
- **Charcoal (`#292D32`)**: High-legibility body copy.
- **Burnt Terracotta (`#C47745`)**: Primary CTAs, active page indicators, and key metric highlights.
- **Muted Sage (`#78918A`)**: Secondary cards, academic badges, and supporting tags.
- **Soft Blue (`#E7EDF5`)**: Informational sections and compliance modules.
- **Light Beige (`#EAE3D6`)**: Subtle borders, architectural lines, and dividers.

### 2. Typography
- **Manrope**: Navigation links, buttons, and interface labels.
- **Inter**: Body text and descriptive paragraphs.
- **DM Sans**: Section headings, card titles, and institution headers.
- **Playfair Display**: Hero headings and the central philosophical quote.
- **Space Mono**: Section labels (`01 / INTRODUCTION`), dates (`2026–2029`), and metadata tags.

### 3. Responsive Breakpoints
- **Desktop (> 1024px)**: 1200px max-width container, two-column hero, 3- and 4-column card grids.
- **Tablet (<= 1024px & <= 768px)**: Flexible 2-column grids, stacked hero, responsive font clamps.
- **Mobile (<= 480px)**: Single-column stacked cards, full-width buttons, horizontal-scroll navigation with touch momentum (zero JavaScript required).
