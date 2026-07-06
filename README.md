# Pricing Page

A responsive pricing page built from scratch with plain HTML and CSS, as a hands-on practice project for core layout and styling concepts — Flexbox, positioning, hover states, and responsive design.

## What's included

**Navbar**
- Built with Flexbox (`justify-content: space-between`) to place the logo on the left and nav links on the right
- Custom SVG logo mark alongside the wordmark
- Collapses into a stacked layout on small screens

**Pricing Cards**
- Three plans — Basic, Standard, Premium — laid out side by side with Flexbox
- The Standard (middle) card stands out with a dark background, a raised `scale()` transform, and a bigger shadow
- A "Most Popular" badge is pinned to the top of the Standard card using `position: absolute` inside a `position: relative` parent
- A rotated "-20%" discount badge floats on the Standard card's price using the same absolute-positioning technique
- All three cards lift slightly with a deeper shadow on hover, with a smooth `transition`
- Stacks into a single column below 900px screen width

**Feature Comparison Table**
- A semantic `<table>` with `<thead>`/`<tbody>` comparing all three plans feature-by-feature
- Dark header row, zebra-striped body rows via `nth-child(even)`, and a hover highlight on individual rows

**Sticky Contact Bar**
- A `position: fixed` bar pinned to the bottom of the viewport with a "Contact Us" button, always visible while scrolling
- Body padding added to prevent the fixed bar from covering page content

## Files

- `index.html` — page structure and content
- `style.css` — all styling, including responsive breakpoints

## Testing

Verified by resizing the browser window down to mobile widths and scrolling through the full page to confirm the sticky bar, hover states, and responsive stacking all behave correctly.