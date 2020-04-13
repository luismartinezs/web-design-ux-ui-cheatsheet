# WEB DESIGN UX/UI CHEATSHEET

Based on [Refactoring UI](https://refactoringui.com/book/#get-refactoring-ui)

## Design personality:

- Font
- Color
- Button border radius
- Language (formal, informal)

## Define beforehand, pick from while building:

- Color palette
- Font sizes: Stick to px or rem
- White space (margin / padding): Use a relative (non linear) scale
- Shadow scale (function of z factor --height with respect to the viewer)

## Font

- Basic font choice: -apple-system, Segoe UI, Roboto, Noto Sans, Ubuntu, Cantarell, Helvetica Neue;
- Google fonts filter for fonts with +10 styles, sort by popularity
  - Serif: https://fonts.google.com/?stylecount=10&sort=popularity&category=Serif
  - Sans serif: https://fonts.google.com/?stylecount=10&sort=popularity&category=Sans+Serif
- Steal font choices from good designs

## Text

- Paragraph width around 20-35em (avoi too long lines)
- Line height depends on font size and paragraph width. Finding the next line when reading is easy
- Links: no need to make them all blue, bold them or underline on hover if not part of main user flow
- When to tinker with letter-spacing?
  - Narrower headlines
  - Improve all caps legibility

## Color

- Use HSL color scale
- Increase saturation for lighter and darker colors
- From dark to light, change the hue, not just the brightness and saturation
- Don't use pure grey, use a very desaturated color
- Design should work in grayscale

## 3D:

- Shadows: for modals, inset / outset shapes
- Leverage overlapping elements
- Avoid image clashing with overlaying text:
  - Add dark overlay
  - Lower image contrast
  - Colorize image
  - Add text shadow and lower a bit image contrast

## Icons:

- Do not use same versions for different scales: redraw

## Aesthetics:

- Custom elements: checkboxes, radio buttons, links, quotes, icon bullet lists...
- Colorful borders in one side
- Fewer borders: separating elements is better accomplished with shadows, bg colors and spacing
- Dropdowns, tables, selection by radio buttons... shouldn't look boring. They can be beautiful
- Colored backgrounds, patterns, textures

## Responsive

- Design mobile first
- Large elements shrink more than small elements

## Visual hierarchy:

- Hierarchy factors:
  - Position
  - Size
  - Weight
  - Contrast
  - Color
  - Shape
- To emphasize something, you can also de-emphasize other elements
- Balance weight of icons VS text with contrast
