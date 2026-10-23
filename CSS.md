# CSS — Complete Study Notes

Definition, explanation, and a short runnable example for every topic in the W3Schools CSS tutorial (189 topics). Prose is rewritten for clarity; all examples are self-contained snippets.

## Contents

- [1. CSS Home](#1-css-home)
- [2. CSS Introduction](#2-css-introduction)
- [3. CSS Syntax](#3-css-syntax)
- [4. CSS Selectors](#4-css-selectors)
- [5. Grouping Selectors](#5-grouping-selectors)
- [6. CSS How To](#6-css-how-to)
- [7. Add Internal CSS](#7-add-internal-css)
- [8. Add Inline Style](#8-add-inline-style)
- [9. Multiple Style Sheets](#9-multiple-style-sheets)
- [10. CSS Comments](#10-css-comments)
- [11. CSS Errors](#11-css-errors)
- [12. CSS Backgrounds](#12-css-backgrounds)
- [13. Background Image](#13-background-image)
- [14. Background Repeat](#14-background-repeat)
- [15. Background Attachment](#15-background-attachment)
- [16. Background Shorthand](#16-background-shorthand)
- [17. CSS Borders](#17-css-borders)
- [18. Border Width](#18-border-width)
- [19. Border Color](#19-border-color)
- [20. Border Sides](#20-border-sides)
- [21. Border Shorthand](#21-border-shorthand)
- [22. Rounded Borders](#22-rounded-borders)
- [23. CSS Margins](#23-css-margins)
- [24. Margin Collapse](#24-margin-collapse)
- [25. CSS Padding](#25-css-padding)
- [26. Padding and box-sizing](#26-padding-and-box-sizing)
- [27. CSS Height / Width](#27-css-height-/-width)
- [28. Min / Max](#28-min-/-max)
- [29. CSS Box Model](#29-css-box-model)
- [30. CSS Outline](#30-css-outline)
- [31. Outline Width](#31-outline-width)
- [32. Outline Color](#32-outline-color)
- [33. Outline Shorthand](#33-outline-shorthand)
- [34. Outline Offset](#34-outline-offset)
- [35. CSS Text](#35-css-text)
- [36. Text Alignment](#36-text-alignment)
- [37. Text Decoration](#37-text-decoration)
- [38. Text Decoration Styles](#38-text-decoration-styles)
- [39. Text Transformation](#39-text-transformation)
- [40. Text Spacing](#40-text-spacing)
- [41. Text Shadow](#41-text-shadow)
- [42. CSS Fonts](#42-css-fonts)
- [43. Font Web Safe](#43-font-web-safe)
- [44. Font Fallbacks](#44-font-fallbacks)
- [45. Font Style](#45-font-style)
- [46. Font Size](#46-font-size)
- [47. Font Google](#47-font-google)
- [48. Font Pairings](#48-font-pairings)
- [49. Font Shorthand](#49-font-shorthand)
- [50. CSS Links](#50-css-links)
- [51. Link Buttons](#51-link-buttons)
- [52. CSS Lists](#52-css-lists)
- [53. CSS Tables](#53-css-tables)
- [54. Table Size](#54-table-size)
- [55. Table Alignment](#55-table-alignment)
- [56. Table Styling](#56-table-styling)
- [57. Responsive Tables](#57-responsive-tables)
- [58. CSS Display](#58-css-display)
- [59. Hiding Elements](#59-hiding-elements)
- [60. CSS Max-width](#60-css-max-width)
- [61. CSS Position](#61-css-position)
- [62. Fixed and Absolute Positioning](#62-fixed-and-absolute-positioning)
- [63. Sticky Positioning](#63-sticky-positioning)
- [64. Position Offsets](#64-position-offsets)
- [65. CSS Z-index](#65-css-z-index)
- [66. CSS Overflow](#66-css-overflow)
- [67. Overflow X and Y](#67-overflow-x-and-y)
- [68. CSS Float](#68-css-float)
- [69. Clear and Clearfix](#69-clear-and-clearfix)
- [70. display: inline-block](#70-display:-inline-block)
- [71. CSS Align](#71-css-align)
- [72. Horizontal Align](#72-horizontal-align)
- [73. Vertical Align](#73-vertical-align)
- [74. CSS Combinators](#74-css-combinators)
- [75. CSS Pseudo-classes](#75-css-pseudo-classes)
- [76. Interactive Pseudo-classes](#76-interactive-pseudo-classes)
- [77. Structural Pseudo-classes](#77-structural-pseudo-classes)
- [78. CSS Pseudo-elements](#78-css-pseudo-elements)
- [79. Text Pseudo-elements](#79-text-pseudo-elements)
- [80. Content Pseudo-elements](#80-content-pseudo-elements)
- [81. CSS Opacity](#81-css-opacity)
- [82. CSS Navigation Bars](#82-css-navigation-bars)
- [83. Vertical Navbar](#83-vertical-navbar)
- [84. Horizontal Navbar](#84-horizontal-navbar)
- [85. CSS Dropdowns](#85-css-dropdowns)
- [86. Advanced Dropdowns](#86-advanced-dropdowns)
- [87. CSS Image Gallery](#87-css-image-gallery)
- [88. CSS Image Sprites](#88-css-image-sprites)
- [89. CSS Attribute Selectors](#89-css-attribute-selectors)
- [90. Advanced Attribute Selectors](#90-advanced-attribute-selectors)
- [91. CSS Forms](#91-css-forms)
- [92. Style Inputs](#92-style-inputs)
- [93. Input Focus / Icons](#93-input-focus-/-icons)
- [94. Other Form Elements](#94-other-form-elements)
- [95. CSS Counters](#95-css-counters)
- [96. Nested Counters](#96-nested-counters)
- [97. CSS Units](#97-css-units)
- [98. Absolute Units](#98-absolute-units)
- [99. Relative Units](#99-relative-units)
- [100. CSS Inheritance](#100-css-inheritance)
- [101. CSS Specificity](#101-css-specificity)
- [102. Specificity Hierarchy](#102-specificity-hierarchy)
- [103. CSS !important](#103-css-!important)
- [104. CSS Math Functions](#104-css-math-functions)
- [105. CSS Optimization](#105-css-optimization)
- [106. CSS Accessibility](#106-css-accessibility)
- [107. CSS Website Layout](#107-css-website-layout)
- [108. CSS Rounded Corners](#108-css-rounded-corners)
- [109. CSS Border Images](#109-css-border-images)
- [110. CSS Multiple Backgrounds](#110-css-multiple-backgrounds)
- [111. Background Size](#111-background-size)
- [112. Background Origin](#112-background-origin)
- [113. Background Clip](#113-background-clip)
- [114. CSS Gradients](#114-css-gradients)
- [115. Radial Gradients](#115-radial-gradients)
- [116. Conic Gradients](#116-conic-gradients)
- [117. CSS Shadows](#117-css-shadows)
- [118. Box Shadow](#118-box-shadow)
- [119. CSS Text Effects](#119-css-text-effects)
- [120. CSS Custom Fonts](#120-css-custom-fonts)
- [121. CSS 2D Transforms](#121-css-2d-transforms)
- [122. CSS 2D Transform Scale](#122-css-2d-transform-scale)
- [123. CSS 2D Transform Skew / Matrix](#123-css-2d-transform-skew-/-matrix)
- [124. CSS 3D Transforms](#124-css-3d-transforms)
- [125. 3D Perspective](#125-3d-perspective)
- [126. 3D Card Flip](#126-3d-card-flip)
- [127. 3D Cube](#127-3d-cube)
- [128. 3D Carousel](#128-3d-carousel)
- [129. CSS Transitions](#129-css-transitions)
- [130. Transition Timing](#130-transition-timing)
- [131. CSS Animations](#131-css-animations)
- [132. Animation Timing](#132-animation-timing)
- [133. Animation Properties](#133-animation-properties)
- [134. CSS Tooltips](#134-css-tooltips)
- [135. Tooltip Arrows](#135-tooltip-arrows)
- [136. CSS Image Styling](#136-css-image-styling)
- [137. Image Effects](#137-image-effects)
- [138. Hover Overlays](#138-hover-overlays)
- [139. CSS Image Modal](#139-css-image-modal)
- [140. CSS Image Centering](#140-css-image-centering)
- [141. CSS Image Filters](#141-css-image-filters)
- [142. CSS Image Shapes](#142-css-image-shapes)
- [143. CSS object-fit](#143-css-object-fit)
- [144. CSS object-position](#144-css-object-position)
- [145. CSS Masking](#145-css-masking)
- [146. Masking - Gradients](#146-masking---gradients)
- [147. Masking - SVG](#147-masking---svg)
- [148. CSS Buttons](#148-css-buttons)
- [149. Hover Effects](#149-hover-effects)
- [150. Button Groups](#150-button-groups)
- [151. CSS Pagination](#151-css-pagination)
- [152. Pagination Styles](#152-pagination-styles)
- [153. CSS Multiple Columns](#153-css-multiple-columns)
- [154. Multiple Column Rules](#154-multiple-column-rules)
- [155. CSS User Interface](#155-css-user-interface)
- [156. CSS Variables](#156-css-variables)
- [157. Overriding Variables](#157-overriding-variables)
- [158. Variables in MQ](#158-variables-in-mq)
- [159. CSS @property](#159-css-@property)
- [160. CSS Box Sizing](#160-css-box-sizing)
- [161. CSS Functions](#161-css-functions)
- [162. CSS Media Queries](#162-css-media-queries)
- [163. Media Query Examples](#163-media-query-examples)
- [164. CSS Flexbox](#164-css-flexbox)
- [165. Flex Container](#165-flex-container)
- [166. Flexbox justify-content](#166-flexbox-justify-content)
- [167. Flexbox Alignment](#167-flexbox-alignment)
- [168. Flex Items](#168-flex-items)
- [169. Responsive Flexbox](#169-responsive-flexbox)
- [170. CSS Grid Layout](#170-css-grid-layout)
- [171. Grid Container](#171-grid-container)
- [172. Grid Tracks](#172-grid-tracks)
- [173. Grid Gaps](#173-grid-gaps)
- [174. Aligning Grid Content](#174-aligning-grid-content)
- [175. Grid Items](#175-grid-items)
- [176. Naming Grid Items](#176-naming-grid-items)
- [177. Grid Item Alignment](#177-grid-item-alignment)
- [178. Grid Item Order](#178-grid-item-order)
- [179. 12-Column Grid Layout](#179-12-column-grid-layout)
- [180. CSS @supports Rule](#180-css-@supports-rule)
- [181. Responsive Web Design](#181-responsive-web-design)
- [182. RWD - The Viewport](#182-rwd---the-viewport)
- [183. RWD - Grid View](#183-rwd---grid-view)
- [184. RWD - Media Queries](#184-rwd---media-queries)
- [185. RWD - Images](#185-rwd---images)
- [186. RWD - Videos](#186-rwd---videos)
- [187. RWD - Frameworks](#187-rwd---frameworks)
- [188. RWD - Templates](#188-rwd---templates)
- [189. CSS Templates](#189-css-templates)

---

## 1. CSS Home
**Definition:** CSS (Cascading Style Sheets) is the language used to style HTML documents — it controls how page elements are displayed on screen and in other media.

**Explanation:**
- HTML supplies the content; CSS decides the visual look of that content
- One set of rules can restyle every page of a site at the same time
- Rules pair a selector with declarations, and live either in a separate `.css` file or inside the page itself
- The usual learning path runs from basic syntax through the box model and layout

**Example:**
```css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```
The page gets a light-blue background, centered white headings, and larger Verdana paragraphs.

---

## 2. CSS Introduction
**Definition:** CSS — short for Cascading Style Sheets — is the styling language of the web; it governs how HTML elements are presented on screen, on paper, and in other media.

**Explanation:**
- A single stylesheet can shape many pages at once, which removes repetitive per-page styling
- Rules are normally stored in external `.css` files, so editing one file retheme an entire site
- CSS covers design concerns: colors, fonts, spacing, layout, and adaptation to different screen sizes
- The same HTML can be shown with completely different appearances just by swapping the stylesheet

**Example:**
```css
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```
A compact stylesheet that changes the page background, heading alignment, and paragraph typography in one pass.

---

## 3. CSS Syntax
**Definition:** Every CSS rule has two parts — a selector that names the elements to affect and a declaration block that carries the styles for them.

**Explanation:**
- The declaration block is wrapped in curly braces `{ }`
- Each declaration is a property, a colon, and a value: `color: red`
- Declarations are terminated by semicolons, letting several share one block
- All declarations inside a block apply to whatever the selector matches

**Example:**
```css
p {
  color: red;
  text-align: center;
}
```
`p` targets every paragraph, and the two declarations make their text red and centered.

---

## 4. CSS Selectors
**Definition:** A selector is the targeting half of a CSS rule: it names the HTML element or elements a declaration block should affect.

**Explanation:**
- Selectors come in five families: simple (name/id/class), combinator (relationship), pseudo-class (state), pseudo-element (part of an element), and attribute
- The **element selector** matches by tag name — `p` hits every paragraph
- The **id selector** is `#` plus the id value (`#para1`) and matches the one element with that id
- The **class selector** is `.` plus the class name (`.center`) and can match any number of elements
- A class can be narrowed to one tag with `p.center`, and an element may carry several classes (`class="center large"`)
- **Note:** an id or class name cannot start with a digit

**Example:**
```css
p { text-align: center; color: red; }
#para1 { text-align: center; color: red; }
.center { text-align: center; color: red; }
p.center { text-align: center; color: red; }
```
Identical declarations scoped four ways: by tag, by unique id, by class on any element, or by class restricted to one tag.

---

## 5. Grouping Selectors
**Definition:** The universal selector and the comma-separated grouping selector let one style reach many elements with less code.

**Explanation:**
- `*` matches every element on the page
- When several selectors need the same declarations, list them with commas before one block: `h1, h2, p`
- Grouping eliminates duplicated blocks and keeps a stylesheet smaller

| Selector | Example | Matches |
|---|---|---|
| `#id` | `#firstname` | the element with `id="firstname"` |
| `.class` | `.intro` | every element with `class="intro"` |
| `*` | `*` | all elements |
| `element` | `p` | all `<p>` elements |
| `element,element` | `div, p` | all `<div>` and `<p>` elements |

**Example:**
```css
h1, h2, p {
  text-align: center;
  color: red;
}
```
One block replaces three: headings and paragraphs all become centered red text.

---

## 6. CSS How To
**Definition:** CSS can be attached to a page in three ways — an external stylesheet, an internal `<style>` block, or inline `style` attributes.

**Explanation:**
- **External CSS** — a separate `.css` file referenced from `<head>` via `<link>`; one file restyles the whole site
- **Internal CSS** — rules inside a `<style>` element in `<head>`; suits a page with its own unique look
- **Inline CSS** — declarations in an element's `style` attribute; affects only that element
- An external file must end in `.css` and contain CSS only, never HTML tags
- **Note:** never split a number from its unit — write `margin-left: 20px`, not `20 px`

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="mystyle.css">
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```
Every page wanting those styles must carry this `<link>` reference in its head.

---

## 7. Add Internal CSS
**Definition:** Internal CSS keeps a page's rules in a `<style>` element inside the document head, for pages that need their own unique styling.

**Explanation:**
- The `<style>` tag lives in `<head>` and holds ordinary CSS rules
- Those rules affect only the page they are written in; other pages are untouched
- Use it for page-specific tweaks — reach for an external file when several pages should share a look

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
  body { background-color: linen; }
  h1 { color: maroon; margin-left: 40px; }
</style>
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```
The background and heading styling come from the document itself rather than a linked file.

---

## 8. Add Inline Style
**Definition:** Inline CSS writes declarations straight into an element's `style` attribute to style that one element only.

**Explanation:**
- Add `style="property: value; ..."` to any HTML element; the attribute accepts any CSS property
- Multiple declarations chain inside one attribute, separated by semicolons
- **Note:** inline styles mix content with presentation and give up most stylesheet benefits — use them sparingly

**Example:**
```html
<!DOCTYPE html>
<html>
<body>
  <h1 style="color:blue;text-align:center;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>
</body>
</html>
```
The heading renders blue and centered, the paragraph red — each rule locked to a single element.

---

## 9. Multiple Style Sheets
**Definition:** When several style sheets target the same selector, the browser merges them and the last one read wins on any conflicting property.

**Explanation:**
- Document order decides the outcome: a `<style>` block placed after a `<link>` overrides that file's matching rules (and the reverse also holds)
- All rules on a page combine into one virtual sheet by priority:
  1. inline `style` attributes (highest)
  2. external and internal style sheets in `<head>`
  3. browser defaults (lowest)
- An inline style therefore always beats both linked and internal rules

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="mystyle.css">
  <style>
    h1 { color: orange; }
  </style>
</head>
<body>
  <h1>A heading</h1>
</body>
</html>
```
The internal block comes last, so its `orange` wins over any `h1` color defined in `mystyle.css`.

---

## 10. CSS Comments
**Definition:** CSS comments are annotations for human readers; browsers ignore them completely when rendering a page.

**Explanation:**
- A comment opens with `/*` and closes with `*/`, and may span one line or several
- They can sit above a rule, inside a declaration block, or even between a property and its value
- Typical uses: explaining intent and temporarily disabling code while testing
- HTML comments use `<!-- ... -->`; neither kind shows up in the rendered page

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
  p {
    color: red; /* Set text color to red */
  }
</style>
</head>
<body>
  <!-- These paragraphs will be red -->
  <p>Hello World!</p>
</body>
</html>
```
The CSS comment documents the declaration and the HTML comment labels the markup; both stay invisible in the output.

---

## 11. CSS Errors
**Definition:** CSS fails silently — a malformed rule or value is simply dropped, so styles can go missing with no visible error message.

**Explanation:**
- **Missing semicolon:** `color: red` without `;` breaks the rule and can swallow the declaration after it
- **Unknown property:** a typo such as `colr: blue` is ignored, so the declaration does nothing
- **Invalid value:** a real property with an impossible value (e.g. `width: -100px`) is discarded
- **Unclosed brace:** a forgotten `}` can cause the whole rule to be skipped
- **Stray characters:** an extra colon like `color:: blue` breaks the declaration
- Prevention: syntax highlighting, a linter or validator, and testing in small increments

**Example:**
```css
.bad {
  color: red
  background-color: yellow;
}
```
Without the semicolon the parser reads `red background-color: yellow` as one value, so neither color is applied.

---

## 12. CSS Backgrounds
**Definition:** The background properties add color, images, and transparency behind an element's content.

**Explanation:**
- `background-color` paints the area behind the element; colors may be a name (`red`), HEX (`#ff0000`), or RGB (`rgb(255,0,0)`)
- The family also includes `background-image`, `background-repeat`, `background-attachment`, `background-position`, and the `background` shorthand
- `opacity` sets transparency from `0.0` (invisible) to `1.0` (solid)
- **Note:** `opacity` fades children too — to fade only the backdrop, use an alpha color like `rgba(0, 128, 0, 0.3)`
- Any element can carry a background: `body`, `h1`, `div`, `p`, …

**Example:**
```css
div {
  background-color: green;
  opacity: 0.3;
}
```
The box gets a green backdrop at 30% opacity, with its inner content faded along with it.

---

## 13. Background Image
**Definition:** `background-image` sets an image as the backdrop behind an element's content.

**Explanation:**
- The value is a URL: `url("paper.gif")`, quoted or unquoted
- By default the image tiles, repeating until the whole element is covered
- It can be applied to any element, so a single `<p>` can have its own backdrop
- **Note:** choose an image that will not fight with the text sitting on top of it

**Example:**
```css
body {
  background-image: url("bgdesert.jpg");
}
```
The page body shows the photo behind its content, repeated as needed to fill the area.

---

## 14. Background Repeat
**Definition:** `background-repeat` controls how a background image tiles, while `background-position` decides where it starts.

**Explanation:**
- Default behavior is `repeat` — the image copies both horizontally and vertically
- `repeat-x` tiles only across, `repeat-y` tiles only down, `no-repeat` shows a single copy
- A one-directional gradient usually looks wrong unless capped with `repeat-x` or `repeat-y`
- `background-position` anchors the image; the default is the top-left corner (`left top`)
- Pair `no-repeat` with a spot like `right top` so the image stays clear of the text

**Example:**
```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```
One copy of the image appears in the upper-right corner instead of tiling across the page.

---

## 15. Background Attachment
**Definition:** `background-attachment` decides whether a background image stays put while the page scrolls or travels with the content.

**Explanation:**
- `fixed` pins the image to the window, so scrolling moves content over a stationary backdrop
- `scroll` — the normal behavior — lets the image scroll along with everything else
- It combines with `background-image`, `background-repeat`, and `background-position`

**Example:**
```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```
The image remains in the top-right corner of the window while page content scrolls past it.

---

## 16. Background Shorthand
**Definition:** `background` is the shorthand property that sets every background property in one declaration.

**Explanation:**
- Instead of several `background-*` lines, the values are listed together in a single rule
- Leave a value out and that property falls back to its initial default
- Values can appear in any order — the browser tells them apart by type

**Example:**
```css
body {
  background: #ffffff url("img_tree.png") no-repeat right top;
}
```
One line stands in for separate `background-color`, `background-image`, `background-repeat`, and `background-position` declarations.

| Property | What it sets |
|---|---|
| `background` | all background properties at once |
| `background-attachment` | fixed vs. scrolling image |
| `background-clip` | painting area of the background |
| `background-color` | background color |
| `background-image` | background image |
| `background-origin` | positioning origin for the image |
| `background-position` | starting position of the image |
| `background-repeat` | image repetition |
| `background-size` | size of the image |

---

## 17. CSS Borders
**Definition:** The border properties draw a frame around an element, with control over its style, width, and color.

**Explanation:**
- `border-style` picks the pattern: `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`, `hidden`
- The 3D styles (`groove`, `ridge`, `inset`, `outset`) take their look from the border color
- `border-style` accepts one to four values — top, right, bottom, left
- **Note:** width and color do nothing unless `border-style` is set to something other than `none`

**Example:**
```css
p.dotted { border-style: dotted; }
p.double { border-style: double; }
p.mix { border-style: dotted dashed solid double; }
```
Each paragraph gets a different pattern, and the last rule gives every side its own style.

---

## 18. Border Width
**Definition:** `border-width` sets how thick an element's four borders are.

**Explanation:**
- Accepts a length (`5px`, `2pt`, `0.2em`) or one of the keywords `thin`, `medium`, `thick`
- Like the other border properties it takes one to four values: top, right, bottom, left
- With two values the first covers top/bottom and the second left/right; with three, left/right share the middle value
- A style is still required — pair it with `border-style` or nothing is drawn

**Example:**
```css
p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: 25px 10px 4px 35px; /* top right bottom left */
}
```
The first paragraph has a uniform 5px frame; the second varies the width on each side.

---

## 19. Border Color
**Definition:** `border-color` sets the color of an element's four borders.

**Explanation:**
- Colors may be a name (`red`), HEX (`#ff0000`), RGB (`rgb(255,0,0)`), HSL (`hsl(0, 100%, 50%)`), or `transparent`
- When `border-color` is omitted, the border falls back to the element's own text color
- One to four values work: `red green blue yellow` colors top, right, bottom, left in order

**Example:**
```css
p.one {
  border-style: solid;
  border-color: red green blue yellow; /* top right bottom left */
}
```
Each edge of the paragraph's frame gets its own color while the style stays solid all around.

---

## 20. Border Sides
**Definition:** Each border edge can be styled individually with `border-top-style`, `border-right-style`, `border-bottom-style`, and `border-left-style`, or handled at once through the `border-style` shorthand.

**Explanation:**
- One value — `border-style: dotted` — applies to all four sides
- Two values — `dotted solid` — top/bottom take the first, left/right the second
- Three values — `dotted solid double` — top, then left/right, then bottom
- Four values — `dotted solid double dashed` — clockwise: top, right, bottom, left
- The same counting rule also applies to `border-width` and `border-color`

**Example:**
```css
p {
  border-style: dotted solid;               /* top/bottom dotted, sides solid */
}

div {
  border-style: dotted solid double dashed; /* top right bottom left */
}
```
The shorthand reproduces what the four individual `border-*-style` properties would write out by hand.

---

## 21. Border Shorthand
**Definition:** `border` condenses width, style, and color into one declaration, and per-side versions like `border-left` do the same for a single edge.

**Explanation:**
- The shorthand covers `border-width`, `border-style`, and `border-color`
- A visible border needs a style, so always include a `border-style` value in the shorthand
- Side shorthands exist for every edge: `border-top`, `border-right`, `border-bottom`, `border-left`

**Example:**
```css
p {
  border: 5px solid red;
}

p.notice {
  border-left: 6px solid red;
}
```
The first rule frames all four sides; the second only thickens the left edge of `.notice`.

---

## 22. Rounded Borders
**Definition:** `border-radius` curves the corners of an element's border.

**Explanation:**
- Any length value works — small amounts gently soften the corners, larger ones approach pill or circle shapes
- It combines with the normal border declarations (`border`, `border-style`, `border-width`, `border-color`)

**Example:**
```css
p {
  border: 2px solid red;
  border-radius: 5px;
}
```
The paragraph's red frame has gently rounded corners instead of sharp 90-degree turns.

---

## 23. CSS Margins
**Definition:** Margins create space outside an element's border, setting the gap between it and its neighbors.

**Explanation:**
- Individual properties are `margin-top`, `margin-right`, `margin-bottom`, `margin-left`; `margin` is the shorthand
- Values may be `auto`, a length (`px`, `pt`, `cm`…), a `%` of the containing element's width, or `inherit`; negative values are allowed
- Shorthand counting: 4 values = top/right/bottom/left, 3 = top/sides/bottom, 2 = top-bottom + left-right, 1 = all sides
- `margin: auto` on an element with a set width centers it horizontally — leftover space splits between left and right
- `inherit` pulls the margin from the parent element

**Example:**
```css
div {
  width: 300px;
  margin: auto;
  border: 1px solid red;
}
```
The 300px box sits centered in its container because the free space becomes equal auto margins.

---

## 24. Margin Collapse
**Definition:** Margin collapse is the behavior where neighboring vertical margins merge into a single margin sized like the larger of the two.

**Explanation:**
- Only top and bottom margins collapse; left and right margins never do
- An `h1` with `margin-bottom: 50px` followed by an `h2` with `margin-top: 20px` leaves 50px between them, not 70px
- Two neighboring paragraphs with 30px top and bottom margins end up 30px apart instead of 60px

**Example:**
```css
h1 {
  margin-bottom: 50px;
}

h2 {
  margin-top: 20px;
}
```
Because the margins overlap, the visual gap between the heading and the subheading is 50px.

---

## 25. CSS Padding
**Definition:** Padding creates space between an element's content and its border — the inner counterpart to margin.

**Explanation:**
- Individual properties are `padding-top`, `padding-right`, `padding-bottom`, `padding-left`; `padding` is the shorthand
- Values accept a length (`px`, `pt`, `cm`…), a `%` of the containing element's width, or `inherit`
- **Note:** negative values are not allowed for padding
- Shorthand counting follows the margin pattern: 4/3/2/1 values map to top-right-bottom-left, top-sides-bottom, top-bottom + left-right, or one value for all sides

**Example:**
```css
div {
  padding: 25px 50px 75px 100px;
}
```
Top gets 25px, right 50px, bottom 75px, and left 100px of breathing room inside the border.

---

## 26. Padding and box-sizing
**Definition:** `box-sizing` controls whether an element's declared `width` and `height` measure only the content or also its padding and border.

**Explanation:**
- By default (`content-box`), `width` covers just the content area, so padding and border stack on top and widen the element
- A `width: 300px` div with `padding: 25px` therefore ends up 350px wide overall
- `border-box` folds padding and border into the declared size: the box stays 300px wide and the content area shrinks as padding grows

**Example:**
```css
div {
  width: 300px;
  padding: 25px;
  box-sizing: border-box;
}
```
The box holds a total width of 300px no matter how much padding is added.

---

## 27. CSS Height / Width
**Definition:** `height` and `width` set the size of an element's content area — the region inside its padding, border, and margin.

**Explanation:**
- Allowed values: `auto` (browser decides, the default), a length like `200px`, a `%` of the containing block, `initial`, or `inherit`
- By default these properties size only the content area; padding, borders, and margins are extra on top
- **Note:** a percentage resolves against the containing block, so `width: 50%` is half of the parent

**Example:**
```css
div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}
```
The box spans half its container's width, stands 200px tall, and carries a powder-blue backdrop.

---

## 28. Min / Max
**Definition:** The `min-width`, `max-width`, `min-height`, and `max-height` properties clamp an element's dimensions so it can never grow too large or shrink too small.

**Explanation:**
- `max-width` caps how wide an element may become; it accepts a length (px, cm, …), a percentage of the containing block, or `none` (the default, meaning no cap)
- A fixed `width` larger than the viewport forces a horizontal scrollbar — `max-width` avoids that, so narrow windows stay readable
- If both `width` and `max-width` are set on the same element and `width` wins the conflict, `max-width` still applies as the ceiling
- `min-width`/`max-height` work the same way for the other two dimensions

**Example:**
```css
.div1 {
  max-width: 500px;
  background-color: powderblue;
}

.div2 {
  width: 500px;
  background-color: powderblue;
}
```
Shrink the browser below 500px: `.div1` follows the window while `.div2` overflows it.

```css
.div1 {
  width: 100%;
  max-width: 900px;
  background-color: powderblue;
}
```
Full-width up to 900px, then the width stops growing — a common responsive container pattern.

---

## 29. CSS Box Model
**Definition:** The box model describes every HTML element as a stack of four layers — content, padding, border, and margin — that together determine how much space it occupies.

**Explanation:**
- **Content** is the inner area where text and images live; `width`/`height` apply only to this layer
- **Padding** clears transparent space inside the border, around the content
- **Border** wraps the padding and content; **margin** clears transparent space outside the border
- Total width = width + left/right padding + left/right border; total height = height + top/bottom padding + top/bottom border
- Margin counts toward the space a box takes on the page but is not part of the box's own size

**Example:**
```css
div {
  width: 320px;
  height: 50px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}
```
Rendered size: 320 + 20 + 10 = 350px wide and 50 + 20 + 10 = 80px tall.

```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```
One declaration per layer makes the content area, inner spacing, frame, and outer spacing all explicit.

---

## 30. CSS Outline
**Definition:** An outline is a line drawn around an element, outside its border, that makes the element stand out without affecting layout.

**Explanation:**
- Unlike a border, an outline sits outside the border edge and may overlap neighboring content
- Outlines are not part of the element's dimensions — total width and height never change because of one
- The outline properties are `outline-style`, `outline-color`, `outline-width`, `outline-offset`, and the `outline` shorthand
- `outline-style` accepts `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`, and `hidden`
- Critical: none of the other outline properties do anything until `outline-style` is set

**Example:**
```css
p.dotted { outline-style: dotted; }
p.dashed { outline-style: dashed; }
p.solid { outline-style: solid; }
p.double { outline-style: double; }
p.groove { outline-style: groove; }
p.ridge { outline-style: ridge; }
p.inset { outline-style: inset; }
p.outset { outline-style: outset; }
```
Each class shows one of the ten style values side by side on the same paragraph markup.

---

## 31. Outline Width
**Definition:** The `outline-width` property sets how thick an outline is drawn.

**Explanation:**
- Accepts the keywords `thin` (typically 1px), `medium` (typically 3px), and `thick` (typically 5px)
- An explicit length — px, pt, cm, em, etc. — is also allowed for exact control
- It only takes effect when `outline-style` is set to something other than `none`

**Example:**
```css
p {
  padding: 5px;
  outline-style: solid;
  outline-color: green;
}

p.ex1 { outline-width: thin; }
p.ex2 { outline-width: medium; }
p.ex3 { outline-width: thick; }
p.ex4 { outline-width: 8px; }
```
Shared style and color on the base rule let each variant differ only in width.

---

## 32. Outline Color
**Definition:** The `outline-color` property sets the color of an outline.

**Explanation:**
- Color can be given as a name (`red`), HEX (`#ff0000`), RGB (`rgb(255,0,0)`), or HSL (`hsl(0, 100%, 50%)`)
- The special value `invert` flips the underlying color, guaranteeing the outline stays visible on any background
- Like `outline-width`, color only shows once `outline-style` is declared

**Example:**
```css
p {
  border: 1px solid black;
  padding: 5px;
}

p.ex1 { outline-style: solid; outline-color: red; }
p.ex2 { outline-style: dotted; outline-color: blue; }
p.ex3 { outline-style: outset; outline-color: green; }
p.ex4 { outline-style: solid; outline-color: invert; }
```
Four paragraphs demonstrate named colors plus the automatic-contrast `invert` value.

```css
p.ex1 {
  outline-style: solid;
  outline-color: #ff0000; /* red */
}
```
The same red as a hexadecimal value; RGB and HSL work identically.

---

## 33. Outline Shorthand
**Definition:** `outline` is the shorthand for `outline-width`, `outline-style`, and `outline-color` in a single declaration.

**Explanation:**
- Supply one, two, or three of the values — their order does not matter
- `outline-style` is the only required component; without a style nothing renders
- Outlines follow rounded corners when `border-radius` is set on the element

**Example:**
```css
p.ex1 { outline: dashed; }
p.ex2 { outline: dotted red; }
p.ex3 { outline: 7px solid yellow; }
p.ex4 { outline: thick ridge pink; }
```
From a lone style keyword up to width + style + color in one line.

```css
p.ex1 {
  outline: dashed;
  border-radius: 8px;
}
```
The outline curves with the rounded border instead of staying rectangular.

---

## 34. Outline Offset
**Definition:** The `outline-offset` property inserts transparent space between an outline and the element's border edge.

**Explanation:**
- A positive value pushes the outline outward, away from the border
- A negative value pulls the outline inward, placing it inside the border edge
- The gap itself is transparent — it shows whatever background lies beneath the element

**Example:**
```css
p {
  margin: 30px;
  padding: 5px;
  background: yellow;
  border: 1px solid black;
  outline: 3px solid red;
  outline-offset: 15px;
}
```
The red outline floats 15px outside the border, with the yellow background ending at the border.

```css
p {
  margin: 30px;
  padding: 5px;
  background: yellow;
  border: 1px solid black;
  outline: 3px solid red;
  outline-offset: -5px;
}
```
A negative offset draws the outline 5px inside the border edge instead.

---

## 35. CSS Text
**Definition:** The `color` property sets the color of an element's text.

**Explanation:**
- Values may be a color name (`red`), a HEX value (`#ff0000`), or an RGB value (`rgb(255,0,0)`)
- The page-wide default text color is normally set once in the `body` selector
- Pair `color` with `background-color` to control both halves of the contrast
- High contrast between text and background is an accessibility requirement — low-contrast text is hard to read for people with vision problems

**Example:**
```css
body {
  color: blue;
}

h1 { color: green; }
h2 { color: red; }
```
The body rule gives every element a default, while headings override it.

```css
h1 {
  background-color: black;
  color: white;
}
```
Dark background with light text — the classic high-contrast pairing.

---

## 36. Text Alignment
**Definition:** Text alignment and direction properties control where lines of text sit horizontally and vertically, and which way the text reads.

**Explanation:**
- `text-align` takes `left`, `right`, `center`, or `justify`; justify stretches each line to equal width like a newspaper column (left/right default depends on writing direction)
- `text-align-last` styles only the final line: `auto`, `left`, `right`, `center`, `justify`, `start`, or `end`
- `vertical-align` positions an inline element against its line: `baseline` (default), a length/%, `sub`, `super`, `top`, `text-top`, `middle`, `bottom`, `text-bottom`
- `direction` sets writing direction (`ltr`/`rtl`) and is normally combined with `unicode-bidi` to support mixed-language text

**Example:**
```css
h1 { text-align: center; }
h2 { text-align: left; }
h3 { text-align: right; }

div { text-align: justify; }
```
Centered heading, flush-left and flush-right headings, and justified body copy.

```css
p.a { text-align-last: right; }
p.b { text-align-last: center; }
p.c { text-align-last: justify; }
```
The last line of a paragraph gets its own alignment, independent of the rest.

---

## 37. Text Decoration
**Definition:** The `text-decoration` family controls decorative lines drawn on text; it is a shorthand over line, color, style, and thickness.

**Explanation:**
- `text-decoration-line` sets the line: `none` (default), `underline`, `overline`, or `line-through`
- Multiple line values can combine, e.g. `overline underline` draws both
- `text-decoration-color` colors the line independently of the text
- Underlining text that isn't a link confuses readers — reserve it for links or use it deliberately

**Example:**
```css
h1 { text-decoration-line: overline; }
h2 { text-decoration-line: line-through; }
h3 { text-decoration-line: underline; }
p  { text-decoration-line: overline underline; }
```
Each heading gets a different decoration line; the paragraph stacks two at once.

```css
h1 {
  text-decoration-line: overline;
  text-decoration-color: red;
}
```
Line and color are separate properties, so the decoration can differ from the text color.

---

## 38. Text Decoration Styles
**Definition:** `text-decoration-style` and `text-decoration-thickness` shape how a decoration line looks, and `text-decoration` combines all four decoration properties.

**Explanation:**
- `text-decoration-style` accepts `solid` (default), `double`, `dotted`, `dashed`, and `wavy`
- `text-decoration-thickness` accepts `auto`, a length (px), or a percentage of the font size
- The `text-decoration` shorthand packs line (required), color, style, and thickness — in that conceptual grouping, e.g. `underline red double 5px`
- `text-decoration: none` is the standard way to remove the default underline from links

**Example:**
```css
h1 { text-decoration-line: underline; text-decoration-style: solid; }
h2 { text-decoration-line: underline; text-decoration-style: double; }
h3 { text-decoration-line: underline; text-decoration-style: dotted; }
p.ex1 { text-decoration-line: underline; text-decoration-style: dashed; }
p.ex2 { text-decoration-line: underline; text-decoration-style: wavy; }
```
Five underline styles from plain to wavy on otherwise identical text.

```css
p {
  text-decoration: underline red double 5px;
}
```
One declaration supplies line, color, style, and thickness together.

---

## 39. Text Transformation
**Definition:** The `text-transform` property controls the capitalization of text without changing the underlying HTML content.

**Explanation:**
- `none` leaves the text exactly as authored (the default)
- `capitalize` uppercases the first character of every word
- `uppercase` converts every character to uppercase; `lowercase` converts every character to lowercase
- The transformation is purely visual — screen readers and copy-paste see the original text

**Example:**
```css
p.uppercase { text-transform: uppercase; }
p.lowercase { text-transform: lowercase; }
p.capitalize { text-transform: capitalize; }
```
Three paragraphs render the same source text in three capitalization styles.

---

## 40. Text Spacing
**Definition:** CSS provides five properties that control spacing in and around text: `text-indent`, `letter-spacing`, `line-height`, `word-spacing`, and `white-space`.

**Explanation:**
- `text-indent` indents the first line of a text block; negative values pull it left
- `letter-spacing` sets the gap between characters; negative values tighten the text
- `line-height` sets the space between lines; negative values are not allowed — use unitless multipliers like `1.8` for scalable spacing
- `word-spacing` sets the gap between words; negative values are allowed
- `white-space` controls whitespace handling: `normal`, `nowrap`, `pre`, `pre-line`, `pre-wrap`

**Example:**
```css
p { text-indent: 50px; }
h1 { letter-spacing: 5px; }
h2 { letter-spacing: -2px; }
p.small { line-height: 0.8; }
p.big { line-height: 1.8; }
```
First-line indent, widened and tightened tracking, and loose versus tight leading.

```css
p.one { word-spacing: 10px; }
p.two { word-spacing: -2px; }
```
Extra space between words versus words packed closer together.

```css
p { white-space: nowrap; }
```
The paragraph refuses to wrap — useful for single-line labels that must stay on one line.

---

## 41. Text Shadow
**Definition:** The `text-shadow` property adds a shadow behind text.

**Explanation:**
- The minimum form sets only horizontal and vertical offsets: `2px 2px`
- A blur radius and a color can be appended, in either order after the offsets: `2px 2px 5px red`
- Multiple shadows are allowed as a comma-separated list — earlier shadows paint on top
- Chained colored shadows produce glow effects, e.g. a red-and-blue neon look

**Example:**
```css
h1 {
  color: white;
  text-shadow: 2px 2px 4px #000000;
}
```
White text with a soft dark shadow behind it for legibility.

```css
h1 {
  text-shadow: 0 0 3px #ff0000, 0 0 5px #0000ff;
}
```
Two offset-free blurred shadows combine into a red-and-blue neon glow.

---

## 42. CSS Fonts
**Definition:** Fonts define the character of a page, and the `font-family` property selects which font renders an element's text.

**Explanation:**
- `font-family` accepts a comma-separated fallback list — the browser uses the first font it can find and always ends with a generic family
- Multi-word font names must be quoted: `"Times New Roman"`
- The five generic families are serif, sans-serif, monospace, cursive, and fantasy
- Serif fonts have small strokes at letter edges (formal, elegant); sans-serif fonts have clean lines (modern, minimal); monospace gives every letter equal width; cursive imitates handwriting; fantasy is decorative
- On screens, sans-serif is generally considered easier to read than serif

**Example:**
```css
.p1 { font-family: "Times New Roman", Times, serif; }
.p2 { font-family: Arial, Helvetica, sans-serif; }
.p3 { font-family: "Lucida Console", "Courier New", monospace; }
```
Each list starts with a preferred font and ends with the matching generic family as the last resort.

---

## 43. Font Web Safe
**Definition:** Web safe fonts are fonts installed on virtually every browser and device, so they render consistently without extra downloads.

**Explanation:**
- No font is 100% guaranteed — always supply a fallback list ending in a generic family
- The best-known web safe fonts: Arial, Verdana, Tahoma, Trebuchet MS (sans-serif); Times New Roman, Georgia, Garamond (serif); Courier New (monospace); Brush Script MT (cursive)
- Arial is the most widely used font online and in print; Verdana stays readable at small sizes; Tahoma has tighter character spacing
- Times New Roman reads as professional/news; Georgia is elegant and readable across sizes (good for responsive design); Garamond is a classical book font
- Courier New is the standard monospace for code and screenplays; Trebuchet MS and Brush Script MT need care — mobile support and readability vary
- Always check rendering across browsers and devices before publishing

**Example:**
```css
p {
  font-family: Tahoma, Verdana, sans-serif;
}
```
Two specific fonts then a generic — if Tahoma is missing the browser tries Verdana, then its default sans-serif.

---

## 44. Font Fallbacks
**Definition:** Font fallback stacks are ready-made comma-separated lists that pair common fonts with their generic family so the browser always has somewhere to go.

**Explanation:**
- Each stack is organized under one of the five generic families
- The browser walks the list left to right, using the first installed font
- Ending with the generic family guarantees a sane default even on minimal systems

**Example:**
```css
/* serif */
h1 { font-family: "Times New Roman", Times, serif; }
h2 { font-family: Georgia, serif; }
h3 { font-family: Garamond, serif; }

/* sans-serif */
h4 { font-family: Arial, Helvetica, sans-serif; }
h5 { font-family: Tahoma, Verdana, sans-serif; }
h6 { font-family: "Trebuchet MS", Helvetica, sans-serif; }
```
Common serif and sans-serif stacks in the order they should appear.

```css
/* monospace, cursive, fantasy */
p.mono { font-family: "Courier New", Courier, monospace; }
p.cur { font-family: "Brush Script MT", cursive; }
p.fant { font-family: Copperplate, Papyrus, fantasy; }
```
The remaining three generic families with their usual first-choice fonts.

---

## 45. Font Style
**Definition:** `font-style`, `font-weight`, and `font-variant` control the slant, thickness, and capitalization treatment of text.

**Explanation:**
- `font-style`: `normal` (default), `italic`, or `oblique` — oblique is a slanted upright face, visually very close to italic
- `font-weight`: `normal` (default = 400), `bold` (= 700), `bolder`, `lighter`, or numeric `100`–`900` for fine-grained thickness
- `font-variant`: `normal` or `small-caps`, which renders lowercase letters as smaller uppercase letters
- Numeric weights only render fully if the font ships those weights; otherwise the browser approximates

**Example:**
```css
p.normal { font-style: normal; }
p.italic { font-style: italic; }
p.oblique { font-style: oblique; }
```
The same paragraph in normal, italic, and oblique slants.

```css
p.normal { font-weight: normal; }
p.light { font-weight: lighter; }
p.thick { font-weight: bold; }
p.thicker { font-weight: 900; }
```
Weights ranging from light through bold to the heaviest numeric cut.

---

## 46. Font Size
**Definition:** The `font-size` property sets the size of text, using either absolute or relative units.

**Explanation:**
- Absolute: `px` for fixed precise control, or keywords `xx-small` through `xx-large` with browser-defined sizes
- Relative: `em` (relative to the parent's font size), `rem` (relative to the root `<html>` size), `%` (relative to the parent), and `smaller`/`larger`
- `vw` equals 1% of the viewport width, so text scales with the browser window
- `px` doesn't respond to user font-size preferences; `em`/`rem` do — prefer them for scalable, accessible designs
- Never fake headings with font-size — use real `<h1>`–`<h6>` and `<p>` tags
- Browsers default `<html>` to 16px, so by default `1rem` = 16px

**Example:**
```css
h1 { font-size: 40px; }
h2 { font-size: 30px; }
p { font-size: 16px; }
```
Pixel sizes: exact, but the page won't rescale with user settings.

```css
body { font-size: 16px; /* base */ }
h1 { font-size: 2.5em; /* 2.5 × 16 = 40px */ }
p { font-size: 1em; /* 16px */ }
```
`em` multiplies against the parent, giving the same visual sizes while remaining user-adjustable.

```css
h1 { font-size: 2.5rem; /* 40px from the 16px root */ }
p { font-size: 5vw; /* 5% of viewport width */ }
```
`rem` always references `<html>` regardless of nesting; `vw` ties text directly to window width.

---

## 47. Font Google
**Definition:** Google Fonts is a free library of 1000+ web fonts loaded through a stylesheet link, usable anywhere standard fonts are.

**Explanation:**
- Add `<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">` in `<head>`, then reference the font in `font-family`
- Always append a generic family (serif/sans-serif) as the final fallback
- Multiple fonts go in one request separated by `|` (pipe), but extra fonts slow page loads — request only what you use
- Fonts can be styled normally with any CSS: size, shadow, color, etc.
- Font effects (fire, neon, outline, emboss, …) are enabled with `&effect=…` in the URL and applied through classes named `font-effect-<name>`

**Example:**
```html
<head>
<link rel="stylesheet"
  href="https://fonts.googleapis.com/css?family=Sofia">
<style>
body {
  font-family: "Sofia", sans-serif;
  font-size: 30px;
  text-shadow: 3px 3px 3px #ababab;
}
</style>
</head>
```
Load Sofia once, then style it like any other font — here with a soft drop shadow.

```html
<link rel="stylesheet"
  href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
```
One pipe-separated request pulls three fonts; each is then used via its own `font-family` rule.

---

## 48. Font Pairings
**Definition:** Font pairing is the craft of combining typefaces so they complement each other and establish a clear visual hierarchy.

**Explanation:**
- **Complement** — pair fonts that harmonize: neither too similar nor too different
- **Superfamilies** — fonts designed to work together (e.g. Lucida Sans, Lucida Serif, Lucida Typewriter) are safe combinations
- **Contrast** — near-identical fonts clash; contrasting pairs (serif with sans-serif) bring out each font's strengths
- **One boss** — a single font should lead the hierarchy, emphasized through size, weight, and color
- Classic web safe pairings: Georgia + Verdana, Helvetica + Garamond
- Popular Google pairings: Merriweather + Open Sans, Ubuntu + Lora, Abril Fatface + Poppins, Cinzel + Fauna One, Fjalla One + Libre Baskerville, Space Mono + Muli, Spectral + Rubik, Oswald + Noto Sans

**Example:**
```css
body {
  background-color: black;
  font-family: Verdana, sans-serif;
  font-size: 16px;
  color: gray;
}

h1 {
  font-family: Georgia, serif;
  font-size: 60px;
  color: white;
}
```
Sans-serif body text under a large serif heading — contrast plus one clear boss.

---

## 49. Font Shorthand
**Definition:** The `font` property sets all individual font properties in one declaration.

**Explanation:**
- It covers `font-style`, `font-variant`, `font-weight`, `font-stretch`, `font-size`, `line-height`, and `font-family`
- `font-size` and `font-family` are required; any omitted values fall back to their defaults
- If present, `font-style`, `font-variant`, and `font-weight` must come before `font-size`
- `line-height` immediately follows `font-size` after a `/`, written as `15px/30px`
- `font-family` must always be last

**Example:**
```css
p.a { font: 20px Arial, sans-serif; }
p.b { font: italic bold 16px Arial, sans-serif; }
p.c { font: italic small-caps bold 15px/30px Georgia, serif; }
```
From minimal size + family up to style, variant, weight, size/leading, and family in a single line.

---

## 50. CSS Links
**Definition:** Links can be styled like any element, and additionally per link state — unvisited, visited, hover, and active.

**Explanation:**
- Any text property works on `a`: `color`, `background-color`, `text-decoration`, `font-size`, `font-weight`, `font-family`
- The four states are `:link` (normal unvisited), `:visited` (already visited), `:hover` (mouse over), `:active` (being clicked)
- State order matters: `:hover` must follow `:link`/`:visited`, and `:active` must follow `:hover` — the usual mnemonic is LVHA (link, visited, hover, active)
- `text-decoration` is most often used to strip the default underline and re-add it on hover
- `background-color` per state gives links a button-like highlight

**Example:**
```css
a:link { color: red; }
a:visited { color: green; }
a:hover { color: hotpink; }
a:active { color: blue; }
```
Four colors for the four states, declared in LVHA order so no rule is shadowed.

```css
a:link, a:visited { text-decoration: none; }
a:hover, a:active { text-decoration: underline; }
```
Plain links lose their underline; hovering or pressing brings it back as feedback.

---

## 51. Link Buttons
**Definition:** With padding, background, and no underline, an ordinary `<a>` can be styled to look and behave like a button.

**Explanation:**
- Group `a:link, a:visited` for the resting style and `a:hover, a:active` for the interactive style
- `display: inline-block` lets padding and centering behave like a real block button
- `text-align: center` plus `text-decoration: none` cleans up the label
- Swapping `background-color` (and often `color`) on hover/active gives click feedback

**Example:**
```css
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 14px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
```
A red button-styled link that brightens while hovered or pressed. An outlined variant is the same pattern with `border: 2px solid green` at rest and inverted colors on hover.

---

## 52. CSS Lists
**Definition:** Lists are styled through the `list-style` family, which controls the marker type, image, and position of `<ul>` and `<ol>` items.

**Explanation:**
- HTML has unordered lists (`<ul>`, bullets) and ordered lists (`<ol>`, numbers/letters)
- `list-style-type` sets the marker: `disc`/`circle`/`square` for unordered; `decimal`/`upper-roman`/`lower-roman`/`lower-alpha` for ordered
- `list-style-image` replaces the marker with an image — always keep a `list-style-type` as backup when the image may fail
- `list-style-position`: `outside` (default, marker hangs outside the text) or `inside` (marker becomes part of the line)
- `list-style: none` removes markers; also reset the default `margin: 0; padding: 0` on the list element
- The `list-style` shorthand sets type, position, and image in that order; missing values take their defaults

**Example:**
```css
ul.a { list-style-type: circle; }
ul.b { list-style-type: disc; }
ul.c { list-style-type: square; }
ol.d { list-style-type: upper-roman; }
ol.e { list-style-type: lower-alpha; }
ol.f { list-style-type: decimal; }
```
Marker types split by list kind — shapes for `ul`, numbering styles for `ol`.

```css
ul {
  list-style-image: url('sqpurple.gif');
  list-style-type: square;
}
```
Image marker with a square fallback if the image can't load — also valid as one shorthand: `list-style: square inside url("sqpurple.gif")`. Styling the `<ul>`/`<ol>` affects the whole list; styling `<li>` targets individual items.

---

## 53. CSS Tables
**Definition:** Tables gain structure and readability through borders, collapsed border spacing, cell padding, and controlled gaps between cells.

**Explanation:**
- The `border` shorthand sets width, style (required), and color — apply it to `table, th, td` for full grid lines
- Double borders appear by default because each cell draws its own; `border-collapse: collapse` merges them into single lines (`separate` is the default)
- `padding` on `<th>` and `<td>` controls the space between cell borders and content
- `border-spacing` sets the distance between adjacent cell borders — only works while `border-collapse` is `separate`
- Putting `border` only on `<table>` yields a single outside frame with no internal lines

**Example:**
```css
table, th, td {
  border: 1px solid;
}
```
A grid around every cell — note the doubled lines where borders meet.

```css
table {
  border-collapse: collapse;
}

th, td {
  padding: 10px;
}
```
Collapsed single borders plus comfortable cell padding — the standard table cleanup. With `border-collapse: separate`, `border-spacing: 15px` puts a 15px gutter between cells.

---

## 54. Table Size
**Definition:** Table width and height are set with the same `width`/`height` properties used elsewhere, accepting percentages, fixed lengths, or `auto`.

**Explanation:**
- Width may be a percent (`width: 100%` for full-width, `50%` for half), a fixed length (`500px`), or `auto` to let the browser size the table from its content
- Height follows the same three options and is often applied to `<th>` cells for consistent header rows
- Percent widths make tables responsive; fixed px widths keep them rigid; `auto` is the natural content-driven default

**Example:**
```css
table {
  width: 100%;
}
```
The table spans its container edge to edge.

```css
table {
  width: 500px;
}
```
A fixed 500px table regardless of content or container.

```css
th {
  height: 70px;
}
```
Header cells get a uniform 70px height while data rows stay content-sized.

---

## 55. Table Alignment
**Definition:** Table alignment controls how cell contents sit inside `<th>` and `<td>` boxes — horizontally through `text-align` and vertically through `vertical-align`.

**Explanation:**
- `text-align` accepts `left`, `right`, or `center` and moves the text within a cell
- Out of the box, header cells (`<th>`) are centered while data cells (`<td>`) are left-aligned
- `vertical-align` parks cell content at the `top`, `middle` (the default), or `bottom` of the cell
- Vertical placement is easiest to see once a row has extra height (for example `height: 50px`)

**Example:**
```css
th {
  text-align: left;
}

td {
  text-align: center;
  height: 50px;
  vertical-align: bottom;
}
```

Headers shift to the left edge, while each data cell centers its text and pins it to the bottom of a taller row.

---

## 56. Table Styling
**Definition:** Table styling covers the everyday touches that make a data table readable — cell padding, row separators, hover highlights, striped rows, and header colors.

**Explanation:**
- `padding` on `th, td` adds breathing room between the cell borders and their text
- `border-bottom` on cells draws thin horizontal dividers between rows
- `tr:hover` tints an entire row when the pointer moves over it
- `tr:nth-child(even)` produces the classic zebra stripe by shading alternate rows
- A colored `background-color` together with `color: white` makes header cells stand out

**Example:**
```css
th, td {
  padding: 10px;
  border-bottom: 1px solid #ddd;
}

tr:hover {
  background-color: coral;
}

tr:nth-child(even) {
  background-color: #f2f2f2;
}
```

One small block of rules adds padding, row dividers, striping, and a hover tint to the same table.

---

## 57. Responsive Tables
**Definition:** A responsive table stays usable on narrow screens by scrolling sideways inside a wrapper instead of overflowing the page.

**Explanation:**
- Wrap the `<table>` in a `<div>` container
- Give that container `overflow-x: auto`, so a horizontal scrollbar appears only when the table is wider than the available space
- Wide screens look unchanged; small screens let the user scroll through the table itself
- Related table properties worth knowing: `border-collapse`, `border-spacing`, `caption-side`, `empty-cells`, `table-layout`

**Example:**
```html
<style>
  .tablecontainer {
    overflow-x: auto;
  }
</style>

<div class="tablecontainer">
  <table>
    <tr><th>Name</th><th>Points</th></tr>
    <tr><td>Jill</td><td>50</td></tr>
  </table>
</div>
```

The wrapper keeps its own width while the wide table scrolls inside it.

---

## 58. CSS Display
**Definition:** The `display` property decides how an element is rendered — as a block-level box, an inline box, a layout container, or no box at all.

**Explanation:**
- Every element carries a default display value, most often `block` or `inline`
- Block-level elements (`<div>`, `<h1>`–`<h6>`, `<p>`, `<form>`, `<header>`, `<footer>`, `<section>`) always start on a new line and span the full available width; inline elements (`<span>`, `<a>`, `<img>`) flow with the text and take only the width they need
- Changing `display` alters rendering only, not the element's actual type: an inline element switched to `block` still must not contain block children

| Value | How the element renders |
|---|---|
| `inline` | Flows inline like surrounding text |
| `block` | Block-level box starting on its own line |
| `contents` | The container's box disappears and its children join the parent's parent |
| `flex` | Block-level flex container |
| `grid` | Block-level grid container |
| `inline-block` | Placed inline, yet accepts `width`, `height`, padding, and vertical margins |
| `none` | Hidden, taking no space at all |

**Example:**
```css
li {
  display: inline;
}

span {
  display: block;
}
```

---

## 59. Hiding Elements
**Definition:** CSS hides content in two distinct ways: `display: none` removes the element from layout, while `visibility: hidden` keeps its space but paints nothing.

**Explanation:**
- `display: none` pulls the element out of the document flow completely — the page reflows as if it never existed
- `visibility: hidden` blanks the pixels but the element still reserves its original space, leaving a gap
- JavaScript toggles usually rely on `display: none`, because flipping the value back to `block` restores the element without recreating it
- Reach for `visibility: hidden` when the surrounding layout must not jump

**Example:**
```css
.hidden {
  display: none;
}

.invisible {
  visibility: hidden;
}
```

The first rule collapses the layout; the second leaves an empty hole exactly where the element sits.

---

## 60. CSS Max-width
**Definition:** `max-width` caps how wide an element may grow — it may be narrower than the value, but never wider.

**Explanation:**
- A hard `width` (say `600px`) breaks on screens smaller than that: content gets clipped and the page gains a horizontal scrollbar
- `max-width` lets the element shrink together with the viewport, which keeps centered text readable at any size
- Both work alongside `margin: auto` to keep the element horizontally centered
- This is a lightweight recipe for responsive, readable containers

**Example:**
```css
div.ex1 {
  width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}

div.ex2 {
  max-width: 500px;
  margin: auto;
  border: 3px solid #73AD21;
}
```

Shrink the window below 500px: the first box overflows, the second one follows the window down.

---

## 61. CSS Position
**Definition:** The `position` property selects how an element is placed — following the normal flow, shifted away from it, or pinned to a reference box.

**Explanation:**
- `static` (the default) lays the element out in normal flow and ignores `top`, `right`, `bottom`, and `left`
- `relative` keeps the element in the flow but offsets it from its normal spot; the original gap is not reclaimed, so neighboring content does not move
- `fixed` locks to the viewport, `absolute` anchors to the nearest positioned ancestor, and `sticky` flips between relative and fixed while scrolling
- Once a position type is chosen, `top`, `right`, `bottom`, and `left` move the element to its final spot

**Example:**
```css
div.static {
  position: static;
  border: 3px solid #73AD21;
}

div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

The static box stays put; the relative box is nudged 30px to the right without disturbing anything around it.

---

## 62. Fixed and Absolute Positioning
**Definition:** `position: fixed` pins an element to the browser window, while `position: absolute` pins it to its nearest positioned ancestor.

**Explanation:**
- A fixed element keeps its screen location while the page scrolls and leaves no gap where it would have been in the flow
- Absolute placement measures `top`/`right`/`bottom`/`left` against the closest ancestor whose `position` is not `static`; with no such ancestor, the document body becomes the reference and the element scrolls with the page
- Absolutely positioned elements leave normal flow, so they can overlap other content
- Typical uses: corner badges and floating panels (fixed), labels layered over an image (absolute)

**Example:**
```css
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
}

div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
}
```

A fixed box stays glued to the window corner; the absolute box is placed inside its nearest positioned ancestor.

---

## 63. Sticky Positioning
**Definition:** `position: sticky` lets an element behave like a normal relative box until it hits a scroll threshold, after which it pins in place as if it were fixed.

**Explanation:**
- Sticky needs at least one of `top`, `right`, `bottom`, or `left` — without an offset it never sticks
- With `top: 0` the element scrolls normally until it reaches the top edge, then holds there
- Because it occupies space until it sticks, it does not cover content the way `fixed` can
- Everyday jobs: navigation bars that pin to the top, sidebars that stay in view, and headers of long tables

| Trait | `sticky` | `fixed` |
|---|---|---|
| Starting state | Behaves like `relative` | Always pinned to the viewport |
| Space in flow | Occupies space until it sticks | Takes no space |
| Container limit | Stops at the parent's edge | Ignores containers |

**Example:**
```css
div.sticky {
  position: sticky;
  top: 0;
  background-color: green;
  border: 2px solid #4CAF50;
}
```

The bar scrolls along with the page until it reaches the top, then holds position while the rest of the content moves past.

---

## 64. Position Offsets
**Definition:** The `top`, `right`, `bottom`, and `left` properties shift a positioned element away from its reference edges by a given amount.

**Explanation:**
- They do nothing on ordinary elements — the element's `position` must be `relative`, `absolute`, `fixed`, or `sticky`
- Each property measures from the matching edge of the element's positioning reference
- Together they pin down the element's final location after a position type has been chosen
- This combination is what makes overlays such as text or badges on an image possible

**Example:**
```css
.positioned {
  position: absolute;
  top: 80px;
  right: 0;
}
```

The box is pulled out of flow, dropped 80px from the top and flush against the right edge of its positioned ancestor.

---

## 65. CSS Z-index
**Definition:** `z-index` sets the stack order of positioned elements — which overlapping box lands in front and which sinks behind.

**Explanation:**
- Only positioned elements take part: those with `position` set to `absolute`, `relative`, `fixed`, or `sticky`, plus direct flex items
- A higher `z-index` renders above a lower one, and values may be negative — for example `z-index: -1` on an absolutely positioned image drops it behind ordinary text
- With no `z-index` at all, overlapping positioned elements stack in HTML source order, so the last one defined wins

**Example:**
```css
.container { position: relative; }
.black-box { position: relative; z-index: 1; }
.gray-box { position: absolute; z-index: 3; }
.green-box { position: absolute; z-index: 2; }
```

Declaration order no longer decides the stack — the `z-index` numbers do.

---

## 66. CSS Overflow
**Definition:** The `overflow` property decides what happens when an element's content is too large for its box — clip it, scroll it, or let it spill out.

**Explanation:**
- `visible` (default): content renders outside the box with no clipping
- `hidden`: the excess is cut off and becomes unreachable
- `scroll`: scrollbars are always displayed, whether or not anything overflows
- `auto`: scrollbars show up only when they are needed — the usual choice for scrollable panels
- The related `overflow-x` and `overflow-y` properties handle each direction separately

**Example:**
```css
div {
  width: 200px;
  height: 65px;
  background-color: coral;
  overflow: auto;
}
```

Content that no longer fits the 200 by 65 box gets a scrollbar instead of escaping onto the page.

---

## 67. Overflow X and Y
**Definition:** `overflow-x` and `overflow-y` set overflow behavior independently for the horizontal and vertical axes.

**Explanation:**
- `overflow-x` governs the left/right edges of the content, `overflow-y` the top/bottom edges
- Each accepts the same values as `overflow`: `visible`, `hidden`, `scroll`, `auto`
- Typical pairings: `overflow-x: auto` for wide tables or long code lines, `overflow-y: scroll` for chat-style panels that must always scroll vertically
- Mixing them lets you clip one direction while scrolling the other

**Example:**
```css
div {
  overflow-x: hidden;
  overflow-y: scroll;
}
```

Horizontal spill is clipped away while a permanent vertical scrollbar keeps the content reachable.

---

## 68. CSS Float
**Definition:** `float` pushes an element toward the left or right edge of its container so that surrounding text and inline content wrap around it.

**Explanation:**
- Values are `left`, `right`, `none` (default — the element stays where it occurs), and `inherit`
- Floated images are the classic way to let a paragraph flow around a picture
- Floated block elements line up next to one another instead of each starting a fresh line
- Once floated, an element leaves normal flow, which is why containers around floats need clearfix handling (covered next)

**Example:**
```css
div {
  float: left;
  padding: 15px;
}

.div1 { background: red; }
.div2 { background: yellow; }
.div3 { background: green; }
```

Three block `<div>`s, which normally stack vertically, sit side by side in one row.

---

## 69. Clear and Clearfix
**Definition:** `clear` controls whether an element may sit beside floating content, and the clearfix hack makes a container grow tall enough to enclose its floats.

**Explanation:**
- `clear` accepts `none` (default), `left`, `right`, `both`, and `inherit`; setting it drops the element below floats on the chosen side
- Without `clear`, content wraps around a float; with it, the element starts underneath
- When a float is taller than its container the float spills out — the clearfix fixes this by appending a cleared `::after` pseudo-element to the container
- In the hack, `content: ""` makes the pseudo-element exist, `clear: both` pushes it below all floats, and `display: table` creates a new block formatting context that traps them

**Example:**
```css
.div1 {
  float: left;
}

.div2 {
  clear: left;
}

.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
```

Give the `clearfix` class to any container holding floated children and its box expands to wrap them.

---

## 70. display: inline-block
**Definition:** `display: inline-block` places an element inline — on the same line as its neighbors — while still letting it behave like a block box for sizing.

**Explanation:**
- Like inline elements, these boxes share a line with other inline or inline-block content
- Unlike inline elements, they honor `width`, `height`, `margin-top`, and `margin-bottom`
- Contrast the three modes: `inline` ignores explicit size, `block` forces a new line, `inline-block` offers both
- The everyday application is converting a vertical `<ul>` into a horizontal navigation bar

**Example:**
```css
nav {
  background-color: lightgray;
  list-style-type: none;
  padding: 0;
  margin: 0;
}

nav li {
  display: inline-block;
  font-size: 18px;
  padding: 15px;
}
```

Menu items share a single row, and their padding now works vertically as well as horizontally.

---

## 71. CSS Align
**Definition:** Centering places an element in the middle of its container — horizontally, vertically, or both — using whichever layout tool suits the element type.

**Explanation:**
- Horizontal options: `margin: auto` for block elements, `text-align: center` for text, and `float` or `position` for edge alignment
- Vertical options: Flexbox with `align-items: center`, Grid with `place-items: center`, or `position` plus `transform` when the element's size is unknown
- Flexbox is the modern default for centering on both axes at once

**Example:**
```css
.center {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

Both alignment properties on one flex container center its children horizontally and vertically.

---

## 72. Horizontal Align
**Definition:** Horizontal alignment lines elements up left-to-right, with a different technique for blocks, text, images, and boxes pushed to an edge.

**Explanation:**
- Center a block with `margin: auto` plus an explicit `width` — without a width (or with `width: 100%`) the auto margins accomplish nothing
- Center text inside a block with `text-align: center`
- Center an image: it is inline by default, so first set `display: block`, then `margin-left: auto; margin-right: auto`
- Push a box to an edge with `position: absolute; right: 0;` (leaves the flow) or `float: right` (stays in the flow)

**Example:**
```css
.center {
  margin: auto;
  width: 50%;
  border: 3px solid green;
  padding: 10px;
}

img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
}
```

The block settles in the middle of its parent, and the image does the same once it stops behaving like inline text.

---

## 73. Vertical Align
**Definition:** Vertical alignment centers content top-to-bottom inside its container — an area where the modern layout modules do the heavy lifting.

**Explanation:**
- Flexbox: `display: flex` with `justify-content: center` (main axis) and `align-items: center` (cross axis); give the container a height so there is something to center within
- Grid: `display: grid` with `place-items: center` handles both axes in one declaration
- Unknown dimensions: `position: absolute` at `top: 50%; left: 50%` plus `transform: translate(-50%, -50%)` pulls the element back by half its own size

**Example:**
```css
.flexbox {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
}

.grid {
  display: grid;
  place-items: center;
}
```

Both containers pull their child to the middle — the flex box uses two alignment properties, the grid box uses one.

---

## 74. CSS Combinators
**Definition:** A combinator is the operator placed between two selectors that expresses how the matched elements are related inside the document tree.

**Explanation:**
- Descendant (space): `div p` — every `<p>` at any depth inside a `<div>`
- Child (`>`): `div > p` — only `<p>` elements that are direct children
- Next sibling (`+`): `div + p` — the single `<p>` immediately after a `<div>`, sharing the same parent
- Subsequent sibling (`~`): `div ~ p` — all `<p>` siblings that follow a `<div>` under the same parent

**Example:**
```css
div p { background-color: yellow; }
div > p { background-color: yellow; }
div + p { background-color: yellow; }
div ~ p { background-color: yellow; }
```

Each line targets a different relationship, so identical markup can be styled at four levels of closeness.

---

## 75. CSS Pseudo-classes
**Definition:** A pseudo-class is a keyword appended to a selector that picks elements by state or position rather than by a class written in the HTML.

**Explanation:**
- Syntax: a single colon joins selector and name — `selector:pseudo-class-name { ... }`
- Typical jobs: react to mouse-over, differentiate visited from unvisited links, highlight focused inputs, style form validity states, target the first child of a parent
- Interactive pseudo-classes (`:hover`, `:focus`, `:active`, `:link`, `:visited`) depend on what the user is doing
- Structural pseudo-classes (`:first-child`, `:last-child`, `:nth-child(n)`, `:lang()`) depend on where the element sits in the document tree

**Example:**
```css
a:hover {
  color: red;
}

p:first-child {
  font-weight: bold;
}
```

The first rule applies only while the pointer rests on a link; the second only to a paragraph that opens its parent.

---

## 76. Interactive Pseudo-classes
**Definition:** Interactive pseudo-classes style elements according to the user's current action — hovering, focusing, activating, or browsing links.

**Explanation:**
- The core set: `:hover` (pointer over the element), `:focus` (element ready for input), `:active` (being clicked or pressed)
- Links typically use the full sequence `:link` → `:visited` → `:hover` → `:active`
- Order matters in the stylesheet: `a:hover` must come after `a:link` and `a:visited`, and `a:active` must come after `a:hover`, otherwise the earlier rule wins
- Capitalization of pseudo-class names is irrelevant, and they combine with ordinary classes (`a.highlight:hover`)
- Bonus pattern: hide a tooltip with `display: none`, reveal it with `div:hover p { display: block; }`

**Example:**
```css
a:link { color: #FF0000; }
a:visited { color: #00FF00; }
a:hover { color: #FF00FF; }
a:active { color: #0000FF; }

input:focus {
  background-color: yellow;
}
```

The four link rules must stay in that exact order; the input rule tints a field while it has focus.

---

## 77. Structural Pseudo-classes
**Definition:** Structural pseudo-classes select elements by their position among siblings, so positional patterns can be styled without extra classes.

**Explanation:**
- `:first-child` matches an element that is the first child of its parent; placement inside the selector changes the meaning: `p em:first-child` picks the first `<em>` inside a `<p>`, while `p:first-child em` picks `<em>`s inside paragraphs that are themselves first children
- `:lang(value)` matches elements whose `lang` attribute equals that value, handy for language-specific quotation marks
- Further options: `:last-child`, `:nth-child(n)`, `:nth-last-child(n)`, `:only-child`, `:first-of-type`, `:last-of-type`

**Example:**
```css
p:first-child {
  color: blue;
}

p em:first-child {
  color: blue;
}

q:lang(no) {
  quotes: "~" "~";
}
```

The first two rules differ only in which element the structural condition binds to; the third recolors quotes marked `lang="no"`.

---

## 78. CSS Pseudo-elements
**Definition:** A pseudo-element is a keyword added to a selector that styles one specific fragment of an element — its first letter, generated content, or a selection highlight — as though it were a separate element.

**Explanation:**
- Syntax uses a double colon: `selector::pseudo-element-name { ... }`
- Text group: `::first-line` and `::first-letter` target a line or character of text
- Content group: `::before` and `::after` insert generated content, `::marker` styles list bullets, `::selection` styles highlighted text, `::backdrop` styles the layer behind a dialog

**Example:**
```css
p::first-letter {
  color: red;
}

h3::before {
  content: "Note: ";
}
```

One rule restyles a paragraph's opening character, the other injects text ahead of a heading's own content.

---

## 79. Text Pseudo-elements
**Definition:** The text pseudo-elements `::first-line` and `::first-letter` restyle only the opening line or the opening character of a text block.

**Explanation:**
- Both may only be applied to block-level elements
- They can be scoped with an HTML class, such as `p.intro::first-letter`
- Several can be combined: one rule for the letter, another for the line, while the rest of the paragraph keeps its normal styling
- Frequent treatments: oversized colored first letters (drop caps) and small-caps lead-ins

**Example:**
```css
p::first-letter {
  color: red;
  font-size: xx-large;
}

p::first-line {
  color: blue;
  font-variant: small-caps;
}
```

The opening letter turns red and oversized while the remainder of the first line renders as blue small-caps.

---

## 80. Content Pseudo-elements
**Definition:** Content pseudo-elements insert or style generated material: `::before` and `::after` add content around an element's own text, while `::marker`, `::selection`, and `::backdrop` target specific interface fragments.

**Explanation:**
- `::before` and `::after` require the `content` property, which holds the text or `url(...)` image to insert
- The inserted material becomes part of the element's box, appearing at its start or at its end
- `::marker` recolors or resizes the bullet or number of a list item
- `::selection` styles whichever portion of text the user has highlighted
- `::backdrop` paints the layer behind an open `<dialog>` or popover

**Example:**
```css
h3::before {
  content: url(smiley.gif);
}

::marker {
  color: red;
  font-size: 23px;
}

::selection {
  color: red;
  background: yellow;
}
```

The heading gains a leading image, list markers turn red and large, and selected text appears as red on yellow.

---

## 81. CSS Opacity
**Definition:** The `opacity` property sets how transparent an element is, ranging from `0.0` (completely see-through) to `1.0` (completely solid, the default).

**Explanation:**
- Middle values such as `0.5` make the whole element — background and content together — half transparent
- Opacity applies to children as well, so text sitting inside a translucent box becomes hard to read
- To fade only the background, switch to an RGBA background color: `rgba(red, green, blue, alpha)`, where `alpha` runs from 0.0 to 1.0
- Pairing opacity with `:hover` is a common interaction — dim an image at rest and brighten it on mouse-over, or the reverse

**Example:**
```css
img {
  opacity: 0.5;
}

img:hover {
  opacity: 1.0;
}

.transbox {
  background: rgba(4, 170, 109, 0.3);
}
```

The image sits at half opacity until hovered, and the box shows its background at 30% while keeping its text fully opaque.

---

## 82. CSS Navigation Bars
**Definition:** A navigation bar is the menu block — usually across the top or down the side of a page — that lets visitors jump between sections of a site.

**Explanation:**
- Navbars are almost always built as an HTML list (`<ul>` with `<li>` items), each item holding one link (`<a>`)
- CSS then removes the bullets, margins, and default padding so the list looks like a menu
- The same stripped-down list is the starting point for both vertical and horizontal navbars
- It typically sits at the top or along the side of the page

**Example:**
```css
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
```

This reset block is the shared base: no bullet points, no browser default spacing — ready to be laid out vertically or horizontally.

---

## 83. Vertical Navbar
**Definition:** A vertical navbar stacks its links one above the other, usually hugging the left or right edge of the page.

**Explanation:**
- Built from the base `<ul>` / `<li>` / `<a>` structure with a fixed width and background; `display: block` on the links makes the whole row clickable (not just the text) and allows padding
- `:hover` swaps the link and background colors to show which item is under the pointer
- An `.active` class highlights the link for the current page; `border-bottom` on each `li` (skipping the last via `:last-child`) draws internal dividers

**Example:**
```css
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  width: 200px;
  background-color: #f1f1f1;
}
li a {
  display: block;
  color: black;
  padding: 8px 16px;
  text-decoration: none;
}
li a:hover {
  background-color: #555555;
  color: white;
}
```

---

## 84. Horizontal Navbar
**Definition:** A horizontal navbar places its links side by side in a bar, most commonly across the top of a page.

**Explanation:**
- Two layout approaches: float the `<li>` elements (`float: left` plus `overflow: hidden` on the `<ul>`), or the modern `display: flex` on the `<ul>` — `justify-content: center` centers the flex version in one line
- `position: fixed` with `top: 0` (or `bottom: 0`) pins the bar in place while the page scrolls; `position: sticky` plus `top: 0` keeps the bar in flow until it reaches the top, then it sticks (sticky needs at least one of `top`/`right`/`bottom`/`left` to work)
- `border-right` on all `li` except the last creates dividers between links

**Example:**
```css
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
  background-color: #333333;
}
ul li a {
  display: block;
  color: white;
  padding: 14px 16px;
  text-decoration: none;
}
ul li a:hover {
  background-color: #111111;
}
```

Flexbox lays the links out in a row on a dark bar; padding gives each link a comfortable hit area.

---

## 85. CSS Dropdowns
**Definition:** A CSS dropdown hides a panel of content and reveals it when the user hovers over (or clicks) a trigger element.

**Explanation:**
- Two parts: a trigger (a `<div>`, `<button>`, or link) and a content container holding the hidden panel
- The trigger wrapper uses `position: relative`; the panel uses `position: absolute` so it sits directly below the trigger
- The panel starts at `display: none` and switches to `display: block` via `.dropdown:hover .dropdown-content`
- `min-width` sets the panel width; `box-shadow` gives it a card-like edge without a border
- `:hover` on the trigger is what actually shows the panel

**Example:**
```css
.dropdown {
  position: relative;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 130px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  padding: 12px 16px;
}
.dropdown:hover .dropdown-content {
  display: block;
}
```

The panel is invisible until the pointer enters `.dropdown`, then it drops down over the page content.

---

## 86. Advanced Dropdowns
**Definition:** Advanced dropdown techniques adjust the panel's direction and what goes inside it — right-alignment, images, or a dropdown embedded in a navbar.

**Explanation:**
- By default the panel opens from the left edge of its trigger; adding `right: 0` anchors it to the right edge instead, so the menu opens leftward (useful for the last item in a navbar)
- The panel content is not limited to text links — images and other elements can live inside `.dropdown-content`
- A dropdown can be nested inside a navigation bar's `<li>` to give one menu item a submenu

**Example:**
```css
.dropdown-content {
  right: 0;
}
```

Pinning `right: 0` flips the panel to open toward the left, keeping it on-screen when the trigger sits near the right edge.

---

## 87. CSS Image Gallery
**Definition:** A CSS image gallery arranges a set of thumbnails in an organized, often responsive grid on a page.

**Explanation:**
- Structure: one outer container (`.gallery`) wrapping per-image cells (`.gallery-item`), each holding an `<img>` and an optional description; `display: flex` with `flex-wrap: wrap` on the container flows the cells into rows
- A fixed `width` on each cell plus `width: 100%` on the image makes thumbnails scale to their box; a hover state that darkens the cell border signals the image is clickable
- Media queries re-flow the gallery: four across on wide screens, two on medium, stacked full-width below 480px

**Example:**
```css
div.gallery {
  display: flex;
  flex-wrap: wrap;
}
div.gallery-item {
  margin: 5px;
  border: 1px solid #ccc;
  width: 180px;
}
div.gallery-item:hover {
  border: 1px solid #777;
}
div.gallery-item img {
  width: 100%;
  height: auto;
}
```

Each thumbnail becomes a bordered, hover-highlighted card, and the flex container wraps them into as many rows as needed.

---

## 88. CSS Image Sprites
**Definition:** An image sprite packs many small images into one larger file, and CSS shows only the needed slice of it per element.

**Explanation:**
- One sprite file replaces many small downloads — fewer server requests and less bandwidth
- The two key properties are `background-image` (points at the sprite) and `background-position` (shifts it so only the wanted part shows)
- Each element sets `width`/`height` to match the slice it displays
- Negative `background-position` values move the sprite left/up so a later cell lines up with the box
- For hover states, a second sprite holding hover variants is shown by shifting `background-position` down (for example `-45px` vertically) — no extra file loads on hover

**Example:**
```css
#home {
  width: 46px;
  height: 44px;
  background-image: url(img_navsprites.gif);
  background-position: 0 0;
}

#prev {
  width: 43px;
  height: 44px;
  background-image: url(img_navsprites.gif);
  background-position: -47px 0;
}
```

Both elements load the same sprite, but the negative position on `#prev` slides it so the second icon appears in the box.

---

## 89. CSS Attribute Selectors
**Definition:** Attribute selectors target elements by the presence or value of an HTML attribute, written inside square brackets `[]`.

**Explanation:**
- `[attribute]` matches any element that has the attribute at all
- `[attribute="value"]` demands an exact value match
- `[attribute~="value"]` matches a whole word inside a space-separated list — `title~="flower"` hits `title="summer flower"` but not `title="flowers"` or `title="my-flower"`
- `[attribute|="value"]` matches the exact value or the value followed by a hyphen, so `[class|="top"]` matches `top` and `top-text`
- Matching is case-sensitive by default; add `i` before the closing bracket for a case-insensitive match

**Example:**
```css
a[target] {
  background-color: yellow;
}

a[target="_blank"] {
  background-color: yellow;
}

[title~="flower"] {
  border: 5px solid yellow;
}
```

The first rule highlights any link with a `target` attribute, the second only `target="_blank"` links, and the third borders elements whose `title` contains the standalone word "flower".

---

## 90. Advanced Attribute Selectors
**Definition:** Advanced attribute selectors match partial attribute values with three operators: starts-with, ends-with, and contains.

**Explanation:**
- `[attribute^="value"]` — the value **starts with** the given text
- `[attribute$="value"]` — the value **ends with** the given text
- `[attribute*="value"]` — the value **contains** the given text anywhere
- They are handy for styling form controls by `type` (for example `input[type="text"]`)

**Example:**
```css
input[type="text"] {
  width: 150px;
  padding: 6px;
  margin-bottom: 10px;
  background-color: pink;
}

input[type="button"] {
  width: 100px;
  padding: 6px;
  background-color: lightgreen;
}
```

The same form gets two different looks purely from attribute selectors — no extra classes needed.

---

## 91. CSS Forms
**Definition:** CSS form styling is the practice of overriding the browser's default look for inputs, labels, and buttons so a form matches the rest of the site.

**Explanation:**
- Nearly every control can be styled: text fields, password fields, checkboxes, radio buttons, file inputs, labels, and buttons
- The workhorse properties are `width`, `padding`, `margin`, `border`, `border-radius`, `background-color`, `color`, and `font-size`
- Attribute selectors such as `input[type="text"]` let you style one input type without touching the others

**Example:**
```css
input[type="text"] {
  width: 100%;
  padding: 12px;
  border: 2px solid #ccc;
  border-radius: 8px;
  background-color: #fff;
  color: #333;
  font-size: 16px;
}
```

One rule restyles a text field end to end: full width, roomy padding, a soft rounded border, and readable text.

---

## 92. Style Inputs
**Definition:** Styling inputs means tuning a field's size, spacing, border, and colors with ordinary CSS box properties.

**Explanation:**
- `width` sets the field size — a text input defaults to about 20 characters wide; `width: 100%` makes it fill its container
- `padding` adds space inside the field; `margin` separates stacked fields from each other
- `box-sizing: border-box` includes padding and border in the declared width, so a `width: 100%` field does not overflow its parent
- `border` changes thickness and color; `border-radius` rounds the corners; `border-bottom` alone gives an underline-only look
- `background-color` and `color` set the field's own paint; `input[type=text]` scopes any of this to text fields only

**Example:**
```css
input[type="text"] {
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  box-sizing: border-box;
  border: 2px solid red;
  border-radius: 8px;
  background-color: #3CBC8D;
  color: white;
}
```

A single rule turns a default field into a full-width, rounded, green input with padding that stays inside its container.

---

## 93. Input Focus / Icons
**Definition:** Focus styling customizes an input's appearance when it is clicked or tabbed to, and icons are placed inside fields with background images.

**Explanation:**
- Browsers add a blue outline on focus by default; `outline: none` removes it — but only replace it with another visible focus style
- `:focus` triggers any change on focus, such as a background tint or a thicker border
- Icons use `background-image` plus `background-position` and `background-repeat: no-repeat`, with `padding-left` reserving room so text starts after the icon
- `transition: width 0.4s ease-in-out` animates the field's width when it gains focus

**Example:**
```css
input[type="text"] {
  background-color: white;
  background-image: url('searchicon.png');
  background-position: 10px 10px;
  background-repeat: no-repeat;
  padding-left: 40px;
}

input[type="text"]:focus {
  background-color: lightblue;
}
```

The search icon sits pinned at the left of the field, and the background tints blue whenever the field is active.

---

## 94. Other Form Elements
**Definition:** Textareas, select dropdowns, and form buttons each take their own small set of CSS rules beyond plain text inputs.

**Explanation:**
- `<textarea>` supports `resize: none` to remove the corner grabber that lets users drag it bigger, and `<select>` takes width, padding, border, and background like any block element
- Buttons of type `button`, `submit`, and `reset` are styled together with one selector list; `cursor: pointer` shows the hand pointer
- Media queries make a form responsive: below 600px, labels and fields stack vertically instead of sitting side by side

**Example:**
```css
textarea {
  width: 100%;
  height: 150px;
  padding: 12px 20px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  background-color: #f8f8f8;
  resize: none;
}
input[type="submit"] {
  background-color: #04AA6D;
  border: none;
  color: white;
  padding: 16px 32px;
  cursor: pointer;
}
```

---

## 95. CSS Counters
**Definition:** CSS counters are variables maintained by the browser that let you number elements automatically, without JavaScript.

**Explanation:**
- Four pieces: `counter-reset` creates (or resets) a counter, `counter-increment` bumps it, `content` inserts generated text, and `counter()` prints the current value
- A counter must be created with `counter-reset` before it can be used — typically once on `body`
- `::before` on each heading increments the counter and prints the label
- `counter-increment` takes an optional step value: default `1`, any number to count by more, or `-1` to count down

**Example:**
```css
body {
  counter-reset: section;
}

h2::before {
  counter-increment: section;
  content: "Section " counter(section) ": ";
}
```

Every `<h2>` on the page gets an auto-numbered "Section 1:", "Section 2:", … prefix.

---

## 96. Nested Counters
**Definition:** Nested counters produce multi-level numbering like 1, 1.1, 1.2 by running a counter at each heading or list level.

**Explanation:**
- A top counter (`section`) is reset on `body`; a child counter (`subsection`) is reset on each `<h1>` so it restarts per section
- Each level increments its own counter and prints both values in its `::before`
- The `counters()` function prints a whole chain of nested counter values with a separator string, such as `counters(section, ".")`
- Useful for numbering nested `<ol>` lists without touching the markup

**Example:**
```css
ol {
  counter-reset: section;
  list-style-type: none;
}

li::before {
  counter-increment: section;
  content: counters(section, ".") " ";
}
```

Nested list items print full hierarchical numbers like `1`, `1.1`, `1.1.2`, with the dot inserted by `counters()`.

---

## 97. CSS Units
**Definition:** CSS units are the suffixes that give length values to properties like `font-size`, `width`, `margin`, `padding`, and `border`.

**Explanation:**
- Two families: **absolute** units are fixed sizes, **relative** units scale against something else
- Absolute units never change with screen size, so they suit print or known output more than websites
- Relative units measure against a parent, the root element, or the viewport, which makes them the go-to for responsive layouts
- `px` is the most-used absolute unit; `em` and `rem` are the most-used relative ones

**Example:**
```css
h1 {
  font-size: 40px;
}

p {
  font-size: 1.25rem;
}
```

The heading uses a fixed pixel size while the paragraph scales relative to the root font size.

---

## 98. Absolute Units
**Definition:** Absolute units are fixed lengths that render at exactly the same size regardless of screen or container.

**Explanation:**
- Pixels give complete control but don't respond to screen size, and browser text-size settings won't scale them — they suit print stylesheets or fixed dimensions that must never change
- No space may appear between the number and the unit (except `0`, which drops the unit)

| Unit | Name | Notes |
|---|---|---|
| `px` | Pixels | The most used absolute unit on screens (1px = 1/96th of an inch) |
| `cm` | Centimeters | Primarily used in print stylesheets |
| `mm` | Millimeters | Primarily used in print stylesheets |
| `in` | Inches | Print (1in = 96px = 2.54cm) |
| `pt` | Points | Typographic unit (1pt = 1/72 of an inch) |
| `pc` | Picas | Print unit (1pc = 12pt) |

**Example:**
```css
h1 {
  font-size: 40px;
}
p {
  font-size: 17px;
}
```

Every size is pinned exactly: change the window size and the text stays put.

---

## 99. Relative Units
**Definition:** Relative units express a length as a ratio of another length — a parent's font size, the root font size, or the viewport.

**Explanation:**
- Relative units scale across screen sizes, which makes them ideal for responsive design

| Unit | Description |
|---|---|
| `em` | Relative to the font size of the parent element |
| `rem` | Relative to the font size of the root HTML element |
| `vw` | 1% of the viewport width (100vw = full width) |
| `vh` | 1% of the viewport height (100vh = full height) |
| `vmin` | 1% of the viewport's smaller dimension |
| `vmax` | 1% of the viewport's larger dimension |
| `%` | Relative to the size of the parent element |
| `fr` | Fractional unit — 1fr equals 1 part of the available space |
| `ch` | Relative to the width of the "0" (zero) character |

**Example:**
```css
html {
  font-size: 16px;
}
h1 {
  font-size: 2.5rem;
}
```

The heading renders at 40px, calculated from the root size — bump `html`'s font size and everything in `rem` follows.

---

## 100. CSS Inheritance
**Definition:** Inheritance decides what a property does on an element when no value is set for it: copy the parent's computed value, or fall back to the initial default.

**Explanation:**
- **Inherited properties** default to the parent's value — text properties like `color`, `font-family`, `font-size`, `line-height`, and `text-align`
- **Non-inherited properties** reset to their initial value — box/layout properties like `border`, `background`, `margin`, `padding`, `width`, and `height`
- So a `<strong>` inside a colored `<p>` inherits the color, but it does not inherit the paragraph's border
- The `inherit` keyword forces inheritance on any property, inherited or not: `strong { border: inherit; }` gives the strong text the same border as its parent

**Example:**
```css
p {
  color: blue;
  font-size: 20px;
  border: 1px solid red;
}

strong {
  border: inherit;
}
```

The bold text inside the paragraph picks up the blue 20px text automatically, and gets the red border only because `inherit` asked for it explicitly.

---

## 101. CSS Specificity
**Definition:** CSS specificity is the algorithm that picks which competing rule wins when several selectors match the same element.

**Explanation:**
- The declaration from the highest-specificity selector is applied; the others are ignored for that property
- A class selector (`.test`) beats a bare element selector (`p`)
- An ID selector (`#demo`) beats a class selector
- An inline `style` attribute beats every stylesheet rule
- This ordering is why the same property set three times only shows one value

**Example:**
```css
#demo {
  color: blue;
}

.test {
  color: green;
}

p {
  color: red;
}
```

On `<p id="demo" class="test">`, the text renders blue — the ID selector out-ranks both the class and the element rule.

---

## 102. Specificity Hierarchy
**Definition:** The specificity hierarchy ranks selector types by weight, expressed as an X-Y-Z notation, to predict which rule wins.

**Explanation:**
- Weights, highest to lowest: inline styles (highest) → ID selectors `1-0-0` → classes/attribute selectors/pseudo-classes `0-1-0` → elements/pseudo-elements `0-0-1` → universal selector and `:where()` `0-0-0`
- X counts IDs, Y counts classes/attributes/pseudo-classes, Z counts elements/pseudo-elements
- Compare left to right: the higher leftmost number wins; if equal, move to the next number
- Ties break by source order — the latest rule wins; an embedded `<style>` also beats an external stylesheet at equal weight because it is closer to the element

**Example:**
```css
#demo {
  color: blue;
}      /* 1-0-0 */

p#demo {
  color: orange;
}      /* 1-0-1 — wins */

p.test {
  color: green;
}      /* 0-1-1 */

p {
  color: red;
}      /* 0-0-1 */
```

`p#demo` wins because its Z column is non-zero while the ID-only rule's is not — extra elements add weight even under the same ID.

---

## 103. CSS !important
**Definition:** `!important` is appended to a declaration to give that value the highest priority, overriding every other rule for that property on that element.

**Explanation:**
- Syntax: the keyword goes at the end of the declaration, before the semicolon — `color: red !important;`
- It beats inline styles, IDs, and classes alike for the property it is attached to
- The only way to beat an `!important` value is another `!important` at equal or higher specificity, which quickly makes stylesheets confusing to debug
- Fair uses: overriding CSS you cannot edit (a CMS), honoring `prefers-reduced-motion` to kill animations, and locking a component's look against conflicting rules

**Example:**
```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation: none !important;
    transition: none !important;
  }
}
```

Users who asked their system to reduce motion get all animation and transition turned off, no matter what other rules request.

---

## 104. CSS Math Functions
**Definition:** CSS math functions let a property value be computed at render time from an expression instead of a fixed number.

**Explanation:**
- `calc()` supports `+`, `-`, `*`, `/` and mixes units freely, such as `calc(100% - 100px)`
- `max()` picks the largest value from a comma-separated list; `min()` picks the smallest
- `clamp(min, preferred, max)` returns the preferred value unless it falls outside the bounds, in which case the nearer bound is used — perfect for fluid type that never gets too small or too large
- The preferred value in `clamp()` is required; min and max are optional

**Example:**
```css
h2 {
  font-size: clamp(1.5rem, 5vw, 3rem);
}

div {
  width: clamp(200px, 50%, 600px);
}
```

Type and width track the viewport through the middle value but stop at the 1.5rem/200px floors and 3rem/600px ceilings.

---

## 105. CSS Optimization
**Definition:** CSS optimization is the set of practices that make a stylesheet smaller and faster to apply, so pages load and run more smoothly.

**Explanation:**
- Prefer short, simple selectors — deeply chained selectors cost parsing time
- Avoid the universal selector `*` for broad styling; it hits every element and slows rendering
- Keep styles out of inline `style` attributes: they bloat HTML and are hard to manage
- Load external CSS with `<link>` in `<head>`, not `@import`, which delays stylesheet loading
- Use shorthand properties (`margin: 10px 20px`) to save bytes and parsing
- Animate `transform`, `opacity`, and `filter` instead of `width`, `height`, `left`, `top`, which force layout recalculations
- Combine and minify into one file, and set a long cache expiry on the server so browsers reuse it

**Example:**
```css
/* Long version */
margin-top: 10px;
margin-right: 20px;
margin-bottom: 10px;
margin-left: 20px;

/* Shorthand version */
margin: 10px 20px;
```

The shorthand expresses the same four values in one declaration — less text to ship and parse.

---

## 106. CSS Accessibility
**Definition:** CSS accessibility styling means choosing visual styles that keep the page usable for people with disabilities, including low vision and motion sensitivity.

**Explanation:**
- Keep strong contrast between text and background; gray-on-gray fails for low-vision and color-blind users
- Use a readable font with comfortable size and `line-height`, and size text in `rem` so users can scale it in their browser settings
- Give interactive elements a visible `:focus` style so keyboard and screen-reader users can track the active element
- Never remove focus outlines without replacing them with another visible indicator
- Pair CSS with semantic HTML (`<nav>`, `<aside>`) rather than styling plain `<div>`s for everything
- Honor `prefers-reduced-motion` to disable animations for users who requested less motion

**Example:**
```css
body {
  background-color: #ffffff;
  color: #000000;
  font-family: Arial, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
}

a:focus,
button:focus,
input:focus {
  outline: 2px solid orange;
}
```

Maximum contrast, scalable text, and a bold orange focus ring make the page navigable by keyboard and readable at any zoom level.

---

## 107. CSS Website Layout
**Definition:** CSS website layout divides a page into its standard regions — header, navigation, content columns, and footer — and makes them adapt to screen size.

**Explanation:**
- The common skeleton is header on top, nav below it, content in the middle, footer at the bottom
- The header and footer are simple blocks: background color, centered text, padding
- Content commonly uses 1 column on mobile, 2 on tablets/laptops, 3 on desktops
- Flexbox holds the columns side by side; a media query flips `flex-direction` to `column` below 600px so they stack on phones
- A footer can also be pinned with `position: fixed; bottom: 0;` plus `z-index` so it stays visible while scrolling

**Example:**
```css
div.flex-container {
  display: flex;
  flex-direction: row;
}

div.flex-container > div {
  margin: 10px;
}

@media screen and (max-width: 600px) {
  div.flex-container {
    flex-direction: column;
  }
}
```

Three columns sit in a row on wide screens and collapse into a single stacked column once the viewport drops below 600px.

---

## 108. CSS Rounded Corners
**Definition:** The `border-radius` property rounds an element's corners, working on any box with a background, border, or background image.

**Explanation:**
- One value rounds all four corners equally; two values set top-left/bottom-right then top-right/bottom-left; three values set top-left, then top-right and bottom-left, then bottom-right; four values run clockwise from top-left
- It is shorthand for `border-top-left-radius`, `border-top-right-radius`, `border-bottom-right-radius`, and `border-bottom-left-radius`
- Two values separated by a slash give an elliptical corner: `70px / 30px` = horizontal radius then vertical radius
- `border-radius: 50%` makes an oval from a rectangle or a circle from a square

**Example:**
```css
#div1 {
  border-radius: 15px 50px 30px 5px; /* TL TR BR BL */
  background: #04AA6D;
  width: 200px;
  height: 150px;
}

#div3 {
  border-radius: 70px / 30px;
  background: #04AA6D;
  width: 200px;
  height: 150px;
}
```

The first box gets a different radius per corner (clockwise from top-left), the second gets wide, shallow elliptical corners from the slash syntax.

---

## 109. CSS Border Images
**Definition:** The `border-image` property lets you replace a normal border with a picture that is sliced into nine parts and reassembled around the element.

**Explanation:**
- The image is cut like a tic-tac-toe board: corners land on the corners, edges and middle are stretched or tiled as you choose
- It is shorthand for `border-image-source` (the image path), `border-image-slice` (how far from each edge to cut), `border-image-width`, `border-image-outset`, and `border-image-repeat`
- The element still needs a regular `border` property set for the image border to appear
- Slice can be a pixel count (`30`) or a percentage (`20%`); repeat options include `round` (tile and rescale to fit) and `stretch`
- Different slice values completely change how much of the image ends up in each of the nine regions

**Example:**
```css
#borderimg {
  border: 10px solid transparent; /* required for border-image */
  padding: 15px;
  border-image: url(border.png) 30 round;
}
```

`border.png` is cut 30 pixels in from every edge; the center section tiles to fill the middle, rescaling if needed to close gaps.

---

## 110. CSS Multiple Backgrounds
**Definition:** One element can carry several background images at once, layered on top of each other through the `background-image` property.

**Explanation:**
- Separate images with commas; the first image in the list sits closest to the viewer
- Position, repeat, and size lists must line up with the image list, one value per image
- The `background` shorthand accepts the same comma-separated stacks
- Later images show through wherever earlier ones do not cover

**Example:**
```css
#example1 {
  background-image: url(img_flwr.gif), url(paper.gif);
  background-position: right bottom, left top;
  background-repeat: no-repeat, repeat;
}
```

A flower is pinned to the bottom-right with no repeat, while a paper texture fills the rest of the box underneath.

---

## 111. Background Size
**Definition:** The `background-size` property sets how large a background image is drawn, in lengths, percentages, or the keywords `auto`, `contain`, and `cover`.

**Explanation:**
- Two length or percentage values set width and height; one value sets width only and height stays `auto`
- `auto` (the default) keeps the image at its natural size
- `contain` scales the image up or down until it fits entirely inside the content area
- `cover` scales the image until the content area is fully covered, cropping whatever sticks out
- With multiple backgrounds, pass a comma-separated size list matching each image
- `html { background: url(...) center fixed; background-size: cover; }` is the standard recipe for a full-window background that never leaves white gaps or scrollbars

**Example:**
```css
#div1 {
  border: 1px solid black;
  background-image: url(img_flwr.gif);
  background-repeat: no-repeat;
  background-size: contain;
}

#div2 {
  border: 1px solid black;
  background-image: url(img_flwr.gif);
  background-repeat: no-repeat;
  background-size: cover;
}
```

The first box shrinks or grows the flower to fit inside without cropping; the second enlarges it until every corner of the box is covered.

---

## 112. Background Origin
**Definition:** The `background-origin` property decides which box the background image starts from: the padding edge, the border edge, or the content edge.

**Explanation:**
- `padding-box` is the default — the image begins at the top-left corner of the padding area
- `border-box` starts the image at the top-left of the border
- `content-box` starts it at the top-left of the content
- It only matters when padding or a border is present, and it has no effect when `background-attachment` is `fixed`

**Example:**
```css
#div1 {
  border: 2px solid black;
  padding: 35px;
  background-image: url(img_flwr.gif);
  background-repeat: no-repeat;
  background-origin: padding-box;
}

#div2 {
  border: 2px solid black;
  padding: 35px;
  background-image: url(img_flwr.gif);
  background-repeat: no-repeat;
  background-origin: content-box;
}
```

Identical boxes show the flower anchored to the padding edge in one and to the content edge in the other.

---

## 113. Background Clip
**Definition:** The `background-clip` property controls how far the background color, image, or gradient extends inside an element.

**Explanation:**
- `border-box` (default) lets the background run all the way behind the border
- `padding-box` stops the background at the inner edge of the border
- `content-box` confines the background to the content area only
- The effect is easiest to see with a transparent or dotted border, or with a solid background color that stops short of the border

**Example:**
```css
#div1 {
  border: 5px dotted black;
  padding: 35px;
  background-color: lightblue;
  background-clip: border-box;
}

#div2 {
  border: 5px dotted black;
  padding: 35px;
  background-color: lightblue;
  background-clip: content-box;
}
```

The first box's blue fills behind the dotted border; the second's blue stops at the content edge, leaving padding and border unpainted.

---

## 114. CSS Gradients
**Definition:** CSS gradient functions paint a smooth transition between two or more colors inside an element, with no image file required.

**Explanation:**
- CSS defines three kinds: linear (straight-line color change), radial (outward from a center point), and conic (rotated around a center)
- All gradient functions are used as values of `background-image`
- Every gradient needs at least two color stops — the colors to blend between
- Linear gradients accept a direction keyword (`to bottom`, `to right`, `to bottom right`, …) or an angle (`0deg` = to top, `90deg` = to right, `180deg` = to bottom)
- Transparency works by using `rgba()` color stops, where the last parameter is 0 (fully transparent) to 1 (fully opaque)
- `repeating-linear-gradient()` tiles the gradient pattern over and over

**Example:**
```css
#grad {
  background-image: linear-gradient(to right, red, yellow);
}

#grad2 {
  background-image: linear-gradient(180deg, rgba(255, 0, 0, 0), rgba(255, 0, 0, 1));
}
```

The first box blends red into yellow left to right; the second fades from fully transparent red to solid red using an explicit angle and rgba stops.

---

## 115. Radial Gradients
**Definition:** A radial gradient spreads color outward from a center point, shaped as an ellipse or a circle.

**Explanation:**
- Built with `radial-gradient()`, which needs at least two color stops
- Optional parameters are `shape` (`ellipse` default, or `circle`), `size`, and `position` (defaults to center)
- Size keywords: `closest-side`, `farthest-side`, `closest-corner`, and `farthest-corner` (default)
- Color stops can be unevenly spaced with percentages: `radial-gradient(red 5%, yellow 15%, green 60%)`
- `repeating-radial-gradient()` repeats the pattern outward from the center

**Example:**
```css
#grad {
  background-image: radial-gradient(circle, red, yellow, green);
}

#grad2 {
  background-image: radial-gradient(closest-side at 70% 60%, red, yellow, black);
}
```

The first box blends three colors in a perfect circle from the center; the second forces the circle's edge to the nearest side and shifts its center to 70% / 60%.

---

## 116. Conic Gradients
**Definition:** A conic gradient rotates colors around a center point like a pie chart or color wheel.

**Explanation:**
- Built with `conic-gradient()`, which needs at least two colors
- Without degrees, colors are spread equally around the circle; with degrees you pin each stop to an angle (`red 45deg, yellow 90deg, green 210deg`)
- `from angle` rotates the whole gradient; `at position` moves the center (default `center`)
- Adding `border-radius: 50%` turns a square conic gradient into a pie chart
- Hard-stop pairs (`red 0deg 90deg, yellow 90deg 180deg, …`) create flat wedges instead of blends
- `repeating-conic-gradient()` tiles the pattern around the center

**Example:**
```css
#grad {
  background-image: conic-gradient(from 90deg, red, yellow, green);
  border-radius: 50%;
}
```

Three colors sweep around a circular pie, with the whole gradient rotated a quarter turn by `from 90deg`.

---

## 117. CSS Shadows
**Definition:** `text-shadow` paints one or more drop shadows behind the text of an element.

**Explanation:**
- Basic form is horizontal offset, vertical offset, then optional blur radius and color: `2px 2px 5px red`
- The color defaults to the current text color when omitted
- Comma-separated lists stack multiple shadows; the first in the list draws on top
- A tight blur and bright color produces a neon glow (`0 0 3px #ff0000`)
- Four shadows of 1px each on the four sides simulate a plain outline around the text

**Example:**
```css
h1 {
  color: white;
  text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;
}
```

White text picks up a tight black drop shadow plus two soft blue glows layered underneath it.

---

## 118. Box Shadow
**Definition:** The `box-shadow` property draws one or more shadows around (or inside) an element's frame.

**Explanation:**
- Order of parameters: horizontal offset, vertical offset, blur radius, spread radius, color, and optional `inset`
- At minimum you only need the two offsets; the default color is the current text color
- Blur radius softens the shadow; spread radius grows (positive) or shrinks (negative) the shadow's size
- `inset` turns the shadow into an inner shadow drawn inside the element's padding
- Multiple shadows are a comma-separated list, drawn first-listed on top
- A common card look is two stacked soft shadows: `0 4px 8px rgba(0,0,0,0.2), 0 6px 20px rgba(0,0,0,0.19)`

**Example:**
```css
div {
  box-shadow: 10px 10px 5px 12px lightblue;
}

div.card {
  width: 250px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2),
              0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: center;
}
```

The first box gets a soft light-blue shadow offset down-right with a large spread; the card uses two stacked grey shadows for a paper-lift effect.

---

## 119. CSS Text Effects
**Definition:** A small set of CSS properties governs text overflow, long-word wrapping, line-breaking rules, and writing direction.

**Explanation:**
- `text-overflow` signals clipped overflow with `clip` (hard cut) or `ellipsis` (…); it also needs `white-space: nowrap;` and `overflow: hidden;`
- `word-wrap: break-word` forces a too-long word to break and wrap instead of spilling outside the box
- `word-break` accepts `normal` (language default), `break-all` (any character), or `keep-all` (never break)
- `writing-mode` lays lines out `horizontal-tb` (default), `vertical-rl`, or `vertical-lr`

**Example:**
```css
p {
  width: 200px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
```

A 200px-wide box with nowrap cuts overflowing text and marks the cut with an ellipsis.

---

## 120. CSS Custom Fonts
**Definition:** The `@font-face` rule lets a page load its own font file from the server, so the typeface does not need to be installed on the visitor's machine.

**Explanation:**
- The two required descriptors are `font-family` (the name you will use) and `src` (a URL to the font file)
- Optional descriptors: `font-stretch`, `font-style`, `font-weight`, `font-display`, and `unicode-range`
- Once registered, apply the font with the ordinary `font-family` property using the name you chose
- A separate `@font-face` rule with `font-weight: bold` points bold text at a bold font file
- WOFF/WOFF2 are the preferred web formats (small, universally supported); TTF/OTF work but are not web-optimized

**Example:**
```css
@font-face {
  font-family: myFont;
  src: url(sansation_light.woff);
}

@font-face {
  font-family: myFont;
  src: url(sansation_bold.woff);
  font-weight: bold;
}

p {
  font-family: myFont;
}
```

Two rules register regular and bold files under one family name; browsers pick the bold file automatically for bolded text.

---

## 121. CSS 2D Transforms
**Definition:** The CSS `transform` property moves, rotates, scales, or skews an element in two dimensions, without affecting the layout of anything around it.

**Explanation:**
- Available 2D functions: `translate()`, `translateX()`, `translateY()`, `rotate()`, `scale()`, `scaleX()`, `scaleY()`, `skew()`, `skewX()`, `skewY()`, and `matrix()`
- `translate(50px, 100px)` shifts an element 50px right and 100px down from its current spot
- `rotate(20deg)` turns clockwise; `rotate(-20deg)` turns counter-clockwise
- `transform-origin` changes the pivot point for rotation, scale, and skew (default is the element's center)
- The two transform properties are `transform` itself and `transform-origin`

**Example:**
```css
div {
  transform: translate(50px, 100px) rotate(20deg);
}
```

The box is first slid 50px right and 100px down, then spun 20 degrees clockwise about its center.

---

## 122. CSS 2D Transform Scale
**Definition:** The scale family of 2D transform functions grows or shrinks an element's size relative to its original dimensions.

**Explanation:**
- `scale(2, 3)` doubles the width and triples the height
- `scale(0.5, 0.5)` halves both dimensions
- `scaleX(2)` and `scaleY(3)` change only one axis at a time
- Values below 1 shrink; values above 1 enlarge; 1 leaves the size unchanged
- The transform does not reflow surrounding elements — it only paints the box differently

**Example:**
```css
div {
  transform: scale(2, 3);
}

div.small {
  transform: scale(0.5, 0.5);
}
```

The first box is painted twice as wide and three times as tall; the second is painted at half size in both directions.

---

## 123. CSS 2D Transform Skew / Matrix
**Definition:** Skew functions slant an element along an axis by a given angle, while `matrix()` combines every 2D transform into one six-value function.

**Explanation:**
- `skewX(20deg)` slants along the X-axis; `skewY(20deg)` slants along the Y-axis
- `skew(20deg, 10deg)` slants both axes at once; omitting the second angle leaves it at 0
- `matrix()` packs translate, rotate, scale, and skew into six numbers ordered `scaleX(), skewY(), skewX(), scaleY(), translateX(), translateY()`
- Skew angles use `deg` units just like rotation

**Example:**
```css
div {
  transform: skew(20deg, 10deg);
}

div.m {
  transform: matrix(1, -0.3, 0, 1, 0, 0);
}
```

The first box is sheared 20 degrees on X and 10 degrees on Y; the second uses a matrix whose second parameter applies the same kind of Y-axis shear.

---

## 124. CSS 3D Transforms
**Definition:** The same `transform` property can also rotate, move, and scale an element along a depth axis, placing it in a three-dimensional space.

**Explanation:**
- For 3D to look three-dimensional the scene needs perspective; without it, every 3D transform still renders flat
- Core 3D functions: `rotateX()` (tilt forward/backward), `rotateY()` (swivel left/right like a door), `rotateZ()` (spin in the screen plane), and `translateZ()` (move closer or farther)
- Positive `translateZ` brings an element toward the viewer; negative pushes it away
- Related properties: `transform-style` (how nested children live in 3D), `perspective`, `perspective-origin`, and `backface-visibility`
- `scaleZ()` scales along the depth axis

**Example:**
```css
.box {
  transform: rotateX(45deg);
}

.box2 {
  transform: rotateY(45deg) translateZ(-100px);
}

.box3 {
  transform: rotateZ(45deg);
}
```

Three boxes demonstrate the three rotation axes: a forward tilt, a side swivel combined with a step backward in depth, and an in-plane spin.

---

## 125. 3D Perspective
**Definition:** Perspective sets the viewer's distance from the 3D scene, which is what makes depth and foreshortening visible.

**Explanation:**
- A low value like `perspective: 200px` places the viewer close and exaggerates the 3D effect
- A high value like `perspective: 2000px` places the viewer far away and flattens the effect
- Perspective can be set two ways: the `perspective` property on a parent, or the `perspective()` function inside a child's `transform`
- The `perspective` property goes on the parent so every child shares one 3D space
- `perspective()` applies depth to a single element only, so siblings do not share a common vanishing point
- Both approaches produce the same look on a lone transformed element

**Example:**
```css
.container {
  width: 180px;
  height: 180px;
  perspective: 500px;
}

.box {
  width: 100%;
  height: 100%;
  background-color: green;
  transform: rotateY(45deg);
}
```

The container declares a 500px viewing distance; the child then swivels 45 degrees and appears to recede into the screen with real foreshortening.

---

## 126. 3D Card Flip
**Definition:** A card flip is the classic two-faced 3D object: a container provides perspective, a card rotates in that space, and front/back faces swap which side faces the viewer.

**Explanation:**
- HTML shape: a `.container` holds a `.card`, which holds two `.face` elements (`.front` and `.back`)
- The container gets `perspective`; the card gets `position: relative`, `transform-style: preserve-3d`, and a `transition` on `transform`
- `preserve-3d` is essential — without it the faces collapse into a flat 2D sheet
- Faces are absolutely positioned, full size, with `backface-visibility: hidden` so a face disappears when turned away
- The back face starts at `rotateY(180deg)`; hovering the container rotates the card the same amount

**Example:**
```css
.container { width: 200px; height: 250px; perspective: 600px; }
.card { width: 100%; height: 100%; position: relative;
  transition: transform 1s; transform-style: preserve-3d; }
.face { position: absolute; height: 100%; width: 100%;
  backface-visibility: hidden; text-align: center; }
.front { background: green; }
.back { background: red; transform: rotateY(180deg); }
.container:hover .card { transform: rotateY(180deg); }
```

Hovering spins the card a half-turn over one second; `backface-visibility` hides whichever face points away mid-flip.

---

## 127. 3D Cube
**Definition:** A rotating 3D cube stacks six absolutely positioned faces, each rotated and pushed outward by half the cube's width to form the six sides of a box.

**Explanation:**
- HTML: one `.container` with perspective, one `.cube` with `preserve-3d` and an animation, and six `.face` divs
- Each face is rotated on its axis then translated by half the cube width (`translateZ(100px)` for a 200px cube)
- Face rotations: front `rotateY(0deg)`, back `rotateY(180deg)`, left `rotateY(-90deg)`, right `rotateY(90deg)`, top `rotateX(90deg)`, bottom `rotateX(-90deg)`
- A translucent background lets the viewer see depth through near faces
- A `@keyframes spin` rule rotating both axes from 0 to 360 degrees, run infinitely, tumbles the cube continuously

**Example:**
```css
.container { width: 200px; height: 200px; margin: 100px auto; perspective: 600px; }
.cube { width: 100%; height: 100%; position: relative;
  transform-style: preserve-3d; animation: spin 12s infinite linear; }
.front { transform: rotateY(0deg) translateZ(100px); }
.back  { transform: rotateY(180deg) translateZ(100px); }
.left  { transform: rotateY(-90deg) translateZ(100px); }
.right { transform: rotateY(90deg) translateZ(100px); }
.top    { transform: rotateX(90deg) translateZ(100px); }
.bottom { transform: rotateX(-90deg) translateZ(100px); }
@keyframes spin {
  from { transform: rotateX(0deg) rotateY(0deg); }
  to   { transform: rotateX(360deg) rotateY(360deg); }
}
```

Six faces are rotated and pushed 100px out from center to form a closed cube, which then tumbles forever on both axes.

---

## 128. 3D Carousel
**Definition:** A 3D carousel arranges several cards evenly around a vertical cylinder and spins the whole ring so each card takes a turn at the front.

**Explanation:**
- Ring radius is calculated as `(card-width / 2) / tan(360 / total-items / 2)` — for six 200px cards that is about 173px
- Custom properties in `:root` keep the math in one place; each card gets an `--index` and is absolutely positioned
- Every card uses `rotateY(calc(var(--index) * (360deg / var(--total-items))))` then `translateZ(var(--radius))`
- The `.carousel` needs `transform-style: preserve-3d` plus an infinite linear spin animation
- `animation-play-state: paused` on `:hover` freezes the wheel for easier viewing

**Example:**
```css
:root { --total-items: 6; --radius: 173px; }
.container { width: 200px; height: 300px; margin: 80px auto; perspective: 1000px; }
.carousel { width: 100%; height: 100%; position: relative;
  transform-style: preserve-3d; animation: spin 20s infinite linear; }
.card { position: absolute; width: 100%; height: 100%;
  transform: rotateY(calc(var(--index) * (360deg / var(--total-items))))
             translateZ(var(--radius)); }
@keyframes spin { from { transform: rotateY(0deg); } to { transform: rotateY(360deg); } }
.carousel:hover { animation-play-state: paused; }
```

Six cards are angled evenly around a cylinder of the calculated radius; a shared Y-axis animation rotates the ring, and hovering pauses it.

---

## 129. CSS Transitions
**Definition:** CSS transitions animate a property from one value to another over a set duration, so changes like hover effects happen smoothly instead of instantly.

**Explanation:**
- At minimum you need the property to animate and a duration; `transition: width 2s;` is a complete transition
- The `transition` property is shorthand for `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`
- Transitions fire when a property value changes — most often inside a pseudo-class such as `:hover`, `:active`, `:focus`, or `:checked`
- Multiple properties each with their own duration are a comma list: `transition: width 2s, height 4s, background-color 3s;`
- The effect also runs in reverse when the trigger stops (for example when the pointer leaves)

**Example:**
```css
div {
  width: 100px;
  height: 100px;
  background-color: red;
  transition: width 2s;
}

div:hover {
  width: 300px;
}
```

Hovering grows the box's width from 100px to 300px over two seconds; leaving the box eases it back down again.

---

## 130. Transition Timing
**Definition:** `transition-timing-function` shapes the speed curve of a transition, and `transition-delay` holds it back before it starts.

**Explanation:**
- Keyword curves: `ease` (default — slow start, fast middle, slow end), `linear` (constant speed), `ease-in` (slow start), `ease-out` (slow end), `ease-in-out` (slow at both ends)
- `cubic-bezier(n,n,n,n)` builds a custom curve from four control-point values
- `transition-delay` accepts seconds (`s`) or milliseconds (`ms`); `1s` waits one second before animating
- The four longhand properties can be listed individually or packed into one shorthand in the order `property duration timing-function delay`

**Example:**
```css
div {
  transition-property: width;
  transition-duration: 2s;
  transition-timing-function: linear;
  transition-delay: 1s;
}

button {
  transition: background-color 1s ease-out, transform 1s ease-out;
}
```

The div's width change waits one second, then runs at constant speed for two seconds; the button eases both its color and transform over one second.

---

## 131. CSS Animations
**Definition:** CSS animations move an element through a sequence of style steps defined in `@keyframes`, without any JavaScript.

**Explanation:**
- An animation needs a name (`animation-name`) and a duration (`animation-duration`); with the default `0s` duration nothing plays
- `@keyframes` holds the styles at each moment; `from`/`to` are shortcuts for `0%`/`100%`
- Percentage steps in between allow any number of intermediate states and can animate many properties at once

**Example:**
```css
@keyframes myAnimation {
  0%   { background-color: red; left: 0; top: 0; }
  25%  { background-color: yellow; left: 200px; top: 0; }
  50%  { background-color: blue; left: 200px; top: 200px; }
  75%  { background-color: green; left: 0; top: 200px; }
  100% { background-color: red; left: 0; top: 0; }
}
div {
  width: 100px; height: 100px; position: relative; background-color: red;
  animation-name: myAnimation; animation-duration: 4s;
}
```

Over four seconds the box cycles through four colors while walking the four corners of a square and returning to its start.

---

## 132. Animation Timing
**Definition:** `animation-delay`, `animation-iteration-count`, and `animation-timing-function` control when an animation starts, how many times it repeats, and the shape of its speed curve.

**Explanation:**
- `animation-delay` waits before the first frame; a negative value starts the animation as if it had already been running for that many seconds
- `animation-iteration-count` takes a number (`3`) or `infinite` for a loop
- `animation-timing-function` uses the same keyword curves as transitions: `ease` (default), `linear`, `ease-in`, `ease-out`, `ease-in-out`, or `cubic-bezier(n,n,n,n)`
- All three are independent longhands that pair with `animation-name` and `animation-duration`

**Example:**
```css
div {
  width: 100px;
  height: 100px;
  position: relative;
  background-color: red;
  animation-name: myAnimation;
  animation-duration: 4s;
  animation-delay: -2s;
  animation-iteration-count: 3;
  animation-timing-function: ease-in-out;
}
```

The animation skips ahead two seconds as if already mid-play, runs three full cycles, and eases at both ends of every cycle.

---

## 133. Animation Properties
**Definition:** `animation-direction` chooses the playback order, `animation-fill-mode` decides what the element looks like before and after the animation, and the `animation` shorthand packs all seven longhands into one line.

**Explanation:**
- `animation-direction`: `normal` (forward, default), `reverse`, `alternate` (forward then backward), `alternate-reverse` (backward then forward)
- Without a fill mode an element snaps back to its pre-animation styles the instant the last keyframe ends
- `animation-fill-mode`: `none` (default), `forwards` (keep last keyframe), `backwards` (apply first keyframe during the delay), `both` (forwards + backwards)
- The shorthand order is `animation: name duration timing-function delay iteration-count direction fill-mode`
- The full property family also includes `animation-play-state` (`running` or `paused`)

**Example:**
```css
div {
  width: 100px; height: 100px; background: red; position: relative;
  animation-name: myAnimation; animation-duration: 5s;
  animation-timing-function: linear; animation-delay: 2s;
  animation-iteration-count: infinite; animation-direction: alternate;
  animation-fill-mode: both;
}
div.short { animation: myAnimation 5s linear 2s infinite alternate; }
```

Both boxes run the same animation forever, alternating direction each cycle; the longhand version also uses `fill-mode: both`.

---

## 134. CSS Tooltips
**Definition:** A CSS tooltip is a small styled box of extra text that appears when the user hovers over a trigger element.

**Explanation:**
- HTML shape: a container `.tooltip` wraps the trigger text plus an inline `.tooltiptext` span holding the tip
- The container uses `position: relative` so the tip can be absolutely positioned; a dotted bottom border and `cursor: pointer` mark it as hoverable
- The tip starts with `visibility: hidden`, a dark background, light text, padding, border-radius, and `z-index: 1`; `:hover` flips it to `visible`
- Positioning offsets: `left: 105%` (right side) or `right: 105%` (left side) with `top: -5px` to counteract vertical padding
- For top/bottom placement use `bottom: 100%` or `top: 100%` with `margin-left: -half-the-tip-width` to center it
- Swapping `visibility` for `opacity: 0` plus a transition and `opacity: 1` on hover produces a fade instead of a snap

**Example:**
```css
.tooltip { position: relative; display: inline-block;
  border-bottom: 1px dotted black; cursor: pointer; }
.tooltiptext {
  visibility: hidden; width: 130px; background-color: black; color: #ffffff;
  text-align: center; padding: 5px 0; border-radius: 6px;
  position: absolute; z-index: 1; bottom: 100%; left: 50%; margin-left: -65px;
}
.tooltip:hover .tooltiptext { visibility: visible; }
```

Hovering the dotted trigger reveals a dark tip centered above it; `margin-left: -65px` cancels half the tip's 130px width so it lines up under the trigger text.

---

## 135. Tooltip Arrows
**Definition:** A tooltip arrow is a small triangular pointer drawn with borders on a `::after` pseudo-element, making the tooltip look like a speech bubble aimed at its trigger.

**Explanation:**
- The arrow is created with `content: " "` on `::after`, `position: absolute`, and four equal `border-width` values
- Three borders are `transparent` and one is the tip color; that single colored border renders as a triangle
- Bottom arrow: `top: 100%` places it under the tip, `left: 50%` centers it, and `border-color: black transparent transparent transparent`
- Top arrow: same idea with `bottom: 100%` and the black on the bottom border
- Left arrow: `right: 100%` with black on the right border; right arrow: `left: 100%` with black on the left border
- Keep `margin-left` (or `margin-top` for side arrows) at half the `border-width`, so a 5px arrow uses -5px, to stay centered
- Changing the border-width without also changing that negative margin throws the arrow off-center

**Example:**
```css
.tooltiptext::after {
  content: " ";
  position: absolute;
  top: 100%;
  left: 50%;
  margin-left: -5px;
  border-width: 5px;
  border-style: solid;
  border-color: black transparent transparent transparent;
}
```

A 5px black triangle sits centered on the bottom edge of the tooltip, pointing down at the trigger text below it.

---

## 136. CSS Image Styling
**Definition:** Core CSS techniques for shaping and sizing images: rounded corners, thumbnail frames, responsive scaling, card layouts, and galleries.

**Explanation:**
- `border-radius` rounds image corners — a small value softens them; `50%` makes a circle
- A thin border, padding, and a fixed `width` together create a thumbnail frame; adding a hover `box-shadow` makes it feel clickable
- `max-width: 100%; height: auto;` is the standard responsive recipe: images shrink to fit but never enlarge past their natural size
- A white card with a layered `box-shadow` plus a full-width image inside gives a Polaroid-style look
- Media queries can reflow gallery items — two columns on tablets, one on phones

**Example:**
```css
img {
  border-radius: 8px;
  max-width: 100%;
  height: auto;
  border: 1px solid #ddd;
  padding: 5px;
}

img:hover {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
```

Corners are softened, the image scales down responsively inside its container, and a subtle glow appears on hover to suggest interactivity.

---

## 137. Image Effects
**Definition:** The `opacity` property controls how transparent an element is, from fully invisible to fully solid.

**Explanation:**
- Accepts a number from `0.0` (completely transparent) to `1.0` (fully opaque); `0.5` is 50% see-through
- The default is `1.0`
- Lowering opacity on an image is a quick way to fade it into the background or dim it under an overlay
- Pairing opacity with positioning lets you place text directly on top of an image without a separate overlay layer
- For blur, saturation, and other visual effects, use the `filter` property instead (covered under Image Filters)

**Example:**
```css
img {
  opacity: 0.5;
}
```

The image renders at half transparency, letting whatever is behind it show through.

---

## 138. Hover Overlays
**Definition:** Hover effects that transform or rearrange images — flipping them horizontally or reflowing a gallery on smaller screens.

**Explanation:**
- `transform: scaleX(-1)` mirrors an image left-to-right when the pointer hovers over it
- The same media-query gallery pattern used elsewhere applies here: items drop to two columns under 768px and one column under 480px
- Overlay panels on hover typically use absolute positioning over the image, but the flip and gallery reflow are the core techniques on this page
- Combine with `transition` for a smooth flip rather than an instant snap

**Example:**
```css
img:hover {
  transform: scaleX(-1);
}

@media only screen and (max-width: 768px) {
  div.gallery-item {
    width: calc(50% - 20px);
  }
}
```

Hovering flips the image like a mirror; below 768px the gallery items each take half the row width so the layout collapses gracefully.

---

## 139. CSS Image Modal
**Definition:** A modal image gallery lets users click a thumbnail and see a larger version in a popup overlay without leaving the page.

**Explanation:**
- CSS hides the modal by default (`display: none`) and shows it with a `.show` class
- The modal backdrop is a fixed, full-screen `rgba` black layer with a high `z-index`
- A small amount of JavaScript swaps the correct image into the modal, toggles the show class, and drives a close (X) button plus caption
- A `@keyframes` zoom animation makes the modal content scale up smoothly when it appears

**Example:**
```css
.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.8);
  align-items: center;
  justify-content: center;
}

.modal.show {
  display: flex;
  opacity: 1;
}
```

The backdrop fills the viewport and stays hidden until JavaScript adds `.show`, at which point it becomes a flex-centered popup over the page.

---

## 140. CSS Image Centering
**Definition:** CSS offers several ways to center an image horizontally, vertically, or both, depending on whether you use margin auto, flexbox, or grid.

**Explanation:**
- `<img>` is inline by default, so `margin: auto` has no effect until you set `display: block`
- With `display: block; margin: auto; width: 50%;` the image sits centered horizontally in its parent
- Flexbox on the parent (`display: flex; justify-content: center;`) centers horizontally; adding `align-items: center` also centers vertically
- Grid achieves both axes in one step with `place-items: center`
- In every case the image width must be smaller than the container, or there is nothing to center

**Example:**
```css
div {
  display: grid;
  place-items: center;
  height: 600px;
  border: 1px solid black;
}

img {
  width: 50%;
}
```

A fixed-height grid container centers its child image on both axes with a single `place-items` declaration.

---

## 141. CSS Image Filters
**Definition:** The `filter` property applies visual effects — blur, brightness, contrast, shadow, grayscale, hue rotation, inversion, opacity, saturation, and sepia — to any element, most commonly images.

**Explanation:**
- Each effect is a dedicated function: `blur()`, `brightness()`, `contrast()`, `drop-shadow()`, `grayscale()`, `hue-rotate()`, `invert()`, `opacity()`, `saturate()`, `sepia()`
- Most percentage-based functions treat `100%` as the original; values above lighten/boost, values below reduce
- `blur()` takes a length (e.g. `2px`); larger values mean more blur, and omitting the value means no effect
- `grayscale(1)`, `invert(1)`, and `sepia(1)` apply the full effect; intermediate values like `0.4` or `60%` produce partial results
- `hue-rotate()` takes an angle in degrees around the color wheel — positive shifts one way, negative the other, `0deg` is unchanged
- `drop-shadow()` uses the same offset-blur-color syntax as `box-shadow` but follows the image's actual shape

**Example:**
```css
#img1 {
  filter: blur(2px);
}

#img2 {
  filter: brightness(150%) contrast(150%);
}

#img3 {
  filter: grayscale(1);
}
```

The first image is lightly blurred, the second is brighter and more contrasty, and the third is fully desaturated to black-and-white.

---

## 142. CSS Image Shapes
**Definition:** `clip-path` cuts an image into basic shapes like circles, ellipses, and polygons; `shape-outside` controls how text wraps around a floated, clipped image.

**Explanation:**
- `clip-path: circle(50%)` clips to a circle centered on the image; add `at right` (or another keyword/coordinate) to move the center
- `ellipse()` takes two radii (x and y): `ellipse(50% 35%)` is wider than it is tall
- `polygon()` takes a list of x/y point pairs — `polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%)` makes a diamond
- `shape-outside` works with the same shape functions but affects surrounding inline content instead of the element itself
- Float the clipped image left, then set a slightly larger `shape-outside` radius so text curves around it with a little breathing room

**Example:**
```css
img {
  float: left;
  clip-path: circle(40%);
  shape-outside: circle(45%);
}
```

The image is clipped to a 40% circle while text wraps around a 45% circular boundary, creating a small gap between image and text.

---

## 143. CSS object-fit
**Definition:** `object-fit` tells an `<img>` or `<video>` how to resize itself inside a fixed-size container while controlling aspect ratio and cropping.

**Explanation:**
- `fill` (default) stretches or squashes the media to fill the box, ignoring aspect ratio
- `cover` preserves aspect ratio and fills the box, cropping whatever overflows
- `contain` preserves aspect ratio and fits entirely inside, leaving empty space if needed
- `none` displays the media at its natural size with no resizing
- `scale-down` picks the smaller of `none` or `contain` — never enlarges past natural size
- Works together with `object-position` to choose which part of the media is visible when cropping occurs

**Example:**
```css
.image-container {
  width: 200px;
  height: 300px;
  border: 1px solid black;
}

.image-container img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
```

The image fills the 200×300 box completely, keeping its proportions and clipping the edges that stick out.

---

## 144. CSS object-position
**Definition:** `object-position` works with `object-fit` to decide which part of an image or video stays visible inside its container, using x/y coordinates.

**Explanation:**
- First value is the x-axis, second is the y-axis
- Values can be keywords (`left`, `center`, `right`), lengths (`px`), percentages, or negative numbers
- Especially useful with `object-fit: cover`, where cropping is inevitable — object-position chooses what gets cut
- The default is `50% 50%` (center)
- Moving the position to `80% 100%` or `15% 100%` shifts focus to different parts of a wide photo inside a tall box

**Example:**
```css
.image-container {
  width: 200px;
  height: 300px;
  border: 1px solid black;
}

.image-container img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 80% 100%;
}
```

With cover cropping the sides, this position keeps the bottom-right area of the photo in view instead of the center.

---

## 145. CSS Masking
**Definition:** Masking places a mask layer over an element so parts of it are hidden — fully or partially — based on the mask image's transparency.

**Explanation:**
- `mask-image` accepts a PNG, SVG image, CSS gradient, or SVG `<mask>` element
- In the mask, black (or full transparency, depending on mode) hides the element; white/opaque areas reveal it
- `mask-repeat` controls tiling; `no-repeat` shows the mask once
- `mask-position` sets where the mask starts — default is top-left
- Related longhand properties include `mask-size`, `mask-clip`, `mask-origin`, `mask-composite`, and `mask-mode`
- Include the `-webkit-` prefixed version for broader browser support

**Example:**
```css
.mask1 {
  -webkit-mask-image: url(w3logo.png);
  mask-image: url(w3logo.png);
  mask-repeat: no-repeat;
  mask-position: center;
}
```

A single centered logo-shaped cutout reveals the underlying image through the logo's opaque regions only.

---

## 146. Masking - Gradients
**Definition:** CSS gradients can serve as mask layers, producing smooth fades and shaped cutouts without an external image file.

**Explanation:**
- A linear gradient from black to transparent fades the element out gradually from top to bottom
- Radial gradients can be circle- or ellipse-shaped; a hard stop at 50% creates a sharp circular cutout
- Conic gradients sweep around a center point — black at 0deg fading to transparent at 360deg masks in a clock-like pattern
- Combine a gradient mask with a background-image to fade a photo into the page
- Always pair the standard `mask-image` with the `-webkit-` prefixed form

**Example:**
```css
.mask1 {
  -webkit-mask-image: linear-gradient(black, transparent);
  mask-image: linear-gradient(black, transparent);
}
```

The element is fully visible at the top and fades to invisible at the bottom, like a dissolve effect.

---

## 147. Masking - SVG
**Definition:** An SVG `<mask>` element can define complex mask shapes — circles, ellipses, polygons, stars, multiple shapes — and apply them to an image via CSS or the SVG `mask` attribute.

**Explanation:**
- Define a `<mask id="...">` containing white shapes; the image's `mask="url(#id)"` attribute references it
- White fill reveals the image; areas outside the shapes stay hidden
- `<circle>` needs `r`, `cx`, `cy`; `<ellipse>` needs `cx`, `cy`, `rx`, `ry`; `<polygon>` takes a `points` list
- Multiple shapes inside one mask combine — three circles yield three circular windows onto the image
- Star and other custom polygons are just longer point lists on `<polygon>`

**Example:**
```html
<svg width="600" height="400" xmlns="http://www.w3.org/2000/svg">
  <mask id="svgmask1">
    <circle r="150" cx="200" cy="200" fill="#ffffff" />
  </mask>
  <image xmlns:xlink="http://www.w3.org/1999/xlink"
    xlink:href="img_5terre.jpg" mask="url(#svgmask1)"></image>
</svg>
```

Only the circular region defined by the mask is visible; everything outside it is cut away.

---

## 148. CSS Buttons
**Definition:** Buttons — whether `<button>`, `<input type="button">`, or a styled `<a>` — are shaped entirely with ordinary CSS properties like background, color, padding, and border-radius.

**Explanation:**
- Key properties: `background-color`, `color`, `border`, `padding`, `border-radius`, `box-shadow`, `text-align`, `font-size`, `text-decoration`, `cursor`
- A solid base style sets a fill color, removes the default border, sets white text, pads the interior, centers the label, and sets `cursor: pointer`
- `font-size` and `padding` together control the button's visual size
- `border-radius` rounds corners; `50%` produces a pill or circle depending on aspect
- Varying `border` style (solid, dotted, dashed) and color creates outline-button variants
- For `<a>` elements used as buttons, `text-decoration: none` removes the default underline

**Example:**
```css
.button {
  background-color: #04AA6D;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  cursor: pointer;
}
```

A clean, solid green button with comfortable padding and a pointer cursor — the starting point for most button variants.

---

## 149. Hover Effects
**Definition:** Button hover effects use the `:hover` pseudo-class, `transition-duration` for smoothness, `box-shadow` for depth, `opacity` for a disabled look, and `width` for fixed sizing.

**Explanation:**
- `:hover` changes background, color, or shadow when the pointer is over the button
- `transition-duration: 0.4s` (on the base class) makes the color change animate instead of snapping
- `box-shadow` adds a drop shadow — apply it always or only on `:hover` for a lift effect
- `opacity: 0.6` combined with `cursor: not-allowed` fakes a disabled button
- `width` overrides the default text-driven size: pixels for a fixed width, percentages for responsive width

**Example:**
```css
.button {
  transition-duration: 0.4s;
}

.button:hover {
  background-color: #4CAF50;
  color: white;
}

.disabledbtn {
  opacity: 0.6;
  cursor: not-allowed;
}
```

The first rule smoothly turns the button green on hover; the second dims a button and shows the forbidden cursor to signal it is disabled.

---

## 150. Button Groups
**Definition:** Button groups arrange multiple buttons in a row or column using flexbox on a wrapper element, with optional shared borders and hover styling.

**Explanation:**
- Wrap buttons in a `<div>` and set `display: flex` on the wrapper for a horizontal group
- Add `flex-wrap: wrap` so buttons drop to a new line on narrow screens
- For a vertical group, use `display: flex; flex-direction: column;`
- A bordered look uses `border` on each button plus `.btn-group .button:not(:last-child) { border-right: none; }` to collapse shared edges
- Scope hover styles to the group with `.btn-group .button:hover` so only group members change color

**Example:**
```css
.btn-group {
  display: flex;
  flex-wrap: wrap;
}

.btn-group .button {
  background-color: #04AA6D;
  border: none;
  color: white;
  padding: 15px 32px;
  cursor: pointer;
}

.btn-group .button:hover {
  background-color: dodgerblue;
}
```

Buttons sit side by side, wrap when space runs out, and each one turns blue on hover.

---

## 151. CSS Pagination
**Definition:** Pagination is a horizontal series of page-number links — usually an unordered list of `<a>` elements with prev/next controls — styled with flexbox.

**Explanation:**
- Structure: a `<ul class="pagination">` with `<li><a>` items per page number plus « and » prev/next controls
- The container uses `display: flex; justify-content: center; list-style: none; padding: 0` to center the row and remove bullets
- Each link uses `display: block` so it fills the `<li>`, then padding, border, margin, and `border-radius` for the chip look
- `.active` highlights the current page; `.disabled` grays out prev/next at the ends with `pointer-events: none`

**Example:**
```css
.pagination {
  display: flex;
  justify-content: center;
  list-style: none;
  padding: 0;
}

.pagination li a {
  display: block;
  padding: 8px 12px;
  text-decoration: none;
  border: 1px solid gray;
  margin: 0 4px;
  border-radius: 5px;
}

.pagination li a.active {
  background-color: #4CAF50;
  color: white;
}
```

A centered row of bordered page chips with the active page filled green.

---

## 152. Pagination Styles
**Definition:** Advanced pagination styling adds hover feedback, smooth transitions, and an alternative breadcrumb trail for hierarchical navigation.

**Explanation:**
- `:hover:not(.active)` changes the background of page links on hover without disturbing the active chip; `transition: background-color 1s` fades that change in
- Breadcrumbs are a horizontal list of section links (`list-style: none`, light background, `display: inline` items); `li + li:before` injects a `/` separator via `content`

**Example:**
```css
.pagination li a {
  transition: background-color 1s;
}

.pagination li a:hover:not(.active) {
  background-color: lightgray;
}

ul.breadcrumb {
  list-style: none;
  background-color: #eee;
}

ul.breadcrumb li {
  display: inline;
}

ul.breadcrumb li + li:before {
  color: black;
  content: "/\00a0";
}
```

Page links fade to lightgray on hover (except the active one); breadcrumbs render as a gray strip with slash separators.

---

## 153. CSS Multiple Columns
**Definition:** The multi-column layout module splits an element's text into newspaper-style columns using `column-count` and `column-gap`.

**Explanation:**
- `column-count: 3` divides the content into exactly three columns regardless of width
- `column-gap: 40px` sets the space between columns
- Related properties: `column-width` (suggested minimum width per column), `columns` (shorthand for width + count), `column-fill`, and the `column-rule-*` family
- The browser adjusts flow so text is balanced across the available columns
- Column rules and spanning are covered in the next section

**Example:**
```css
div {
  column-count: 3;
  column-gap: 40px;
}
```

The paragraph text is redistributed into three equal columns with a 40-pixel gutter between each.

---

## 154. Multiple Column Rules
**Definition:** Column rules are the vertical lines between multi-column text; `column-span` lets an element (like a heading) cross all columns, and `column-width` suggests a preferred column size.

**Explanation:**
- `column-rule-style`, `column-rule-width`, and `column-rule-color` control the divider's appearance individually
- `column-rule` is the shorthand combining all three — same syntax as `border`
- `column-span: all` stretches an element across every column, useful for section headings
- `column-width: 100px` tells the browser the optimal column width; the actual column count is derived from available space
- Combining `column-width` with `column-count` sets both a minimum width and a maximum number of columns

**Example:**
```css
div {
  column-rule: 1px solid lightblue;
  column-width: 100px;
}

h2 {
  column-span: all;
  text-align: center;
}
```

A light blue rule runs between columns sized around 100 pixels wide, while the heading stretches across the full layout.

---

## 155. CSS User Interface
**Definition:** The user-interface properties `resize` and `outline-offset` control whether users can drag-resize an element and how far its focus outline sits from its border.

**Explanation:**
- `resize` accepts `horizontal`, `vertical`, `both`, or `none`
- `resize` only takes effect when `overflow` is not `visible` — pair it with `overflow: auto`
- `<textarea>` is resizable by default; `resize: none` disables that
- `outline-offset` adds transparent space between an element's border and its outline; positive values push the outline outward
- Unlike borders, outlines do not affect the element's layout dimensions and may overlap neighboring content

**Example:**
```css
div.ex1 {
  margin: 20px;
  border: 1px solid black;
  outline: 4px solid red;
  outline-offset: 15px;
}

textarea {
  resize: none;
}
```

The div shows a red outline floating 15 pixels outside its border; the textarea can no longer be dragged to resize.

---

## 156. CSS Variables
**Definition:** CSS variables (custom properties) store reusable values — typically colors or sizes — that can be declared globally or locally and inserted anywhere with `var()`.

**Explanation:**
- Names must start with `--` and are case-sensitive
- Global variables live in `:root`; local variables live inside the selector that uses them
- `var(--name)` inserts the value; `var(--name, fallback)` uses the fallback if the variable is not found
- Centralizing colors in variables means one edit re-themes the whole page
- Variables are part of the DOM: JavaScript can change them, and media queries can override them
- Benefits: easier maintenance, clearer code, and consistent theming

**Example:**
```css
:root {
  --primary-bg-color: #1e90ff;
  --primary-color: #ffffff;
}

body {
  background-color: var(--primary-bg-color);
}

.container {
  color: var(--primary-bg-color);
  background-color: var(--primary-color);
  padding: 15px;
}
```

Two global color variables drive the page background and the container's text/background; changing the variable values re-themes everything at once.

---

## 157. Overriding Variables
**Definition:** A local variable declaration inside a selector overrides a global variable of the same name for that selector and its descendants, letting one section of the page use different values.

**Explanation:**
- Re-declaring `--primary-bg-color: red` inside `.note` makes every `var(--primary-bg-color)` in `.note` resolve to red, while the rest of the page keeps the global value
- Alternatively, introduce a brand-new local variable (e.g. `--note-border-color`) when only one place needs a unique value — clearer than shadowing
- Overriding follows normal cascade rules: the closest matching declaration wins
- This pattern is ideal for accents, callout boxes, or themed sub-sections without touching global defaults

**Example:**
```css
:root {
  --primary-bg-color: #1e90ff;
}

.container .note {
  --primary-bg-color: red; /* local override */
  border: 1px solid var(--primary-bg-color);
  padding: 10px;
}
```

Only the `.note` border turns red; every other use of `--primary-bg-color` on the page stays blue.

---

## 158. Variables in MQ
**Definition:** Media queries can reassign CSS variable values at different viewport widths, letting a single `var()` reference adapt responsively without duplicating full style rules.

**Explanation:**
- Declare a local variable (e.g. `--fontsize: 20px`) on the element that uses it
- Inside `@media screen and (min-width: 450px)`, re-declare the same variable with a new value (e.g. `40px`)
- Global variables on `:root` can also be swapped inside a media query — for example changing `--primary-bg-color` on wider screens
- Because every `var()` reference updates automatically, one variable change restyles all its consumers at that breakpoint
- This keeps responsive styling centralized instead of repeating full property blocks per breakpoint

**Example:**
```css
.container {
  --fontsize: 20px;
  font-size: var(--fontsize);
}

@media screen and (min-width: 450px) {
  .container {
    --fontsize: 40px;
  }
}
```

Text starts at 20px and jumps to 40px once the viewport reaches 450px, driven entirely by reassigning one variable.

---

## 159. CSS @property
**Definition:** The `@property` at-rule registers a custom CSS property in the stylesheet with a declared syntax type, inheritance flag, and initial value — no JavaScript required.

**Explanation:**
- Required descriptors: `syntax` (e.g. `"<color>"`, `"<number>"`, `"<length>"`), `inherits` (`true`/`false`), and `initial-value`
- Type checking rejects invalid assignments and falls back to `initial-value` — assigning the number `2` to a `<color>` property uses the default instead of breaking
- `inherits: true` lets descendants pick up the value; `false` isolates it to the declaring element
- Registered properties can be animated smoothly, including gradient color stops that previously could not transition
- Usage with `var()` is identical to ordinary custom properties once registered

**Example:**
```css
@property --my-bg-color {
  syntax: "<color>";
  inherits: true;
  initial-value: lightgray;
}

div {
  width: 300px;
  height: 150px;
  padding: 15px;
  background-color: var(--my-bg-color);
}
```

The custom property is typed as a color, inherits by default, and falls back to lightgray if something invalid is assigned.

---

## 160. CSS Box Sizing
**Definition:** `box-sizing` controls whether an element's declared width/height include its padding and border, solving the classic "element is bigger than I asked" problem.

**Explanation:**
- Default (`content-box`): actual size = width + padding + border, so a 300px div with 50px padding is 400px wide
- `border-box` folds padding and border into the declared width/height — what you write is what you get
- Two divs with the same `width` and `height` but different padding end up different sizes under `content-box`, identical under `border-box`
- Applying `* { box-sizing: border-box; }` globally is a widely adopted, safe reset
- Many form controls already default to `border-box`, which is why inputs and textareas can look inconsistent with plain divs at `width: 100%`

**Example:**
```css
* {
  box-sizing: border-box;
}

.div2 {
  width: 300px;
  height: 100px;
  padding: 50px;
  border: 1px solid red;
  box-sizing: border-box;
}
```

With border-box, the div's total footprint stays 300×100 no matter how much padding or border is added inside.

---

## 161. CSS Functions
**Definition:** CSS functions compute or supply property values inline — calculations, variable lookups, colors, flexible sizing, resource URLs, attribute content, and transforms.

**Explanation:**
- `calc()` does arithmetic and mixes units: `calc(100% - 150px)` leaves room for a sidebar
- `var()` inserts a custom property; a fallback second argument covers missing variables
- `rgb()` and `hsl()` define colors; both accept an optional alpha after a slash (e.g. `rgb(255 0 0 / 0.3)`)
- `min()`, `max()`, and `clamp()` pick among values for responsive sizing — `clamp(1rem, 2.5vw, 2rem)` tracks viewport width within bounds
- `url()` loads external resources like images and fonts
- `attr()` pulls an HTML attribute value into `content`
- Transform helpers: `rotate()` turns, `scale()` resizes, `perspective()` adds a 3D depth context

**Example:**
```css
.container {
  width: calc(100% - 150px);
}

div {
  font-size: clamp(1rem, 2.5vw, 2rem);
}

img:hover {
  transform: scale(1.1);
}
```

The container always leaves 150px free, font size tracks the viewport between 1rem and 2rem, and the image grows 10% on hover.

---

## 162. CSS Media Queries
**Definition:** Media queries apply styles conditionally based on device or environment characteristics — viewport width, height, orientation, resolution, and color-scheme preference — and are the foundation of responsive design.

**Explanation:**
- The `@media` rule wraps conditional style blocks; the query is true only when the media type matches and all features evaluate true
- Media types: `all` (default if omitted), `print`, `screen`
- `not` inverts the entire query; `and` combines a type with one or more features
- Common features: `min-width`, `max-width`, `width`, `min-height`, `max-height`, `height`, `orientation`, `resolution`, `prefers-color-scheme`
- Range checks like `min-width: 480px` fire on wider screens; combining `min-width` and `max-width` targets a band (e.g. 480px–768px)
- Rules inside a true query cascade normally, overriding earlier non-matching styles

**Example:**
```css
@media screen and (min-width: 480px) {
  body {
    background-color: lightgreen;
  }
}

@media screen and (min-width: 480px) and (max-width: 768px) {
  body {
    background-color: lightgreen;
  }
}
```

The first block turns the background green on any screen 480px or wider; the second restricts the same change to the 480–768px band only.

---

## 163. Media Query Examples
**Definition:** A set of common recipes that use `@media` rules to restyle a page at different viewport sizes, orientations, and user preferences.

**Explanation:**
- Mobile-first pattern: plain CSS targets small screens; each `@media (min-width: ...)` block upgrades the layout at wider widths (768px, 992px in the source examples)
- Column layouts: flex items at `flex: 25%` (four columns) drop to `50%` (two columns) under 992px, then stack with `flex-direction: column` under 600px
- Navigation menus switch from a horizontal row to a vertical stack under a `max-width` query
- Elements can be hidden (`display: none`) or resized (font-size) per breakpoint
- `orientation: landscape` reacts to how the device is held; `prefers-reduced-motion: reduce` disables animations for users who asked for less motion

**Example:**
```css
.container { display: flex; flex-wrap: wrap; }
.column { flex: 25%; padding: 20px; }

@media screen and (max-width: 992px) {
  .column { flex: 50%; }
}
@media screen and (max-width: 600px) {
  .container { flex-direction: column; }
}
```

Four equal columns collapse to two, then stack vertically as the viewport shrinks.

---

## 164. CSS Flexbox
**Definition:** Flexbox (Flexible Box Layout) is a CSS layout model for arranging items along one axis — a row or a column — in a flexible, responsive way.

**Explanation:**
- Setting `display: flex` (or `inline-flex`) on a parent turns it into a **flex container**
- Its direct children automatically become **flex items**
- `flex-direction` chooses the axis: `row` (default) or `column`, each with a reverse variant
- Flexbox solves layout problems that used to need `float` or positioning
- Flexbox handles **one** dimension (rows OR columns); CSS Grid handles **two** (rows AND columns)

**Example:**
```html
<style>
.container { display: flex; background-color: DodgerBlue; }
.container div { background-color: #f1f1f1; margin: 10px; padding: 20px; font-size: 30px; }
</style>

<div class="container">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

The three divs line up horizontally inside the blue flex container.

---

## 165. Flex Container
**Definition:** The flex container is the parent element with `display: flex` or `inline-flex`; its properties control how all flex items are laid out.

**Explanation:**
- Container properties: `display`, `flex-direction`, `flex-wrap`, `flex-flow`, `justify-content`, `align-items`, `align-content`
- `flex-direction`: `row` (default), `column`, `row-reverse`, `column-reverse`
- `flex-wrap`: `nowrap` (default — everything on one line), `wrap`, `wrap-reverse`
- `flex-flow` is the shorthand combining `flex-direction` and `flex-wrap` (for example `row wrap`)

**Example:**
```css
.flex-container {
  display: flex;
  flex-flow: row wrap;
}
```

Items flow left to right and wrap onto new lines when space runs out.

---

## 166. Flexbox justify-content
**Definition:** The `justify-content` property aligns flex items along the main axis (horizontally in a row layout) when they do not fill the container.

**Explanation:**
- Values: `flex-start` (default), `center`, `flex-end`, `space-between`, `space-around`, `space-evenly`
- `flex-start` / `flex-end` pack items against the start or end edge
- `center` clusters the items in the middle
- `space-between` puts equal gaps between items, flush at both ends
- `space-around` gives each item equal space on both sides; `space-evenly` makes every gap identical

**Example:**
```css
.flex-container {
  display: flex;
  justify-content: space-between;
}
```

Items spread across the row with equal gaps between them and no gap at the outer edges.

---

## 167. Flexbox Alignment
**Definition:** `align-items` aligns flex items on the cross axis (vertically in a row layout), `align-content` aligns the wrapped lines themselves, and setting both axes to `center` produces true centering.

**Explanation:**
- `align-items` values: `normal` (default), `stretch`, `center`, `flex-start`, `flex-end`, `baseline`
- The container needs a height (for example `height: 200px`) for vertical alignment to be visible
- `align-content` only takes effect when items wrap onto multiple lines; values include `stretch` (default), `center`, `flex-start`, `flex-end`, `space-between`, `space-around`, `space-evenly`
- True centering: set both `justify-content: center` and `align-items: center` on the container

**Example:**
```css
.flex-container {
  display: flex;
  height: 400px;
  justify-content: center;
  align-items: center;
}
```

The flex item sits perfectly centered, horizontally and vertically.

---

## 168. Flex Items
**Definition:** Flex items are the direct children of a flex container; item-level properties control their size, order, and individual alignment.

**Explanation:**
- `order`: display order as a number, default `0` — source order does not have to match visual order
- `flex-grow`: how much the item grows relative to its siblings, default `0`
- `flex-shrink`: how much it shrinks when space is tight, default `1`
- `flex-basis`: the item's initial length before growing or shrinking
- `flex`: shorthand for `flex-grow`, `flex-shrink`, `flex-basis` (for example `1 0 150px`)
- `align-self`: overrides the container's `align-items` for this one item

**Example:**
```html
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div style="flex: 1 0 150px">3</div>
  <div>4</div>
</div>
```

Item 3 starts at 150px, never shrinks, and grows to absorb leftover space.

---

## 169. Responsive Flexbox
**Definition:** Combining media queries with flexbox so the layout rearranges itself at chosen breakpoints.

**Explanation:**
- One approach: keep `flex-direction: row` by default, then switch to `column` inside `@media (max-width: 600px)` to stack a three-column page into one column on phones
- Another approach: give each item a percentage `flex` value (for example `33.3%`), then raise it to `100%` at the breakpoint
- The percentage approach needs `flex-wrap: wrap` on the container so items can fall to new lines
- Both techniques change only the breakpoint rules — the base CSS stays the same

**Example:**
```css
.flex-container { display: flex; flex-direction: row; }
.flex-item { background-color: #f1f1f1; padding: 10px; font-size: 30px; text-align: center; width: 100%; }

@media (max-width: 600px) {
  .flex-container { flex-direction: column; }
}
```

Three columns on wide screens become a single stacked column below 600px.

---

## 170. CSS Grid Layout
**Definition:** The Grid Layout Module is a two-dimensional CSS layout system with both rows and columns.

**Explanation:**
- Setting `display: grid` (or `inline-grid`) on a parent creates a **grid container**
- Direct children automatically become **grid items**
- Grid covers rows AND columns at once; Flexbox covers rows OR columns
- Grid replaces hand-rolled `float` and positioning for page-level structure

**Example:**
```html
<style>
.container { display: grid; grid-template-columns: auto auto auto; background-color: dodgerblue; padding: 10px; }
.container div { background-color: #f1f1f1; border: 1px solid black; padding: 10px; font-size: 30px; text-align: center; }
</style>

<div class="container">
  <div>1</div><div>2</div><div>3</div>
  <div>4</div><div>5</div>
</div>
```

Five items fill a three-column grid; the fifth wraps onto a new row automatically.

---

## 171. Grid Container
**Definition:** A grid container is the element whose `display` is set to `grid` or `inline-grid`; it holds one or more grid items arranged in columns and rows.

**Explanation:**
- All direct children automatically become grid items
- `grid` takes a full block-level row; `inline-grid` sizes to its content and sits inline
- Container properties: `grid-template-columns`, `grid-template-rows`, `grid-template-areas`, `grid-auto-flow`, `grid-auto-columns`, `grid-auto-rows`, `gap` / `row-gap` / `column-gap`, `justify-content`, `align-content`, `justify-items`, `align-items`, `place-content`, and the `grid` shorthand

**Example:**
```css
.container {
  display: grid;
  grid-template-columns: auto auto auto;
}
```

A block-level grid with three auto-sized columns.

---

## 172. Grid Tracks
**Definition:** Grid tracks are the rows and columns of a grid, declared on the container with `grid-template-columns`, `grid-template-rows`, and `grid-template-areas`.

**Explanation:**
- `grid-template-columns` takes a space-separated list, one width per column: fixed lengths (`80px 200px`), percentages, `fr` units, `auto`, `repeat()`, `minmax()`
- `fr` means "fraction of the leftover space": `1fr 2fr 1fr` gives the middle column twice the share
- `repeat(3, 1fr)` is shorthand for `1fr 1fr 1fr`; `minmax(80px, 1fr)` clamps a track between a floor and a ceiling
- Items beyond the defined tracks automatically create extra rows
- `grid-template-rows` works the same way for heights and also accepts `min-content`, `max-content`, and `fit-content()`; undeclared rows default to `auto`

**Example:**
```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

Three equal-width fluid columns.

---

## 173. Grid Gaps
**Definition:** Gaps (gutters) are the spaces between grid rows and columns — never along the outer edges of the container.

**Explanation:**
- `column-gap` sets the space between columns; `row-gap` sets it between rows
- `gap` is the shorthand for both
- One `gap` value applies to rows and columns; two values mean `row-gap column-gap`
- The default is `0` — items sit flush until you add a gap

**Example:**
```css
.container {
  display: grid;
  gap: 30px 100px;
}
```

Rows are separated by 30px and columns by 100px.

---

## 174. Aligning Grid Content
**Definition:** `justify-content` and `align-content` position the whole grid inside its container when the tracks do not fill it; `place-content` sets both at once.

**Explanation:**
- `justify-content` works horizontally, `align-content` vertically — both accept `start`, `end`, `center`, `space-between`, `space-around`, `space-evenly`
- They only have an effect when the grid's total size is smaller than the container in that axis
- `place-content` with two values reads `align-content justify-content`; with one value it sets both
- The demos use fixed-height containers (for example `height: 300px`) so vertical alignment is visible

**Example:**
```css
.container {
  display: grid;
  height: 300px;
  place-content: center;
}
```

The entire grid is centered horizontally and vertically inside the container.

---

## 175. Grid Items
**Definition:** Grid items are the direct children of a grid container, placed on the grid's numbered column-lines and row-lines, and able to span multiple tracks.

**Explanation:**
- Lines between columns are column-lines; lines between rows are row-lines; both are numbered starting at `1`
- `grid-column-start` / `grid-column-end` pin an item between two column-lines
- `grid-row-start` / `grid-row-end` do the same for rows
- `grid-column` and `grid-row` are the shorthands; `1 / span 2` starts at line 1 and spans two tracks
- An item can span both axes at once by combining the two shorthands

**Example:**
```css
.item1 {
  grid-column: 1 / span 2;
  grid-row: 1 / span 2;
}
```

The item covers a 2×2 block of cells in the top-left corner.

---

## 176. Naming Grid Items
**Definition:** `grid-template-areas` draws a named map of the grid on the container, and each item claims a region of that map with its `grid-area` property.

**Explanation:**
- Each row of the map is one string of names inside apostrophes; names separated by spaces line up as columns
- Repeating a name across cells makes that item span them
- A period (`.`) marks a cell with no named item
- One quoted string per row — more strings mean more rows
- A common result is a full page template: header, menu, main, right column, footer

**Example:**
```css
.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item5 { grid-area: footer; }

.container {
  display: grid;
  grid-template-areas:
    'header header header header'
    'menu main main right'
    'menu footer footer footer';
}
```

A classic page skeleton: full-width header, sidebar menu, main content, and footer.

---

## 177. Grid Item Alignment
**Definition:** `justify-self` and `align-self` align a single grid item inside its own cell — horizontally (inline direction) and vertically (block direction); `place-self` is their shorthand.

**Explanation:**
- `justify-self` values: `auto` (default), `normal`, `stretch`, `start`, `left`, `center`, `end`, `right`
- `align-self` values: `auto` (default), `normal`, `stretch`, `start`, `center`, `end`
- Alignment only shows when the item is smaller than its cell — leftover space is what gets aligned
- On the container, `justify-items` and `align-items` set the default for every item; per-item `*-self` overrides it
- In English pages the inline direction is left-to-right and the block direction is top-to-bottom

**Example:**
```css
.item1 { justify-self: right; }
.item6 { align-self: center; }
```

Item 1 hugs the right edge of its cell; item 6 is vertically centered in its cell.

---

## 178. Grid Item Order
**Definition:** The `order` property renumbers the visual order of grid items so the first item in the HTML does not have to appear first on screen.

**Explanation:**
- `order` takes a number; the default is `0`
- Lower numbers are placed first; higher numbers come later
- **Note:** `order` changes only the visual arrangement — the DOM order stays the same, so screen readers still announce elements in source order

**Example:**
```css
.item1 { order: 3; }
.item2 { order: 6; }
.item3 { order: 1; }
.item4 { order: 2; }
.item5 { order: 4; }
.item6 { order: 5; }
```

Item 3 appears first on screen even though it is third in the HTML.

---

## 179. 12-Column Grid Layout
**Definition:** A 12-column grid splits the page width into twelve equal tracks, the most common foundation for flexible, responsive page layouts.

**Explanation:**
- Twelve divides evenly into halves, thirds, and quarters (6+6, 4+4+4, 3+3+3+3), which is why it beats other counts
- `repeat(12, [col-start] 1fr)` creates twelve fluid columns and names every start line `col-start`
- Items are placed with `grid-column`: `span 3`, `col-start 4 / span 9`, or explicit start/end lines
- Mobile-first breakpoints re-place the items: full width under 576px, two-column at 576–767px, three-column at 768px and up

**Example:**
```css
.container {
  display: grid;
  grid-template-columns: repeat(12, [col-start] 1fr);
  gap: 20px;
}
.container > * { grid-column: col-start / span 12; }

@media (min-width: 768px) {
  .content { grid-column: col-start 3 / span 8; }
  .sidebar { grid-column: col-start 11 / span 2; }
}
```

Everything is full-width on phones; on wide screens the content and sidebar claim specific columns.

---

## 180. CSS @supports Rule
**Definition:** The `@supports` at-rule tests whether the browser understands a given CSS property/value pair, and only then applies the rules inside its block.

**Explanation:**
- Syntax: `@supports (property: value) { ... }` — the block runs when the feature is supported
- Put progressive enhancements inside `@supports`; keep the basic fallback styles outside, so older browsers still get a working layout
- `not` inverts the test: `@supports not (display: grid)` runs when grid is missing
- Multiple tests combine with `and` and `or`: `@supports (display: grid) and (gap: 10px)`

**Example:**
```css
.container { display: table; width: 90%; padding: 10px; }

@supports (display: grid) {
  .container {
    display: grid;
    grid-gap: 10px;
  }
}
```

Browsers without grid keep the table-based fallback; capable browsers upgrade to grid.

---

## 181. Responsive Web Design
**Definition:** Responsive web design (RWD) is the practice of building pages that resize, reflow, hide, or enlarge so they look good on every device — desktop, tablet, or phone.

**Explanation:**
- The layout adapts automatically to the viewport instead of shipping separate sites per device
- Three key components work together: the viewport `<meta>` tag, flexible layouts (grid and flexbox), and media queries
- The goal is the same content looking good and staying easy to use at any screen size

**Example:**
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

Every responsive page starts with this tag in `<head>`; flexible layouts and media queries build on top of it.

---

## 182. RWD - The Viewport
**Definition:** The viewport is the user's visible area of a page, and it varies wildly between devices — the `<meta name="viewport">` tag tells the browser how to size and scale it.

**Explanation:**
- `width=device-width` makes the page width follow the device's screen width
- `initial-scale=1.0` sets the zoom level to 1 when the page first loads
- Without this tag, mobile browsers assume a desktop width and shrink the whole page — or force horizontal scrolling
- Users scroll vertically, never horizontally: avoid fixed-width blocks wider than the viewport
- Content must not depend on one particular width; use relative widths (`width: 100%`) and media queries instead of large absolute widths or offsets

**Example:**
```html
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Page</title>
</head>
```

The standard head for a responsive page.

---

## 183. RWD - Grid View
**Definition:** A responsive grid view divides the page into rows and columns — typically 6 or 12 — that expand and shrink with the browser window.

**Explanation:**
- First set `* { box-sizing: border-box; }` so padding and borders count inside each element's width and height
- The sample layout is one grid container with five named areas stacked in a single column: header, menu, main, facts, footer
- `grid-template-areas` with one name per row is the mobile-first starting point; media queries later rearrange the areas
- Colors, gaps, and typography are cosmetic layers on top of the same structure

**Example:**
```css
* { box-sizing: border-box; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header'
    'menu'
    'main'
    'facts'
    'footer';
  gap: 10px;
}
.header { grid-area: header; background-color: purple; text-align: center; color: #ffffff; }
.footer { grid-area: footer; background-color: #0099cc; color: #ffffff; text-align: center; }
```

A single-column page skeleton that media queries will later promote to multi-column.

---

## 184. RWD - Media Queries
**Definition:** In responsive design, media queries apply different styles at different viewport widths (breakpoints) and also react to orientation and user preferences.

**Explanation:**
- Wrap breakpoint rules in `@media (min-width: ...)`; rearrange grid areas or flex layouts inside each block
- Add as many breakpoints as the design needs — a typical ladder is 600px, 768px, 992px, 1200px
- `orientation: landscape` / `portrait` reacts to how the device is held
- Small screens can hide elements (`display: none`) or scale type down; wide screens can scale it up
- `prefers-reduced-motion: reduce` turns off animations and transitions for users who requested less motion

**Example:**
```css
@media (min-width: 600px) {
  .header { grid-area: 1 / span 6; }
  .menu { grid-area: 2 / span 1; }
  .content { grid-area: 2 / span 4; }
}
@media (min-width: 768px) {
  .content { grid-area: 2 / span 6; }
  .sidebar { grid-area: 2 / span 1; }
}
```

Each breakpoint restyles the same grid items for more screen real estate.

---

## 185. RWD - Images
**Definition:** Responsive images scale with their container instead of overflowing it, using percentage widths on `<img>` elements, `background-size` on backgrounds, or the `<picture>` element for per-device files.

**Explanation:**
- `width: 100%; height: auto` lets an image grow beyond its original size as well as shrink
- `max-width: 100%; height: auto` shrinks when needed but never upscales past the natural size — usually the better choice
- Backgrounds: `background-size: contain` fits while keeping aspect ratio, `cover` fills and may crop, `100% 100%` stretches (distorts)
- Media queries can swap a small background image for a large one at a chosen width
- `<picture>` lists multiple `<source srcset=... media=...>` candidates; the browser picks the first match, and a fallback `<img>` covers browsers without `<picture>` support

**Example:**
```css
img {
  max-width: 100%;
  height: auto;
}
```

Images shrink to fit narrow viewports and stay at natural size on wide ones.

---

## 186. RWD - Videos
**Definition:** Video players become responsive with the same two-property pattern used for images.

**Explanation:**
- `width: 100%; height: auto` makes the player track the container width in both directions
- That rule can enlarge the player past its original size; `max-width: 100%` prevents that
- Either way `height: auto` keeps the video's aspect ratio

**Example:**
```css
video {
  max-width: 100%;
  height: auto;
}
```

The player fills its container on small screens and never upscales beyond its native size.

---

## 187. RWD - Frameworks
**Definition:** Free responsive CSS frameworks — such as W3.CSS and Bootstrap — ship prebuilt grids and utility classes so pages adapt without writing your own media queries.

**Explanation:**
- Both still need the viewport `<meta>` tag to behave correctly on phones
- W3.CSS: link its stylesheet, then combine classes like `w3-container`, `w3-row-padding`, and `w3-third` for equal columns
- Bootstrap 5: load the CSS (and optionally the JS bundle) from a CDN, then use `container`, `row`, and breakpoint columns such as `col-sm-4`
- Framework columns collapse and restack automatically at each framework's breakpoints

**Example:**
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<div class="w3-row-padding">
  <div class="w3-third"><h2>London</h2><p>Capital of England.</p></div>
  <div class="w3-third"><h2>Paris</h2><p>Capital of France.</p></div>
  <div class="w3-third"><h2>Tokyo</h2><p>Capital of Japan.</p></div>
</div>
```

Three equal columns that restack on small screens, driven entirely by framework classes.

---

## 188. RWD - Templates
**Definition:** Prebuilt responsive page templates based on the W3.CSS framework — complete starter pages you can modify and reuse.

**Explanation:**
- The templates are responsive out of the box because W3.CSS handles the breakpoints
- They are free to modify, save, share, and use in any project
- Each template already includes the viewport meta tag and the W3.CSS stylesheet link

**Example:**
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<div class="w3-container w3-blue">
  <h1>My Site</h1>
</div>
```

The skeleton every W3.CSS template starts from — swap in your own content and sections.

---

## 189. CSS Templates
**Definition:** Responsive starter templates written in plain CSS — ready-made page layouts you can drop into a project and adapt.

**Explanation:**
- They are starter files, not a framework: you own the CSS after you take them
- Each template is responsive, so the layout already adapts to different screen sizes
- They are free to modify, save, share, and use in any project

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Starter Template</title>
</head>
<body>
  <h1>Starter Template</h1>
</body>
</html>
```

The baseline page a CSS template ships as — head boilerplate included, layout and styles ready to expand.

---

*Source topics: W3Schools HTML/CSS tutorials. Notes reworded; identifiers (tags, properties, values) kept exact.*
