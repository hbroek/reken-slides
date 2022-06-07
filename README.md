# reken-slides
HTML Slide show web page written with Reken

To customize:
- Use the slides array for content. Every object entry is one slide. The object supports the following properties:
  - title: slide title
  - bullets: an array with bullet points. The text can contain HTML for formatting.
  - left: Image to the left of the bullets;
  - right: Image to the right of the bullets;
  - bottom: Image below the bullets
  - frame embed a web page, for example to do a demo, for space sake probably do not want to list bullets on this slide
- Color scheme, there are the color vars: --color-slides-main-h (hue) and color-slides-main-s (saturation). The lightness is in --color-slides-main-l. The secondary color is calculated by adding 45% to the lightness.
- The top left logo and link can be updated in the body>header tag.