# MATRIX THEME for Obsidian

A neon-green, cyberpunk Matrix-inspired theme for Obsidian with Live Preview parity, always-on animated H1/inline title glow, and cohesive styling across links, blockquotes, code, tables, and more. Ships with dark and light variants.

![Matrix Theme screenshot](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/SCR-20250807-rqus-AcoictKbzaOc4V2UsvJBUCUiRksYug.png)

## Features

- Live Preview parity
  - Headings h1–h6 mirror Reading view colors, weights, and spacing
  - Blockquotes in editor match Reading view (background, border-left, radius, shadow)
- Cyberpunk title effect
  - Always-on animated gradient/sheen for `h1` and `.inline-title` with subtle pulse and glow
- Link glow on hover with underline and offset
- Code blocks styled as a “MATRIX TERMINAL” with mono font and chromatic glow
- Tables, tags, inputs, menus, tabs, Dataview, and Mermaid colors aligned to theme variables
- Light and dark modes included
- Optional “digital rain” overlay


## Options

- Digital Rain overlay (opt‑in): the CSS includes a selector that enables rain when the `matrix-rain-on` class is present on `<body>`. Add that class via a community plugin (e.g., Style Settings or Custom Classes). To keep the rain always on, you can replace the selector in the CSS from `\.matrix-rain-on .workspace::before` to `body .workspace::before`.

