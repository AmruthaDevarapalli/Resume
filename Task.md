# Resume Website — Maintenance Task

## Goal

Update my static HTML resume website (hosted on GitHub Pages) to reflect the latest content from my attached resume PDF and my GitHub projects. Make **incremental edits** to the existing files — do not recreate them from scratch.

## Attached Files

- **Resume PDF** — attached to this conversation. Extract all content (name, contact, summary, work experience, education, skills, certifications/achievements) from it.

## GitHub Projects to Include

Fetch the latest README info from these two repositories and update the **GitHub Projects** section accordingly:

1. https://github.com/AmruthaDevarapalli/SemanticLens
2. https://github.com/AmruthaDevarapalli/App-Pulse

## Existing File Structure

```
index.html      — Main HTML page (sections: Hero, Experience, Education, GitHub Projects, Technical Skills, Achievements, Footer)
styles.css      — All CSS (dark theme, gradient blobs, AOS animations, responsive)
script.js       — All JS (AOS init, navbar scroll, mobile toggle, intersection observer, blob parallax)
Resume.pdf      — PDF resume (for download, not currently linked)
Task.md         — This file
```

## Current Website Sections (in order)

1. **Hero** — Name, professional summary, email, location, GitHub profile button
2. **Work Experience** — Timeline layout with role cards
3. **Education** — Grid of education cards
4. **GitHub Projects** — Two project cards (SemanticLens, App Pulse) with descriptions, tech stacks, highlights
5. **Technical Skills** — Three category cards (Data Analysis, Program Management, Technical Systems)
6. **Achievements** — Three achievement cards (Spot Award, JEE Advanced, NSEJS)
7. **Footer** — Email and GitHub icon links

## Design Specifications (preserve these)

- **Theme**: Dark background (`#0f0e17`) with purple/pink gradient accents
- **Fonts**: Google Fonts — Inter (body) + Playfair Display (headings)
- **Icons**: Font Awesome 6.5.1
- **Animations**: AOS (Animate on Scroll) library
- **Background**: Three animated gradient blobs with mouse parallax
- **Navbar**: Fixed, glassmorphism on scroll, active section highlighting via IntersectionObserver
- **Favicon**: Blue document icon with black text lines on transparent background (inline SVG data URI)
- **Responsive**: Mobile nav toggle, single-column grids below 768px
- **No phone number displayed** on the page

## How to Execute This Task

1. **Extract** content from the attached resume PDF.
2. **Fetch** latest project info from the two GitHub repo URLs above.
3. **Compare** extracted content against what's currently in `index.html`.
4. **Make incremental edits** to `index.html`, `styles.css`, and `script.js` as needed:
   - Update text content if the resume has changed (new roles, updated skills, new education, etc.)
   - Update GitHub Projects section if the repos have new descriptions, tech stacks, or highlights
   - Add new sections if the resume contains new categories not currently represented
   - Remove content no longer in the resume
5. **Do not** change the visual design, color scheme, fonts, animations, or layout unless explicitly asked.
6. **Do not** add a phone number to the page.
7. **Do not** add a resume download button unless asked.