---
version: alpha
name: "My Project 1 Guide"
description: "It should feel like chocolate with little strawberry bits in it."
omitted: [rounded]
colors:
  defaultText: "#EBE0DA"
  defaultBackground: "#3C352B"
  alternateText: "#EBE0DA"
  alternateBackground: "#3C352B"
  action: "#F98BC5"
  hover: "#FFF799"
  buttonText: "#3C352B"
typography:
  rootSize: 16px

fontFamilies:
  body: "Open Sans"
  headings: "Ubuntu"

sizes:
  body: 1rem
  small: 0.8rem
  h1: 2.441rem
  h2: 1.953rem
  h3: 1.563rem
  h4: 1.25rem
  h5: 1rem
  h6: 0.8rem

spacing:
  sm: 1.125rem
  md: 1.5rem
  lg: 3rem
  xl: 4.5rem
  xxl: 6rem
---

## Overview

It should feel like chocolate with little strawberry bits in it.

## Colors

Default colors apply to the page. Alternate colors apply to grouped sections. Links and buttons use the action color, then hover on pointer hover. Button text uses buttonText. Keep links underlined.

- Default Text on Default Background: 9.33:1 — meets the 4.5:1 target for normal text.
- Alternate Text on Alternate Background: 9.33:1 — meets the 4.5:1 target for normal text.
- Links and buttons on Default Background: 5.49:1 — meets the 4.5:1 target for normal text.
- Links and buttons on hover on Default Background: 10.95:1 — meets the 4.5:1 target for normal text.
- Button text: 5.49:1 — meets the 4.5:1 target for normal text.
- Button text on hover: 10.95:1 — meets the 4.5:1 target for normal text.

## Typography

The base font size is 16px. Use Open Sans for body text and Ubuntu for headings. All size values use rem so changing the root size scales the full type system.

## Layout

Default line height is 1.6. Default page width is 960px. Use the spacing scale for gaps and padding: sm 1.125rem, md 1.5rem, lg 3rem, xl 4.5rem, xxl 6rem.

## Do and Don't

### Do

- Use the same exported `style.css` on every page so the type, colors, and spacing stay consistent.
- Use headings in order, beginning with one `h1`, then moving through lower heading levels as the content needs them.
- Keep underlined links and visible keyboard focus so people can find and use interactive content.

### Don't

- Create one-off colors, font sizes, or spacing values when an exported choice already fits the purpose.
- Rely on color alone to communicate meaning; use clear text, labels, or icons too.
- Change a design decision in only one file. Update the form and export a fresh set of files when the system changes.
