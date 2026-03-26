# autox.tools design style

Reference for all projects under autox.tools.

## Font
- JetBrains Mono via Google Fonts
- Weights: 300 (headings), 400 (body), 500 (labels)

## Colors
- Background: `#0a0a0a`
- Text: `#e0e0e0`
- Subtitle/muted: `#444`
- Description: `#555`
- Accent: `#ff6b35`

## Background
Subtle dot grid via `body::before`:
```css
background-image: radial-gradient(circle, #ffffff06 1px, transparent 1px);
background-size: 24px 24px;
```

## Typography
- All lowercase
- Headings: weight 300, letter-spacing -1px
- Subtitles: weight 400, uppercase, letter-spacing 3px, color #444
- Descriptions: weight 300, 0.65rem, letter-spacing 0.5px

## Interactive elements
- No borders or outlines
- Hover: subtle orange glow
```css
background: rgba(255, 107, 53, 0.04);
box-shadow: 0 0 30px rgba(255, 107, 53, 0.08), 0 0 60px rgba(255, 107, 53, 0.04);
```
- Transition: 0.4s ease

## Canonical reference
`index.html` in this repo.
