# HTML — Complete Study Notes

Definition, explanation, and a short runnable example for every topic in the W3Schools HTML tutorial (74 topics). Prose is rewritten for clarity; all examples are self-contained snippets.

## Contents

- [1. HTML HOME](#1-html-home)
- [2. HTML Introduction](#2-html-introduction)
- [3. HTML Editors](#3-html-editors)
- [4. HTML Basic](#4-html-basic)
- [5. HTML Elements](#5-html-elements)
- [6. HTML Attributes](#6-html-attributes)
- [7. HTML Headings](#7-html-headings)
- [8. HTML Paragraphs](#8-html-paragraphs)
- [9. HTML Styles](#9-html-styles)
- [10. HTML Formatting](#10-html-formatting)
- [11. HTML Quotations](#11-html-quotations)
- [12. HTML Comments](#12-html-comments)
- [13. HTML CSS](#13-html-css)
- [14. HTML Links](#14-html-links)
- [15. Link Bookmarks](#15-link-bookmarks)
- [16. HTML Images](#16-html-images)
- [17. Image Map](#17-image-map)
- [18. Background Images](#18-background-images)
- [19. The Picture Element](#19-the-picture-element)
- [20. HTML Favicon](#20-html-favicon)
- [21. HTML Page Title](#21-html-page-title)
- [22. HTML Tables](#22-html-tables)
- [23. Table Borders](#23-table-borders)
- [24. Table Sizes](#24-table-sizes)
- [25. Table Headers](#25-table-headers)
- [26. Padding & Spacing](#26-padding-&-spacing)
- [27. Colspan & Rowspan](#27-colspan-&-rowspan)
- [28. Table Styling](#28-table-styling)
- [29. Table Colgroup](#29-table-colgroup)
- [30. HTML Lists](#30-html-lists)
- [31. Unordered Lists](#31-unordered-lists)
- [32. Ordered Lists](#32-ordered-lists)
- [33. Other Lists](#33-other-lists)
- [34. Block & Inline](#34-block-&-inline)
- [35. Div](#35-div)
- [36. Classes](#36-classes)
- [37. Id](#37-id)
- [38. Buttons](#38-buttons)
- [39. Iframes](#39-iframes)
- [40. HTML JavaScript](#40-html-javascript)
- [41. File Paths](#41-file-paths)
- [42. HTML Head](#42-html-head)
- [43. HTML Layout](#43-html-layout)
- [44. HTML Responsive](#44-html-responsive)
- [45. Computercode](#45-computercode)
- [46. HTML Semantics](#46-html-semantics)
- [47. HTML Style Guide](#47-html-style-guide)
- [48. HTML Entities](#48-html-entities)
- [49. HTML Symbols](#49-html-symbols)
- [50. HTML Emojis](#50-html-emojis)
- [51. HTML Charsets](#51-html-charsets)
- [52. HTML URL Encode](#52-html-url-encode)
- [53. HTML vs. XHTML](#53-html-vs-xhtml)
- [54. HTML Forms](#54-html-forms)
- [55. HTML Form Attributes](#55-html-form-attributes)
- [56. HTML Form Elements](#56-html-form-elements)
- [57. HTML Input Types](#57-html-input-types)
- [58. HTML Input Attributes](#58-html-input-attributes)
- [59. Input Form Attributes](#59-input-form-attributes)
- [60. HTML Canvas](#60-html-canvas)
- [61. HTML SVG](#61-html-svg)
- [62. HTML Media](#62-html-media)
- [63. HTML Video](#63-html-video)
- [64. HTML Audio](#64-html-audio)
- [65. HTML Plug-ins](#65-html-plug-ins)
- [66. HTML YouTube](#66-html-youtube)
- [67. Web APIs](#67-web-apis)
- [68. Geolocation API](#68-geolocation-api)
- [69. Drag and Drop API](#69-drag-and-drop-api)
- [70. Popover API](#70-popover-api)
- [71. Web Storage API](#71-web-storage-api)
- [72. Web Workers API](#72-web-workers-api)
- [73. Server-Sent Events API](#73-server-sent-events-api)
- [74. HTML Accessibility](#74-html-accessibility)

---

## 1. HTML HOME
**Definition:** HTML is the standard markup language used to build web pages, and with it you can create a website of your own.

**Explanation:**
- Every web page is a plain-text file written in HTML
- The fastest way to learn is by reading a short explanation, then typing and running the matching example
- Each chapter pairs its text with editable example code so you can change it and watch the result
- Chapters end with exercises and a quiz to test what stuck
- Complete references for tags, attributes, events, colors, and encodings are available for later lookup

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>

  <h1>This is a Heading</h1>
  <p>This is a paragraph.</p>

</body>
</html>
```
A minimal page: a title in the tab, one heading, and one paragraph — the skeleton every HTML document follows.

---

## 2. HTML Introduction
**Definition:** HTML (HyperText Markup Language) is the standard markup language for structuring the content of a web page.

**Explanation:**
- HTML describes a page's structure as a tree of **elements**
- An element usually has a start tag, content, and an end tag: `<tag>content</tag>`
- Elements label content — a heading, a paragraph, a link — so the browser knows how to display it
- Some elements are **empty** and have no end tag (for example `<br>` for a line break)
- Browsers read HTML files and render them as visible web pages

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>

</body>
</html>
```

`<!DOCTYPE html>` marks an HTML5 document. `<head>` holds meta info (like the title), `<body>` holds everything visible on the page.

---

## 3. HTML Editors
**Definition:** An HTML editor is any program that can create and edit plain-text files — for learning, a basic text editor such as Notepad (Windows) or TextEdit (macOS) is enough.

**Explanation:**
- Professional HTML editors exist, but a plain text editor keeps the focus on the markup itself
- Write or paste the HTML into a new document
- Save the file with a `.htm` or `.html` extension — the two are interchangeable — using **UTF-8** encoding; `index.htm` is the conventional name for a site's front page
- Open the saved file in any browser (double-click it, or right-click and choose "Open with")
- **Note:** TextEdit on macOS must be switched to **Plain Text** under Preferences → Format first, otherwise it saves rich text instead of raw markup

**Example:**
```html
<!DOCTYPE html>
<html>
<body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>

</body>
</html>
```
Save this as `index.htm` with UTF-8 encoding, open it in a browser, and you have your first web page.

---

## 4. HTML Basic
**Definition:** HTML Basic covers the essential building blocks of every page — the document skeleton, headings, paragraphs, links, and images.

**Explanation:**
- Every document opens with `<!DOCTYPE html>`, then `<html>`, and keeps all visible content inside `<body>`
- `<!DOCTYPE html>` appears exactly once at the top of the file; it is case-insensitive and declares an HTML5 document
- Headings use `<h1>` to `<h6>` (`h1` most important, `h6` least); paragraphs use `<p>`
- Links use `<a>` with the destination in `href`; images use `<img>` with `src` (file path), `alt` (fallback text), `width`, and `height`
- To study any live page: press `Ctrl+U` to view its source, or right-click an element and choose **Inspect** to see its HTML and CSS — and edit them on the fly

**Example:**
```html
<!DOCTYPE html>
<html>
<body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>
  <p><a href="https://www.w3schools.com">This is a link</a></p>
  <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

</body>
</html>
```
One document showing the four basics: a heading, a paragraph, a hyperlink, and a sized image with alternative text.

---

## 5. HTML Elements
**Definition:** An HTML element runs from its start tag through its content to its end tag, and a page is built by nesting elements inside one another.

**Explanation:**
- The usual shape is `<tag>content</tag>` — for example `<h1>My First Heading</h1>`
- **Empty elements** carry no content and have no end tag; `<br>` (line break) is one
- Elements **nest**: `<html>` contains `<body>`, which contains `<h1>` and `<p>` — every page is a single tree rooted at `<html>`
- Always close what you open: some unclosed tags still render, but relying on that invites unexpected errors
- Tags are case-insensitive (`<P>` equals `<p>`), though lowercase is the convention (and mandatory in stricter formats like XHTML)

**Example:**
```html
<!DOCTYPE html>
<html>
<body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>

</body>
</html>
```
Four elements nested: `<html>` wraps `<body>`, which in turn wraps the `<h1>` and the `<p>`.

---

## 6. HTML Attributes
**Definition:** Attributes are name/value pairs written in an element's start tag that supply extra information about it — where a link leads, which image to load, or how to style it.

**Explanation:**
- Attributes always live in the start tag and take the form `name="value"`
- Attribute names are case-insensitive, but lowercase is the convention; values should always be quoted — double quotes are usual, single quotes work too and are required when the value itself contains double quotes (e.g. `title='John "ShotGun" Nelson'`)
- `src` accepts an **absolute** URL (a full address on another site, with copyright and availability risks) or a **relative** path (`photo.jpg` resolves beside the current page, `/images/photo.jpg` from the domain root) — relative paths survive domain changes, so prefer them
- **Note:** `<img>` requires `alt`: it displays if the image fails to load and is read aloud by screen readers

| Attribute | Element | Purpose |
|---|---|---|
| `href` | `<a>` | URL the link points to |
| `src` | `<img>` | path to the image file |
| `alt` | `<img>` | fallback text when the image is missing |
| `style` | any | inline CSS, e.g. color or font |
| `lang` | `<html>` | language of the page (`en`, `en-US`) |
| `title` | any | tooltip shown on hover |

**Example:**
```html
<!DOCTYPE html>
<html lang="en">
<body>
  <a href="https://www.w3schools.com">Visit W3Schools</a>
  <p title="I'm a tooltip">This is a paragraph.</p>
  <img src="img_girl.jpg" alt="Girl with a jacket" width="500" height="600">
  <p style="color:red;">This is a red paragraph.</p>
</body>
</html>
```
A page declaring its language, a link, a hover tooltip, an image with size and fallback text, and a paragraph colored red through an inline style.

---

## 7. HTML Headings
**Definition:** HTML headings are the titles and subtitles of a page, written with the `<h1>` through `<h6>` tags — `h1` is the most important level, `h6` the least.

**Explanation:**
- Each level renders at its own default size, and browsers add margin whitespace before and after every heading
- Headings carry structure: search engines index pages by them, and readers skim a page by jumping between them
- Step down the levels in order — `<h1>` for the page title, `<h2>` for sections, `<h3>` for subsections — and use only one `<h1>` per page
- **Note:** headings are for structure only; never use them just to make text big or bold — that is CSS's job
- A single heading's size can still be overridden where needed, e.g. `style="font-size:60px;"`

**Example:**
```html
<h1>Travel Guide</h1>

<h2>Europe</h2>
<h3>France</h3>
<h3>Italy</h3>

<h2>Asia</h2>
<h3>India</h3>
<h3>Thailand</h3>
```
One `h1` names the page, `h2`s divide it into regions, and `h3`s nest the countries beneath each region.

---

## 8. HTML Paragraphs
**Definition:** A paragraph is a block of text defined with the `<p>` tag — it always starts on a new line, and browsers add whitespace margin around it.

**Explanation:**
- Each `<p>` begins a new line automatically; no blank lines are needed between paragraphs in the source
- **Note:** the browser ignores extra spaces, tabs, and line breaks inside the source — it collapses them, so you cannot control layout by typing spaces or newlines (that is CSS's job)
- `<hr>` marks a thematic break between sections and usually renders as a horizontal line; `<br>` inserts a single line break without starting a new paragraph
- Both `<hr>` and `<br>` are empty tags — they have no end tag
- `<pre>` defines preformatted text: it keeps every space and line break as written (rendered in a fixed-width font), which is the fix for text like poems or code

**Example:**
```html
<p>This is a paragraph.</p>

<p>This is<br>a paragraph with a line break.</p>

<hr>

<pre>
  My Bonnie lies over the ocean.
  My Bonnie lies over the sea.
</pre>
```
Two paragraphs, a thematic divider, and a `<pre>` block whose line breaks survive exactly as typed.

---

## 9. HTML Styles
**Definition:** The HTML `style` attribute adds CSS styling — color, font, size, alignment — directly to a single element.

**Explanation:**
- Syntax: `<tagname style="property:value;">` where the property and value are both CSS
- It can be applied to any element, including `<body>` to tint the whole page background

| Property | Controls |
|---|---|
| `background-color` | background color of the element |
| `color` | text color |
| `font-family` | the font used |
| `font-size` | the text size |
| `text-align` | horizontal alignment of the text |

**Example:**
```html
<body style="background-color:powderblue;">

  <h1 style="color:blue; font-family:verdana; font-size:300%;">This is a heading</h1>
  <p style="text-align:center; background-color:tomato;">This is a paragraph.</p>

</body>
```
A powder-blue page, a large blue Verdana heading, and a red centered paragraph — each effect applied inline on its own element.

---

## 10. HTML Formatting
**Definition:** HTML formatting elements give text a special meaning — importance, emphasis, highlighting, edits, sub- and superscript — rather than just a different look.

**Explanation:**
- Formatting tags describe **meaning**, not appearance: browsers choose the default rendering, and CSS can restyle them later
- `<b>` is bold with no extra meaning, while `<strong>` marks text of strong importance (typically bold too); `<i>` sets an alternate voice or mood, while `<em>` marks emphasis — screen readers pronounce `<em>` with verbal stress
- `<del>` and `<ins>` record edits: deleted text usually gets a strikethrough, inserted text an underline

| Tag | Meaning |
|---|---|
| `<b>` | bold text, no extra importance |
| `<strong>` | important text, typically bold |
| `<i>` | alternate voice or mood, typically italic |
| `<em>` | emphasized text |
| `<mark>` | marked / highlighted text |
| `<small>` | smaller text |
| `<del>` | deleted text |
| `<ins>` | inserted text |
| `<sub>` | subscript (e.g. chemical formulas) |
| `<sup>` | superscript (e.g. footnotes) |

**Example:**
```html
<p>Do not forget to buy <mark>milk</mark> today.</p>
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
<p>Water is H<sub>2</sub>O.</p>
```
Highlighted text, a corrected color shown as deleted plus inserted, and a subscripted formula number.

---

## 11. HTML Quotations
**Definition:** Quotation and citation elements mark quoted passages, abbreviations, contact details, and work titles so their meaning is explicit in the markup.

**Explanation:**
- `<blockquote>` holds a longer quotation from another source (its `cite` attribute carries the source URL) and browsers indent it; `<q>` is for a short inline quotation — browsers add the quotation marks themselves
- `<abbr>` wraps an abbreviation or acronym; put the full wording in `title` so it appears on hover, and marking them helps browsers, translation tools, and search engines
- `<address>` holds the contact details of the page's author or owner (usually italic, on its own lines); `<cite>` names the title of a creative work — a person's name is not a work title
- `<bdo>` (bi-directional override) reverses the text direction: `<bdo dir="rtl">` writes right to left

**Example:**
```html
<blockquote cite="https://www.example.com/source">
  A long quotation from another source appears here, indented by the browser.
</blockquote>

<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<bdo dir="rtl">This text will be written from right to left</bdo>
```
An indented block quotation with its source, an abbreviation that reveals its full name on hover, and a direction-overridden run of text.

---

## 12. HTML Comments
**Definition:** HTML comments are notes written into the source code that browsers never display on the page.

**Explanation:**
- Syntax: `<!-- your comment here -->` — the start tag contains `!`, the closing tag does not; comments may span several lines
- They document the source for anyone reading the code, such as reminders or explanations
- Everything between `<!--` and `-->` is hidden from the rendered page, which makes comments a handy way to disable content temporarily — including a fragment in the middle of a line
- **Note:** commenting out lines one at a time is a quick debugging technique: whatever you comment disappears from the page, so you can isolate where an error comes from

**Example:**
```html
<p>This is a paragraph.</p>

<!-- <p>This paragraph is hidden while I test.</p> -->

<p>This <!-- inline comment --> is also a paragraph.</p>
```
The middle paragraph never renders, and the inline comment vanishes while its surrounding sentence displays normally.

---

## 13. HTML CSS
**Definition:** CSS (Cascading Style Sheets) controls the visual design of a page — colors, fonts, sizes, spacing, and layout — and can be attached to HTML in three ways: inline, internal, or external.

**Explanation:**
- **Inline**: the `style` attribute on a single element (as in the HTML Styles section) — affects only that element
- **Internal**: a `<style>` element in the `<head>` — one block styles every matching element on that one page
- **External**: `<link rel="stylesheet" href="styles.css">` in the `<head>` — a plain-text `.css` file with no HTML in it can restyle an entire site from one place; its `href` may be a full URL or a path relative to the page
- "Cascading" means a style set on a parent element flows down to its children unless something more specific overrides it — set the `<body>` text color and every heading and paragraph inherits it
- Common properties: `color`, `font-family`, `font-size`, `border` (edge around an element), `padding` (space inside the border), `margin` (space outside it)

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
<style>
  body { background-color: powderblue; }
  h1   { color: blue; }
  p    { color: red; }
</style>
</head>
<body>
  <h1>This is a heading</h1>
  <p>This is a paragraph.</p>
</body>
</html>
```
An internal stylesheet that gives the page a powder-blue background, blue headings, and red paragraphs in a single page-level block.

---

## 14. HTML Links
**Definition:** A hyperlink lets readers jump from page to page (or to another location) — it is defined with the `<a>` tag, whose `href` attribute names the destination.

**Explanation:**
- Syntax: `<a href="url">link text</a>` — the text between the tags is what readers click; by default links are blue and underlined (visited links turn purple, the active one red) and CSS can restyle them
- Any element can be a link: nest an `<img>` inside the `<a>`, or give a `<button>` an `onclick` handler that sets `document.location`
- `target` decides where the link opens: `_self` (default — same window), `_blank` (new window or tab), `_parent` (parent frame), `_top` (full window body)
- `href` takes an **absolute** URL (`https://www.w3.org/`) or a **relative** URL for a page in the same site (`html_images.asp` next to the current page, `/css/default.asp` from the domain root)
- `mailto:someone@example.com` opens the reader's email program; `title` adds a tooltip on hover

**Example:**
```html
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
<a href="html_images.asp">HTML Images</a>
<a href="mailto:someone@example.com">Send email</a>

<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```
Four link forms: absolute URL opening in a new tab, relative URL within the site, an email link, and an image used as the clickable link.

---

## 15. Link Bookmarks
**Definition:** An HTML bookmark lets readers jump straight to a specific section of a long page by combining an `id` attribute with a link that points at it.

**Explanation:**
- Two steps: mark the destination with an `id` (`id="C4"`), then link to it with a `#` prefix (`href="#C4"`)
- Clicking the link scrolls the page up or down to the element carrying that id
- The bookmark can live on another page — write the file name first: `href="html_demo.html#C4"`
- Bookmarks are most useful on very long pages where scrolling by hand is tedious

**Example:**
```html
<p><a href="#C4">Jump to Chapter 4</a></p>

<h2 id="C4">Chapter 4</h2>
<p>Chapter 4 content goes here.</p>
```
The link scrolls down to the heading tagged `id="C4"`; adding `html_demo.html` before the `#` would jump to that anchor on a different page instead.

---

## 16. HTML Images
**Definition:** The `<img>` tag embeds a picture in a page — it is an empty tag (attributes only, no closing tag) with two required attributes: `src` for the image path and `alt` for its description.

**Explanation:**
- Images are linked, not inserted: when the page loads, the browser fetches the file named by `src` from the server — if the path is wrong, visitors see a broken-link icon plus the `alt` text, so keep the file where the path says it is
- `alt` supplies alternate text for readers who cannot see the image (slow connection, typo in `src`, or a screen reader — software that reads the HTML aloud for visually impaired users)
- **Note:** always set the size — with the `width`/`height` attributes (pixels) or an inline `style` — otherwise the page may flicker while images load; inline sizing also stops a stylesheet rule such as `img {width:100%}` from resizing the picture
- Paths: add the folder name for sub-folders (`/images/html5.gif`), or a full URL for an image on another server — external images may be copyrighted, can disappear or change without warning, and are outside your control
- An animated GIF is just another `<img>`; an image becomes a link by sitting inside an `<a>`; CSS `float` slides it beside the text; and heavy images slow the whole page, so use them sparingly

| Format | Full name | Extensions |
|---|---|---|
| APNG | Animated Portable Network Graphics | `.apng` |
| GIF | Graphics Interchange Format | `.gif` |
| ICO | Microsoft Icon | `.ico`, `.cur` |
| JPEG | Joint Photographic Expert Group | `.jpg`, `.jpeg` |
| PNG | Portable Network Graphics | `.png` |
| SVG | Scalable Vector Graphics | `.svg` |

**Example:**
```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">

<p><img src="smiley.gif" alt="Smiley face" style="float:right;width:42px;height:42px;">
The image floats to the right of this text.</p>
```
A sized image pulled from a sub-folder, and a small image floated beside a paragraph's text.

---

## 17. Image Map
**Definition:** An image map turns separate regions of one picture into individual links — `<map>` declares the map, `<area>` elements define the clickable regions, and the `<img>` points at the map with `usemap`.

**Explanation:**
- The picture links to its map via `usemap="#workmap"`, and that name must equal the `<map name="workmap">` — any image can be used this way
- Each `<area>` carries a `shape`, its `coords`, and an `href` (or an `onclick` that runs JavaScript)
- Shapes and their coordinates (pixels measured from the image's top-left corner):
  - `rect` — `coords="x1,y1,x2,y2"`: top-left then bottom-right corners
  - `circle` — `coords="x,y,r"`: center point then radius
  - `poly` — an `x,y` pair per vertex, tracing any outline
  - `default` — whatever part of the image no other area covers

**Example:**
```html
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect"   coords="34,44,270,350"  alt="Computer" href="computer.htm">
  <area shape="rect"   coords="290,172,333,250" alt="Phone"   href="phone.htm">
  <area shape="circle" coords="337,300,44"      alt="Coffee"  href="coffee.htm">
</map>
```
Three regions of one photo — the computer, the phone, and the coffee cup — each opening its own page when clicked.

---

## 18. Background Images
**Definition:** A background picture can be set on almost any element with the CSS `background-image` property, written inline in a `style` attribute or in a `<style>` block; put it on `<body>` to cover the whole page.

**Explanation:**
- An image smaller than its element tiles by default, repeating horizontally and vertically — set `background-repeat: no-repeat` to stop it
- `background-size: cover` fills the element without distorting proportions; pair it with `background-attachment: fixed` so the backdrop stays in place as the page scrolls
- `background-size: 100% 100%` instead stretches the image to the element's exact box, so it always fills the area but warps when the window is resized

**Example:**
```html
<style>
  body {
    background-image: url('img_girl.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
  }
</style>
```
A full-page backdrop that never repeats, stays fixed while scrolling, and always covers the viewport.

---

## 19. The Picture Element
**Definition:** The `<picture>` element picks between several image files so the browser can serve the right one for the current screen width or supported format — it wraps one or more `<source>` elements plus a fallback `<img>`.

**Explanation:**
- Every `<source>` names a candidate file through `srcset`; a `media` attribute such as `(min-width: 650px)` says when that candidate applies
- The browser uses the **first** `<source>` whose conditions match and ignores all the ones after it — the same rule lets you list several formats and have the browser take the first it understands
- **Note:** the `<img>` must be the last child: it is what renders when `<picture>` is unsupported or no `<source>` matches, so a page never ends up imageless
- Two reasons to use it: bandwidth (a small device skips the large file) and format support (older browsers fall back to a format they can decode)

**Example:**
```html
<picture>
  <source media="(min-width: 650px)" srcset="img_food.jpg">
  <source media="(min-width: 465px)" srcset="img_car.jpg">
  <img src="img_girl.jpg" alt="Girl in a jacket">
</picture>
```
Wide screens get `img_food.jpg`, medium screens `img_car.jpg`, and anything smaller — or any browser ignoring `<source>` — falls back to the `<img>`.

---

## 20. HTML Favicon
**Definition:** A favicon is the small icon displayed beside the page title in the browser tab, linked to the page from `<head>` with a `<link rel="icon">` element.

**Explanation:**
- Put the image in the web server's root directory or in an `images` folder inside it; the conventional file name is `favicon.ico`
- Add the `<link>` element after `<title>`, with `rel="icon"`, a `type` such as `image/x-icon`, and an `href` pointing at the file — reload the page and the icon appears in the tab
- **Tip:** the favicon renders only a few pixels wide, so keep it simple and high-contrast; any image may be used, provided it stays legible at that size
- All major browsers (Edge, Chrome, Firefox, Opera, Safari) accept ICO, PNG, GIF, JPEG, and SVG favicon files

**Example:**
```html
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
```
The `<link>` sits right after the `<title>`, and the saved page shows the icon to the left of the title in the browser tab.

---

## 21. HTML Page Title
**Definition:** The `<title>` element gives the document its title — a short description of the page's meaning that lives in the `<head>` section.

**Explanation:**
- Every page should have a title that describes its content, and it is shown in the browser toolbar or tab
- The same text becomes the page's name when a reader adds it to their favorites, and the headline shown in search engine results
- **Note:** titles carry real weight for search engine optimization (SEO) — search algorithms use this text when deciding the order of listings, so make the title as accurate and meaningful as possible

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>HTML Tutorial</title>
</head>
<body>
  The content of the document...
</body>
</html>
```
One line in `<head>` supplies the tab label, the bookmark name, and the search-result headline.

---

## 22. HTML Tables
**Definition:** A table arranges data into rows and columns — `<table>` is the container, `<tr>` defines each row, and its cells hold either `<td>` data or `<th>` header content.

**Explanation:**
- `<td>` (table data) wraps one cell; everything between the open and close tag is the cell's content, and a cell may contain any HTML — text, images, lists, links, even another table
- `<tr>` (table row) opens each line of cells; a table can have any number of rows, and normally every row should hold the same number of cells (deliberate mismatches come with `colspan`/`rowspan`, covered later)
- `<th>` (table header) is used instead of `<td>` for header cells — their text is bold and centered by default, and CSS can restyle that
- The wider tag set adds `<caption>` (a heading for the whole table), `<colgroup>`/`<col>` (column-level formatting), and `<thead>`, `<tbody>`, `<tfoot>` (groups of header, body, and footer rows)

**Example:**
```html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
</table>
```
A header row of `<th>` cells over a data row of `<td>` cells, three columns wide.

---

## 23. Table Borders
**Definition:** Table borders are pure CSS — apply the `border` property to `table`, `th`, and `td`, then adjust collapse, radius, style, and color.

**Explanation:**
- `border: 1px solid black` on all three selectors draws the lines, but neighboring cells then show doubled borders — add `border-collapse: collapse` to merge them into single shared edges
- `border-style` sets the look: `dotted`, `dashed`, `solid`, `double`, `groove`, `ridge`, `inset`, `outset`, `none`, or `hidden`
- `border-color` sets the color (e.g. `#96D4D4`); a neat trick is cells with a background color and borders in the page's background color, which makes the grid read as borderless
- `border-radius` rounds the corners (e.g. `10px`); drop `table` from the selector and only the cells get frames — the outline around the whole table disappears

**Example:**
```css
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
  border-radius: 10px;
}
```
One rule set gives every cell a single black border with rounded corners.

---

## 24. Table Sizes
**Definition:** A table's width, a column's width, and a row's height are set with the `style` attribute and the CSS `width` or `height` properties.

**Explanation:**
- **Table width** — `style="width:100%"` on `<table>`: a percentage measures the element against its parent (here the `<body>`), so the table spans the page
- **Column width** — `style="width:70%"` on a `<th>` or `<td>` of that column; the whole column follows the cell you size
- **Row height** — `style="height:200px"` on the `<tr>`; pixels give an absolute height

**Example:**
```html
<table style="width:100%">
  <tr>
    <th style="width:70%">Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr style="height:200px">
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
</table>
```
The table fills its parent, the first column takes 70% of the width, and the data row is stretched to 200px tall.

---

## 25. Table Headers
**Definition:** Table headers are `<th>` cells that label columns, rows, or a span of several columns — bold and centered by default — and `<caption>` gives the whole table a heading.

**Explanation:**
- **Horizontal headers**: a first row of `<th>` cells labels each column; **vertical headers**: make the first cell of every row a `<th>` to label the rows instead (like a time column in a schedule)
- **Alignment**: headers are bold and centered out of the box; `th { text-align: left; }` left-aligns them when the table reads better that way
- **Spanning columns**: `colspan="2"` on a `<th>` stretches one header across two or more columns — `rowspan` does the same down a column, with both covered in depth in the colspan & rowspan chapter
- **Caption**: `<caption>` titles the entire table and belongs immediately after the opening `<table>` tag

**Example:**
```html
<table style="width:100%">
  <caption>Members</caption>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
</table>
```
The caption sits above the table, and one `Name` header spans the Firstname and Lastname columns while `Age` covers only its own.

---

## 26. Padding & Spacing
**Definition:** Tables have two independent gaps — cell padding (space between a cell's edge and its content) and cell spacing (space between neighboring cells) — both tuned with CSS.

**Explanation:**
- Padding defaults to `0`; give `th, td` a `padding` value (e.g. `15px`) to breathe content off the cell walls, or use `padding-top`, `padding-bottom`, `padding-left`, and `padding-right` for each side separately
- Spacing defaults to 2 pixels; change the gap between cells with `border-spacing` on the `table` element (e.g. `30px`)
- Padding lives on the cells, spacing on the table — they stack, so set both when a table looks cramped or loose

**Example:**
```css
table { border-spacing: 30px; }
th, td { padding: 15px; }
```
Wide gaps between the cells while each cell's text keeps 15px of breathing room on all sides.

---

## 27. Colspan & Rowspan
**Definition:** The `colspan` and `rowspan` attributes let one cell stretch across several columns or several rows of a table.

**Explanation:**
- `colspan="2"` on a cell makes it span two columns — the value is always the number of columns covered
- `rowspan="2"` does the same down two rows — the value is the number of rows covered
- The cells a span covers are absorbed by it, so those positions need no cells of their own in the rows below

**Example:**
```html
<table>
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <th rowspan="2">Phone</th>
    <td>Jill</td>
    <td>43</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>57</td>
  </tr>
</table>
```
`Name` stretches over two columns with `colspan`, and the `Phone` header stretches down two rows with `rowspan` — the last row supplies only two cells because `Phone` already covers the first position.

---

## 28. Table Styling
**Definition:** A handful of CSS rules turn a plain grid into a readable table — zebra stripes, horizontal dividers, and row highlighting on hover.

**Explanation:**
- **Zebra stripes**: shade every other row with `tr:nth-child(even)`; `(odd)` targets rows 1, 3, 5 instead of 2, 4, 6
- **Vertical stripes**: run `:nth-child(even)` on cells instead of rows — `td:nth-child(even), th:nth-child(even)` shades every other column, and listing both selectors covers headers and data cells alike
- **Combined stripes**: row rules plus column rules overlap; use a transparent `rgba()` color so the crossings blend into a darker intersection
- **Dividers**: `border-bottom: 1px solid #ddd` on `tr` draws a line under every row without vertical borders
- **Hover**: `tr:hover` with a background color lights up whichever row the mouse is over

**Example:**
```css
tr { border-bottom: 1px solid #ddd; }
tr:nth-child(even) { background-color: #D6EEEE; }
tr:hover { background-color: rgba(150, 212, 212, 0.4); }
```
One rule set: divider lines between rows, pale stripes on even rows, and a translucent highlight following the cursor.

---

## 29. Table Colgroup
**Definition:** `<colgroup>` styles whole columns at once — it sits inside `<table>` and holds one or more `<col>` elements, each describing a group of columns and the style they share.

**Explanation:**
- Placement matters: `<colgroup>` must be a child of `<table>` placed before any `<thead>`, `<tr>`, or `<td>` — but after `<caption>` when the table has one
- Each `<col>` carries `span` (how many columns it applies to) and `style`; several `<col>` elements give different column groups different looks, and an unstyled `<col>` covers the columns you leave untouched before a styled group starts
- Only a short list of properties works on columns: `width`, `visibility`, `background`, and `border` — every other CSS property is ignored
- `visibility: collapse` on a `<col>` hides those columns completely

**Example:**
```html
<table>
  <colgroup>
    <col span="2" style="background-color: #D6EEEE">
    <col span="3" style="background-color: pink">
  </colgroup>
  <tr>
    <th>MON</th>
    <th>TUE</th>
    <th>WED</th>
    <th>THU</th>
    <th>FRI</th>
  </tr>
</table>
```
The first two columns are tinted one color, the next three another, without touching a single cell.

---

## 30. HTML Lists
**Definition:** HTML lists group a set of related items in three flavors — unordered (`<ul>`), ordered (`<ol>`), and description (`<dl>`) lists — each built from a small family of tags.

**Explanation:**
- `<ul>` and `<ol>` both wrap `<li>` items: bullets for unordered, numbers for ordered
- `<dl>` holds `<dt>` terms paired with `<dd>` descriptions instead of plain items
- Tag cheat sheet: `<ul>` unordered list, `<ol>` ordered list, `<li>` list item, `<dl>` description list, `<dt>` term, `<dd>` description of that term

**Example:**
```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
</ul>
<ol>
  <li>Coffee</li>
  <li>Tea</li>
</ol>
```
The same two items: bullets from `<ul>`, numbered markers from `<ol>`.

---

## 31. Unordered Lists
**Definition:** `<ul>` defines a bulleted (unordered) list, and the CSS `list-style-type` property chooses the marker — `disc` (default), `circle`, `square`, or `none`.

**Explanation:**
- Items get small filled bullets by default; swap the marker with `list-style-type`, e.g. `circle` for hollow dots, `square` for blocks, `none` to remove markers entirely
- Lists nest: an `<li>` can contain a whole new `<ul>` for sub-items, and a list item may also hold other HTML such as images and links
- A list laid out horizontally makes a navigation menu — strip markers with `list-style-type: none`, float the items with `float: left`, and style the anchors inside

**Example:**
```html
<ul>
  <li>Coffee</li>
  <li>Tea
    <ul>
      <li>Black tea</li>
      <li>Green tea</li>
    </ul>
  </li>
  <li>Milk</li>
</ul>
```
The nested `<ul>` sits inside the `Tea` item, producing a sub-list under it.

---

## 32. Ordered Lists
**Definition:** `<ol>` defines an ordered list whose items are marked with numbers, letters, or Roman numerals, controlled by the `type` attribute.

**Explanation:**
- Default counting starts at `1` with plain numbers as markers
- `type` on `<ol>` picks the marker: `"1"` numbers (default), `"A"`/`"a"` uppercase/lowercase letters, `"I"`/`"i"` uppercase/lowercase Roman numerals
- `start` changes the first number — `start="50"` makes the list run 50, 51, 52 … instead of beginning at 1
- Nesting works exactly like unordered lists: an `<li>` may contain a nested `<ol>`

**Example:**
```html
<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
Items are lettered A, B, C because `type="A"` was set on the `<ol>`.

---

## 33. Other Lists
**Definition:** A description list pairs each term with its explanation, using `<dl>` for the list, `<dt>` for the term (name), and `<dd>` for the description.

**Explanation:**
- `<dl>` is the container; inside it every `<dt>` introduces a term and the `<dd>` that follows describes it
- Terms and descriptions alternate down the list — one `<dt>` then its `<dd>`, then the next term
- Use it for glossaries, parameter lists, or anything that is a definition rather than a sequence

**Example:**
```html
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```
Two term/description pairs: `Coffee` explained as a black hot drink, `Milk` as a white cold drink.

---

## 34. Block & Inline
**Definition:** Every element carries a default display value; the two common ones are *block* (starts on its own line, spans full width) and *inline* (flows inside surrounding text).

**Explanation:**
- Block-level elements always begin on a new line, stretch across the full available width, and get margin space added before and after by the browser — `<p>` and `<div>` are the typical examples
- Inline elements start no new line and take only as much width as their content needs — `<span>` is the typical example
- `<div>` is a block container for whole sections; `<span>` is an inline container for a fragment of text — both commonly carry `style`, `class`, and `id`
- A block-level element must never live inside an inline element

**Example:**
```html
<p>Hello World</p>
<div>Hello World</div>
<p>This is a <span>Hello World</span> inside a paragraph.</p>
```
The `p` and `div` each break onto their own line, while the `span` stays inline within its paragraph.

---

## 35. Div
**Definition:** `<div>` is a block-level container used to group other HTML elements so they can be styled, centered, or arranged as a unit.

**Explanation:**
- By default a `<div>` takes all available width and inserts line breaks before and after, so surrounding text splits into separate lines
- It has no required attributes; `style`, `class`, and `id` are the common ones
- To center a narrower `<div>`, give it a `width` and set `margin: auto`
- Placing `<div>`s side by side is CSS work on a wrapper: `float: left` on the children, `display: inline-block` on the `<div>`s themselves, a flex container (`display: flex`), or a grid container (`display: grid` with `grid-template-columns`) — grid, unlike flex, can define and position multiple rows

**Example:**
```html
<div>
  <h2>London</h2>
  <p>London is the capital city of England.</p>
  <p>London has over 9 million inhabitants.</p>
</div>
```
One container groups the heading and both paragraphs so the whole block can be styled together.

---

## 36. Classes
**Definition:** The `class` attribute assigns one or more class names to an element, letting CSS and JavaScript target every element that shares the name.

**Explanation:**
- Define a class in CSS with a period plus the name (`.city { ... }`) and attach it in HTML with `class="city"` — any HTML element may use it, and names are case sensitive
- Multiple classes ride on one element separated by spaces, e.g. `class="city main"`; the element receives the styles of all listed classes
- Different tags can share the same class — an `<h2>` and a `<p>` both with `class="city"` get identical styling
- JavaScript collects all elements of a class with `getElementsByClassName()`

**Example:**
```html
<style>
.city { background-color: tomato; color: white; padding: 10px; }
</style>
<h2 class="city">London</h2>
<p class="city">Paris is the capital of France.</p>
```
Heading and paragraph share one `.city` definition, so both render with the same background, text color, and padding.

---

## 37. Id
**Definition:** The `id` attribute gives an element a unique identifier — exactly one element in the document may carry a given id value.

**Explanation:**
- CSS targets it with a hash: `#myHeader { ... }`; the name is case sensitive, needs at least one character, cannot start with a number, and must contain no whitespace
- Class vs id: a class may repeat across many elements, an id must appear only once per page
- Bookmarks: put an id on a heading (`id="C4"`), then link to it with `href="#C4"` from the same page or `href="page.html#C4"` from another page — the browser scrolls to that element
- JavaScript fetches that single element with `getElementById()`

**Example:**
```html
<h2 id="C4">Chapter 4</h2>
<a href="#C4">Jump to Chapter 4</a>
```
The id marks the destination and the fragment link jumps straight to it.

---

## 38. Buttons
**Definition:** `<button>` defines a clickable button that can submit forms, run JavaScript, or trigger other actions when clicked.

**Explanation:**
- By itself a button does nothing until it is given an action; it can be styled freely with CSS, e.g. through a `class`
- The `disabled` attribute makes the button unclickable — it usually renders faded
- The `onclick` attribute runs JavaScript on click, e.g. `onclick="alert('Hello!')"`
- `type` defines the behavior: `"button"` is a plain clickable button (does nothing by default), `"submit"` sends the form data, `"reset"` clears the form fields — inside a form the default is `submit`, so always state the `type` explicitly

**Example:**
```html
<button type="button">Normal Button</button>
<button type="submit">Submit</button>
<button type="reset">Reset</button>
```
The three types side by side: inert button, form submitter, and form clearer.

---

## 39. Iframes
**Definition:** `<iframe>` creates an inline frame that embeds another document — typically a whole web page — inside the current page.

**Explanation:**
- `src` gives the URL of the page to embed; always include a `title` so screen readers can announce what the frame contains
- Size it with the `height` and `width` attributes (pixels by default) or with CSS `height`/`width` inside `style`
- The default border can be removed with `style="border:none;"` or restyled like any border, e.g. `border:2px solid red`
- A link can target the frame: give the iframe a `name` (e.g. `iframe_a`) and set the link's `target` to that name — the linked page then loads inside the frame

**Example:**
```html
<iframe src="demo_iframe.htm" name="iframe_a" title="Iframe Example"></iframe>
<p><a href="https://www.w3schools.com" target="iframe_a">W3Schools.com</a></p>
```
Clicking the link loads W3Schools into the named frame instead of replacing the page.

---

## 40. HTML JavaScript
**Definition:** `<script>` defines client-side JavaScript — either statements written inline or an external file via `src` — and `<noscript>` supplies alternate content when scripts cannot run.

**Explanation:**
- JavaScript makes pages dynamic: common jobs are image manipulation, form validation, and changing content on the fly
- The usual way to reach an element is `document.getElementById()`, after which the script can rewrite `innerHTML`, adjust `style` properties, or swap an image's `src`
- `<noscript>` content is what users see when their browser has scripts disabled or unsupported

**Example:**
```html
<script>
  document.getElementById("demo").innerHTML = "Hello JavaScript!";
</script>
<noscript>Sorry, your browser does not support JavaScript!</noscript>
```
The script writes "Hello JavaScript!" into the element with `id="demo"`; the `<noscript>` message appears only when scripts don't run.

---

## 41. File Paths
**Definition:** A file path describes a file's location within the site's folder structure and is required whenever a page links to external files — web pages, images, stylesheets, or scripts.

**Explanation:**
- An absolute path is the file's full URL and works from anywhere, but ties the link to that exact domain
- A relative path resolves against the current page: `picture.jpg` is the same folder, `images/picture.jpg` a subfolder, `/images/picture.jpg` the web root, and `../picture.jpg` one folder up
- Best practice: use relative paths when possible, so links keep working on localhost, on the current domain, and on any future domain

**Example:**
```html
<img src="https://www.w3schools.com/images/picture.jpg" alt="Mountain">
<img src="/images/picture.jpg" alt="Mountain">
<img src="images/picture.jpg" alt="Mountain">
<img src="../images/picture.jpg" alt="Mountain">
```
Same picture, four resolutions: full URL, web root, current folder's subfolder, and one level up.

---

## 42. HTML Head
**Definition:** `<head>` is the document's metadata container — placed between `<html>` and `<body>` — and holds `<title>`, `<style>`, `<meta>`, `<link>`, `<script>`, and `<base>`.

**Explanation:**
- Metadata is data about the page that is never displayed; it typically defines the title, character set, styles, scripts, and other document info
- `<title>` is required, must be text-only, and appears in the browser toolbar, in favorites, and as the search-result heading — it heavily influences SEO, so make it accurate
- `<style>` holds CSS for that single page; `<link rel="stylesheet" href="mystyle.css">` attaches an external stylesheet; `<script>` defines client-side JavaScript
- `<meta>` specifies character set, description, keywords, author, refresh, and viewport settings; `<base>` declares the one base URL and/or click target that every relative link in the page resolves from — only one `<base>` is allowed, and it needs `href`, `target`, or both

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <title>A Meaningful Page Title</title>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="mystyle.css">
</head>
<body>
The content of the document......
</body>
</html>
```
Everything the reader never sees — title, encoding, stylesheet link — lives in `<head>`; the visible content lives in `<body>`.

---

## 43. HTML Layout
**Definition:** Semantic HTML elements mark a page's regions (`<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<details>`, `<summary>`), and four CSS techniques build multicolumn layouts from them.

**Explanation:**
- The layout elements name each part of a page: header, navigation links, document sections, independent articles, sidebar content, footer, plus `<details>`/`<summary>` for expandable content with a heading
- Four multicolumn techniques each with their own pros and cons: CSS frameworks, `float`, flexbox, and grid
- `float` layouts are easy to learn (`float` + `clear`), but floating elements stay tied to the document flow, which can hurt flexibility
- Flexbox keeps elements behaving predictably across screen sizes and devices; grid is a row-and-column system that replaces both floats and positioning — and unlike flex, it can define multiple rows positioned individually

**Example:**
```html
<header>...</header>
<nav>...</nav>
<section>...</section>
<aside>...</aside>
<footer>...</footer>
```
The semantic skeleton of a page — each region named before any CSS decides where it sits.

---

## 44. HTML Responsive
**Definition:** Responsive web design uses HTML and CSS to resize, hide, shrink, or enlarge content automatically so a page looks good on desktops, tablets, and phones.

**Explanation:**
- Start with the viewport tag — `<meta name="viewport" content="width=device-width, initial-scale=1.0">` — so `width=device-width` follows the device's screen width and `initial-scale=1.0` fixes the zoom level on first load
- Responsive images: `width:100%` scales both up and down (and can enlarge past the original size), while `max-width:100%; height:auto` only scales down — usually the better choice
- `<picture>` with `<source srcset media="...">` serves different image files for different window widths, falling back to the inner `<img>`
- Responsive text uses viewport units: 1vw = 1% of viewport width, so `font-size:10vw` grows and shrinks with the window
- Media queries switch styles at breakpoints — e.g. `@media screen and (max-width: 800px)` can drop three columns to full width on small screens; frameworks like W3.CSS and Bootstrap ship responsive defaults

**Example:**
```css
.left, .right { float: left; width: 20%; }
.main { float: left; width: 60%; }
@media screen and (max-width: 800px) {
  .left, .main, .right { width: 100%; }
}
```
Three columns on wide screens; below 800px every column claims full width and stacks.

---

## 45. Computercode
**Definition:** HTML has dedicated elements for code and input — `<code>`, `<kbd>`, `<samp>`, `<var>`, and `<pre>` — rendered in the browser's monospace font except `<var>`, which is typically italic.

**Explanation:**
- `<kbd>` marks keyboard input (e.g. `Ctrl + S`); `<samp>` marks sample output from a program; `<code>` marks a piece of computer code — all three display monospace
- `<var>` defines a variable in programming or math and is typically shown in italic
- `<code>` does not preserve extra whitespace or line breaks — wrap it in `<pre>` to keep the original formatting
- `<pre>` defines preformatted text, so indentation and newlines survive rendering

**Example:**
```html
<pre>
<code>
x = 5;
y = 6;
z = x + y;
</code>
</pre>
```
The `<pre>` wrapper keeps the three statements on separate lines exactly as written.

---

## 46. HTML Semantics
**Definition:** A semantic element clearly signals its purpose to both the browser and the developer — `<article>`, `<img>`, and `<table>` state what their content is, while non-semantic `<div>` and `<span>` say nothing about theirs.

**Explanation:**
- Pages used to fake meaning with `<div id="nav">`, `<div class="header">`, `<div id="footer">`; HTML's semantic elements carry that meaning in the tag itself
- `<section>` is a thematic grouping, typically with a heading (chapters, introductions, news items, contact info); `<article>` is independent, self-contained content (blog posts, forum posts, comments, product cards) — and either may nest inside the other, the definitions do not decide nesting order
- `<header>` holds introductory content or navigation (headings, logo, authorship) and `<footer>` holds authorship, copyright, contact, sitemap, and back-to-top links; a document may have several of each, but `<header>` never goes inside `<footer>`, `<address>`, or another `<header>`
- `<nav>` wraps only major blocks of navigation links (screen readers may skip it); `<aside>` is indirectly related sidebar content; `<figure>` holds self-contained illustrations with an optional `<figcaption>` as first or last child
- W3C's rationale: a semantic web lets information be shared and reused across applications, enterprises, and communities

**Example:**
```html
<figure>
  <img src="pic_trulli.jpg" alt="Trulli">
  <figcaption>Fig1. - Trulli, Puglia, Italy.</figcaption>
</figure>
```
The image and its caption are bound together in one semantic unit instead of an anonymous `<div>`.

---

## 47. HTML Style Guide
**Definition:** Guidelines for writing HTML code that is clean, readable, and consistent — proper doctype, lowercase names, quoted values, and sensible spacing.

**Explanation:**
- Always start with `<!DOCTYPE html>`; never skip the required `<title>` (it drives SEO); add `lang` to `<html>`; declare `<meta charset>` early so language and encoding are interpreted correctly
- Use lowercase element and attribute names, always quote attribute values (mandatory when a value contains spaces), and keep `=` free of surrounding spaces
- Close every element even when HTML allows omission (`<p>`), and keep `<html>`/`<head>`/`<body>` — omitting them can error in old browsers or crash DOM/XML software; the trailing slash in `<meta charset="utf-8" />` is only needed for XML/XHTML consumers
- Formatting: avoid long lines, separate logical blocks with blank lines, indent two spaces (not tabs); one-line comments stay on one line, multi-line comments are wrapped and indented
- Images always get `alt`, `width`, `height` (space reserved before load = less flicker); file names stay lowercase because servers like Apache/Unix are case-sensitive; extensions are `.html` (or `.htm`, identical), `.css`, `.js`

**Example:**
```html
<!DOCTYPE html>
<html lang="en-us">
<head>
  <meta charset="UTF-8">
  <title>Page Title</title>
</head>
```
The recommended opening: doctype, language, charset early, required title — before any body content.

---

## 48. HTML Entities
**Definition:** Character entities replace reserved HTML characters and special symbols, written either as `&entity_name;` or as `&#entity_number;`, so the browser renders the character instead of parsing markup.

**Explanation:**
- `<` and `>` are reserved — used literally, the browser may mix them with your tags; entities display them as plain text. Names (`&lt;`) are easier to remember than numbers (`&#60;`), and entity names are case sensitive
- `&nbsp;` is the non-breaking space: it never splits across a line break, keeping pairs like `§ 10`, `10 km/h`, and `10 PM` together. It also defeats whitespace collapsing — ten plain spaces become one, but `&nbsp;` always renders a full space
- The non-breaking hyphen works the same way for hyphens that must not split a line
- Combining diacritical marks add a glyph (grave, acute — both accents) to a letter, producing characters absent from the page's encoding, e.g. `a` + grave = `à`

**Example:**
```html
<p>Tom &amp; Jerry</p>
<p>Signs: &lt; and &gt;</p>
<p>10&nbsp;km/h</p>
```
Ampersand escaped, reserved signs shown as text, and a distance that cannot wrap after `10`.

---

## 49. HTML Symbols
**Definition:** Symbols and letters that are not on your keyboard — currency, arrows, card suits, math operators, Greek letters — are added to HTML through character entities.

**Explanation:**
- Three equivalent forms exist for each symbol: the entity name (`&euro;`), the decimal number (`&#8364;`), and the hexadecimal reference (`&#x20AC;`) — all render the euro sign
- Common sets include copyright `©`, registered `®`, trademark `™`, the arrows `← ↑ → ↓`, and the card suits `♠ ♣ ♥ ♦`
- Mathematical entities (`∀`, `∂`, `∃`, `∈`, `∑` …) and Greek letters (`Α`, `Β`, `Γ`, `Δ` …) work exactly the same way, with full reference tables for each category

**Example:**
```html
<p>I will display &euro;</p>
<p>I will display &#8364;</p>
<p>I will display &#x20AC;</p>
```
Name, decimal, and hex — three spellings of the same character.

---

## 50. HTML Emojis
**Definition:** Emojis look like images but are not — they are letters (characters) from the UTF-8 (Unicode) character set, and can be written directly or as entity numbers such as `&#128512;`.

**Explanation:**
- UTF-8 covers nearly every character and symbol used on the web; the browser must know the page uses it via `<meta charset="UTF-8">` (UTF-8 is HTML's default charset anyway)
- Every UTF-8 character has a number — `A` is 65, written `&#65;` with `&#` opening and `;` closing — and emoji work the same way: 128516, 128525, and 128151 are all valid character numbers
- Because emojis are characters, they can be copied, displayed, and sized like any other text — e.g. `font-size:48px` scales them up
- W3Schools' reference groups them into smileys, hands, people, office, places, transport, animals, food, sports, weather, and more

**Example:**
```html
<meta charset="UTF-8">
<h1>My First Emoji</h1>
<p>&#128512;</p>
<p style="font-size:48px">&#128512; &#128516; &#128525;</p>
```
An emoji written as its character number, then a row of three enlarged with `font-size`.

---

## 51. HTML Charsets
**Definition:** A character set is the mapping of code numbers to characters that a browser uses to decode a page; it must be declared so text does not render as garbage.

**Explanation:**
- Declare the set in the document head with `<meta charset="UTF-8">` — the modern default for every page
- ASCII covers 128 latin characters (letters, digits, symbols such as `! $ + ( ) @ #`)
- ANSI (Windows-1252) extended ASCII: extras in 128–159, then matches UTF-8 from 160–255
- ISO-8859-1 was HTML 4's default: 256 characters, ASCII plus 160–255
- UTF-8 keeps ASCII for 0–127, then extends into tens of thousands of code points

**Example:**
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Charset Demo</title>
</head>
<body>
  <p>Prices: café €10</p>
</body>
</html>
```

Modern pages should always use UTF-8; older sets (Windows-1252, ISO-8859-1) only matter when reading legacy content.

---

## 52. HTML URL Encode
**Definition:** A URL (web address) can use a domain name or an IP address, and may only carry ASCII characters — anything else must be percent-encoded before the browser sends it.

**Explanation:**
- URL syntax: `scheme://prefix.domain:port/path/filename` — scheme names the service; port defaults to 80 for http; a missing path means the site root
- Common schemes: `http` (plain pages), `https` (encrypted pages), `ftp` (file transfer), `file` (local file)
- Percent-encoding writes a reserved character as `%` followed by hex digits
- Spaces are illegal in URLs — browsers turn them into `+` or `%20` when encoding form input
- With UTF-8, `€` becomes `%E2%82%AC`; Windows-1252 would send the single byte `%80`

**Example:**
```html
<form action="/search">
  <input type="text" name="q" value="café au lait">
  <input type="submit" value="Submit">
</form>
```

On submit the browser percent-encodes the field value, so the server receives ASCII-only bytes it can decode back to the original text.

---

## 53. HTML vs. XHTML
**Definition:** XHTML is HTML written as a strict XML application — the same tags, enforced by XML's well-formedness rules.

**Explanation:**
- `<!DOCTYPE>` and the `xmlns` attribute on `<html>` are mandatory; head, title, and body must all be present
- Elements must be properly nested (`<b><i>x</i></b>`, never crossed like `<b><i>x</b></i>`), always closed, always lowercase
- Attribute names are lowercase and values always quoted
- Minimized attributes are forbidden — write `checked="checked"`, not just `checked`
- Empty elements take a trailing slash: `<br />`, `<img src="x.gif" alt="face" />`

**Example:**
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN"
  "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head><title>Doc</title></head>
<body><p>Hello</p></body>
</html>
```

HTML5 superseded XHTML for new work, but the strictness lessons (nesting, closing tags, quoting attributes) still apply to clean HTML.

---

## 54. HTML Forms
**Definition:** A form collects user input and sends it to a server for processing.

**Explanation:**
- `<form>` is the container for input elements: text fields, radio buttons, checkboxes, submit buttons, and more
- `<input>` is the workhorse — its `type` attribute decides the control: `text`, `password`, `radio`, `checkbox`, `submit`, `button`
- `<label for="x">` binds to the input whose `id` is `x`: screen readers announce it, and clicking the label toggles the control
- Radio buttons sharing one `name` form a group where only one choice wins; checkboxes each need their own name
- `<input type="submit">` posts data to the form's `action`; every input needs a `name` or its value is never sent

**Example:**
```html
<form action="/register">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname">
  <label for="pw">Password:</label>
  <input type="password" id="pw" name="pw">
  <input type="submit" value="Register">
</form>
```

Submitting sends `fname` and `pw` to `/register`; without the `name` attributes the server would receive nothing.

---

## 55. HTML Form Attributes
**Definition:** Attributes on `<form>` control where the data goes, how it is transported, and how the browser treats the submission.

**Explanation:**
- `action` — URL that receives the form data; omit it and the form posts to the current page
- `target` — where the response opens: `_blank` (new tab), `_self` (same window, default), `_parent`, `_top`, or a named frame
- `method` — HTTP verb: `get` appends name/value pairs to the URL (visible, bookmarkable, capped ~2048 chars, never for secrets) or `post` puts data in the request body (no length limit, not bookmarkable)
- `autocomplete="on"` lets the browser fill previously entered values
- `novalidate` skips built-in validation on submit
- Full attribute list: `accept-charset`, `action`, `autocomplete`, `enctype`, `method`, `name`, `novalidate`, `rel`, `target`

**Example:**
```html
<form action="/login" method="post" autocomplete="on">
  <input type="text" name="user">
  <input type="password" name="pass">
  <input type="submit">
</form>
```

Rule of thumb: POST for anything sensitive or large; GET for search-style queries users may bookmark.

---

## 56. HTML Form Elements
**Definition:** Beyond `<form>` and `<input>`, the form vocabulary includes controls for selection, grouping, and computed output.

**Explanation:**
- `<select>` + `<option>` build a drop-down; the first option is pre-selected unless one carries `selected`; `size="3"` shows multiple rows; `multiple` allows multi-pick
- `<textarea>` is a multi-line field — `rows` sets visible lines and `cols` sets width (CSS sizing is preferred)
- `<button>` is a clickable button; always set `type` (`button`, `submit`, `reset`) because browsers disagree on defaults
- `<fieldset>` groups related controls and `<legend>` captions the group — useful for radio clusters and accessibility
- `<datalist>` supplies pre-defined suggestions for an `<input>` via matching `list`/`id`; `<output>` displays a calculation result

**Example:**
```html
<label for="cars">Choose a car:</label>
<select id="cars" name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab" selected>Saab</option>
  <option value="fiat">Fiat</option>
</select>
```

Saab starts selected because of the `selected` attribute; without it the first option (Volvo) would win.

---

## 57. HTML Input Types
**Definition:** The `type` attribute on `<input>` decides which control the browser renders; text is the default and the other types add structure, validation, and better mobile keyboards.

**Explanation:**
- Classic types: `text`, `password` (masked), `submit`, `reset`, `radio` (pick one per name group), `checkbox` (pick any), `button`, `hidden` (not visible; never for secrets)
- Contact types: `email`, `url`, `tel`, `search` — each may auto-validate on submit and shape the on-screen keyboard on phones
- Numeric: `number` (with `min`/`max`/`step`) and `range` (slider, default 0–100)
- Date/time pickers: `date`, `datetime-local`, `month`, `time`, `week` — all accept `min`/`max`
- Special: `color` (native picker), `file` (upload; add `multiple` for multi-select), `image` (graphic submit button, needs `src` and `alt`)

**Example:**
```html
<form>
  <label for="qty">Quantity (1–5):</label>
  <input type="number" id="qty" name="qty" min="1" max="5">
  <input type="submit">
</form>
```

Omit `type` and the browser treats the control as plain text. Client-side constraints are not security — always re-check on the server.

---

## 58. HTML Input Attributes
**Definition:** Input attributes fine-tune a field's initial value, visibility, size, and validation rules.

**Explanation:**
- `value` sets the initial content; `readonly` locks editing (value still submits) while `disabled` greys out the control and drops its value from the submission
- `size` is visible width in characters (default 20); `maxlength` caps how many characters the user may type
- `min`/`max` bound numeric and date inputs; `step` sets legal intervals (e.g. `step="3"` gives …, 0, 3, 6 …)
- `multiple` lets `email`/`file` accept several values; `pattern` validates against a regular expression (add `title` to explain the rule); `placeholder` shows a short hint inside the empty field
- `required` blocks submission until filled; `autofocus` puts the cursor in the field on load
- `list` points at a matching `<datalist>` for suggestions; `autocomplete` is browser prediction on/off

**Example:**
```html
<input type="text" id="fname" name="fname" value="John" readonly>
<input type="text" id="pin" name="pin" maxlength="4" size="4" required>
```

The first field shows John but cannot be edited; the second refuses to submit until the user types something, and accepts at most 4 characters.

---

## 59. Input Form Attributes
**Definition:** `form*` attributes let an `<input>` live outside its `<form>` tag yet still belong to that form, and let one submit button override the form's own settings.

**Explanation:**
- `form="form1"` attaches an input (anywhere on the page) to the form whose `id` is `form1` — handy when a field sits beside, not inside, the form element
- `formaction`, `formenctype`, `formmethod`, `formtarget` override the form's `action`, `enctype`, `method`, and `target` for that one button — e.g. two submit buttons posting to different handlers
- `formnovalidate` skips validation for that submit button; the form-level `novalidate` disables validation for every submission
- The `form*` overrides work only with `type="submit"` and `type="image"`

**Example:**
```html
<form action="/action_page.php" id="form1">
  <input type="text" id="fname" name="fname">
  <input type="submit" value="Submit">
</form>
<input type="text" id="lname" name="lname" form="form1">
```

The last-name field sits outside the form yet still submits with it; use per-button overrides when one form must route "Save" and "Save as Admin" to different endpoints.

---

## 60. HTML Canvas
**Definition:** `<canvas>` is an empty rectangular drawing surface; JavaScript paints pixels onto it — lines, shapes, gradients, text, and images.

**Explanation:**
- The tag itself draws nothing: give it `id`, `width`, `height` (and usually a CSS border), fetch it with `document.getElementById`, and obtain a 2D context via `getContext("2d")`
- Path basics: `moveTo`/`lineTo` + `stroke()` for lines; `beginPath()` + `arc(x, y, r, 0, 2*Math.PI)` + `stroke()` for circles
- Text: set `ctx.font`, then `fillText` (solid) or `strokeText` (outline)
- Gradients: `createLinearGradient` or `createRadialGradient`, add color stops, assign to `fillStyle`, then `fillRect`
- Images: `drawImage(img, x, y)` pastes an existing `<img>` element onto the canvas

**Example:**
```html
<canvas id="myCanvas" width="200" height="100"
        style="border:1px solid #000;"></canvas>
<script>
  var c = document.getElementById("myCanvas");
  var ctx = c.getContext("2d");
  ctx.beginPath();
  ctx.arc(95, 50, 40, 0, 2 * Math.PI);
  ctx.stroke();
</script>
```

Canvas is resolution-dependent and pixel-based: once drawn, the scene is gone — changing one element means redrawing everything.

---

## 61. HTML SVG
**Definition:** SVG (Scalable Vector Graphics) describes shapes as XML markup inside the page; vectors stay crisp at any zoom or size.

**Explanation:**
- Each shape is a real DOM element (`<circle>`, `<rect>`, `<polygon>`, `<ellipse>`, `<text>`) — attributes like `stroke`, `fill`, `stroke-width`, and `opacity` style it directly, and you can attach event handlers
- `<circle cx="50" cy="50" r="40">` centers on (50,50) with radius 40; `<rect>` takes `x`, `y`, `width`, `height` and optional `rx`/`ry` for rounded corners; `<polygon points="...">` draws multi-point shapes
- Reusable defs such as `<linearGradient>` live in `<defs>` and are referenced with `fill="url(#grad1)"`
- SVG vs Canvas: SVG is resolution-independent and re-renders individual objects when attributes change; Canvas is pixel-based and must be fully redrawn — better for games, SVG for logos and icons

**Example:**
```html
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40"
          stroke="green" stroke-width="4" fill="yellow" />
</svg>
```

Both are supported by modern browsers; pick SVG when the graphic must stay sharp and interactive, Canvas when you need raw pixel throughput.

---

## 62. HTML Media
**Definition:** Multimedia on the web covers audio, video, and animation; each asset lives in a file whose extension hints at its format, and browsers only play a fixed set of built-in formats.

**Explanation:**
- HTML's supported video formats are **MP4 (.mp4)**, **WebM (.webm)**, and **Ogg (.ogg)** — MP4 is the recommended default; legacy formats like MPEG, AVI, WMV, MOV, and Flash do not play in HTML browsers
- HTML's supported audio formats are **MP3 (.mp3)**, **WAV (.wav)**, and **Ogg (.ogg)**; MP4 audio also works in all browsers
- MP3 is the best choice for recorded music; WAV is uncompressed; MIDI holds notes, not sound, and does not play in browsers
- Other common but non-HTML audio: MIDI, RealAudio, WMA, AAC — fine on desktop players, not in `<audio>`/`<video>` without a plug-in
- Always ship a supported format (MP4 + WebM fallback for video; MP3 + Ogg for audio) so every browser can decode the file

**Example:**
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.webm" type="video/webm">
  Your browser does not support the video tag.
</video>
```

Listing several sources lets each browser pick the first format it can decode; the fallback text covers browsers that support none of them.

---

## 63. HTML Video
**Definition:** The `<video>` element embeds a movie directly in the page — no plug-in required.

**Explanation:**
- Core pattern: set `width`/`height` (avoids layout flicker while loading) and `controls` (play, pause, volume, timeline); put fallback text between the tags for browsers that lack support
- Multiple `<source>` children let the browser pick the first format it understands — ship MP4 (`type="video/mp4"`) plus a WebM or Ogg fallback
- `autoplay` starts playback on load, but Chromium blocks unmuted autoplay; add `muted` so autoplay is allowed (or require a user gesture)
- Supported formats are MP4, WebM, and Ogg; MIME types are `video/mp4`, `video/webm`, `video/ogg`; put MP4 first because Safari historically lacks Ogg
- The DOM exposes methods and properties (`play`, `pause`, `volume`, duration) and events (play, pause, ended) so custom players can drive the element in JavaScript

**Example:**
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

The browser tries each source in order and plays the first one it can decode; the text between the tags only shows if `<video>` itself is unsupported.

---

## 64. HTML Audio
**Definition:** The `<audio>` element plays sound the same way `<video>` plays pictures — declare sources, add controls, offer fallbacks.

**Explanation:**
- Pattern mirrors video: `controls` shows play/pause/volume; fallback text inside the tags appears only in unsupported browsers
- `<source>` children are tried in order; the browser picks the first recognized MIME type (`audio/mpeg` for MP3, `audio/ogg`, `audio/wav`)
- `autoplay` has the same Chromium restriction — pair with `muted` or trigger play from a user gesture
- Supported formats: MP3, WAV, Ogg — MP3 is the safe default for music (small files, all browsers); WAV is lossless and large; Ogg is a royalty-free fallback (Safari is the weak spot)
- Like video, the audio DOM provides `play`/`pause` methods, `volume`/`currentTime` properties, and play/pause/ended events for scripted players

**Example:**
```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

Always list MP3 with a clear MIME type so every browser can decode at least one source.

---

## 65. HTML Plug-ins
**Definition:** Plug-ins once extended browsers with Java applets, ActiveX, Flash, maps, and scanners — almost all of that is dead; the embed containers remain useful for HTML fragments and images.

**Explanation:**
- Modern browsers no longer support Java applets, ActiveX, or Shockwave Flash; do not design around them
- `<object>` defines an embedded object: historically plug-ins (PDF, Flash), now also HTML fragments (`data="snippet.html"`) or images; it has `width`/`height` and can carry fallback content between its tags
- `<embed>` also embeds content but is void (no closing tag) and cannot hold fallback text; it was standardized only in HTML5 after long browser use
- Both work for including another HTML snippet or an image inside the current page; for video/audio prefer `<video>`/`<audio>`, and for third-party players prefer `<iframe>`

**Example:**
```html
<object width="100%" height="500px" data="snippet.html"></object>
<embed src="audi.jpeg">
```

Use `<object>` when you might need fallback content; use `<embed>` for a simple, self-contained resource with no alternative text required.

---

## 66. HTML YouTube
**Definition:** Embedding YouTube via `<iframe>` is the easiest way to put video on a page — the platform handles formats, transcoding, and delivery.

**Explanation:**
- Workflow: upload to YouTube, copy the video ID (e.g. `tgbNymZ7vqY`), then embed an iframe whose `src` is `https://www.youtube.com/embed/<id>` with `width`/`height` for the player size
- Autoplay: append `autoplay=1`, but Chromium needs `mute=1` as well for autoplay to run
- Loop: `playlist=<videoID>&loop=1` repeats forever; `loop=0` (default) plays once; playlist mode accepts a comma-separated ID list
- Controls: `controls=0` hides the player chrome; `controls=1` (default) shows play/pause/scrubber
- All parameters ride on the embed URL as a query string — keep the `/embed/` path so YouTube serves the player UI, not the full site chrome

**Example:**
```html
<iframe width="420" height="315"
        src="https://www.youtube.com/embed/tgbNymZ7vqY">
</iframe>
```

Iframe embedding avoids shipping multiple video formats yourself; set `loading="lazy"` and sensible dimensions to keep pages fast and layout-stable.

---

## 67. Web APIs
**Definition:** An API (Application Programming Interface) is a set of functions that let programs access features or data of an application, OS, or service; a Web API is one built for the browser.

**Explanation:**
- A Web API extends browser functionality, simplifies complex operations, and wraps hard code behind easy syntax
- Built-in browser APIs covered here: Geolocation (user position), Drag and Drop, Web Storage (key/value pairs), Web Workers (background JS), Server-Sent Events (server-pushed updates), Canvas (JS drawing)
- Always check browser support before using an API, add robust error handling, and request user permission when accessing sensitive data (e.g. location)
- Third-party APIs (YouTube, Twitter, Facebook) are not built in — their code must be downloaded and integrated separately

**Example:**
```html
<script>
if (navigator.geolocation) {
  navigator.geolocation.getCurrentPosition(showPosition);
} else {
  document.getElementById("demo").innerHTML =
    "Geolocation is not supported by this browser.";
}
</script>
```

The feature check runs before any API call — a pattern to copy for every built-in browser API.

---

## 68. Geolocation API
**Definition:** The Geolocation API reads the user's current position — but only after the user grants permission, and only on secure (HTTPS) contexts.

**Explanation:**
- Access it via `navigator.geolocation`; the browser prompts for consent, then picks the best source (GPS on phones, Wi-Fi/IP elsewhere)
- `getCurrentPosition(success, error)` returns coordinates once; success receives `position.coords` with latitude, longitude, and accuracy always present, plus altitude, heading, speed, and timestamp when available
- The error callback can switch on `error.code`: `PERMISSION_DENIED`, `POSITION_UNAVAILABLE`, `TIMEOUT`, `UNKNOWN_ERROR`
- `watchPosition()` keeps returning updated positions as the user moves; `clearWatch()` stops it

**Example:**
```html
<script>
function getLocation() {
  if (navigator.geolocation) {
    navigator.geolocation.getCurrentPosition(showPosition);
  } else {
    document.getElementById("demo").innerHTML = "Not supported.";
  }
}
function showPosition(p) {
  document.getElementById("demo").innerHTML =
    "Latitude: " + p.coords.latitude + "<br>Longitude: " + p.coords.longitude;
}
</script>
```

The coords object always carries latitude, longitude, and accuracy; always handle permission denial and unavailable-position cases gracefully.

---

## 69. Drag and Drop API
**Definition:** The HTML Drag and Drop API lets users grab an element and drag it to a new location — no libraries needed.

**Explanation:**
- Make any element draggable with `draggable="true"`
- `ondragstart` fires on the source; call `dataTransfer.setData("text", id)` to declare what is being dragged
- `ondragover` fires on the potential target; you must call `event.preventDefault()` there, because drops are blocked by default
- `ondrop` fires on the target; call `preventDefault()`, read the payload with `dataTransfer.getData("text")`, then move the element (e.g. `appendChild`)

**Example:**
```html
<div id="div1" ondrop="dropHandler(event)" ondragover="dragoverHandler(event)"></div>
<img id="img1" src="img_logo.gif" draggable="true"
     ondragstart="dragstartHandler(event)" width="336" height="69">
```

Any element (image, heading, link) can be dragged once `draggable="true"` and the three event handlers are wired up.

---

## 70. Popover API
**Definition:** The Popover API is a built-in HTML feature for pop-ups (menus, tooltips, toasts) with zero JavaScript — the browser handles show/hide, stacking, outside-click, and Esc.

**Explanation:**
- Add `popover` to an element (e.g. a `<div>`) to make it a popover; it stays hidden until opened
- Add `popovertarget="tip1"` to a `<button>` to connect it to the popover whose id is `tip1`
- Default type `popover` (= `popover="auto"`) closes on outside click or Esc, and opening one closes any other open auto popover; `popover="manual"` stays open until you close it (good for toasts)
- `popovertargetaction` overrides the toggle default with `"show"` or `"hide"`; style with CSS and the `::backdrop` pseudo-element

**Example:**
```html
<button popovertarget="tip1">Show Tip</button>
<div id="tip1" popover>Here we can show a helpful tip.</div>
```

Use a popover for light, non-blocking UI; use a modal `<dialog>` when the user must respond before continuing.

---

## 71. Web Storage API
**Definition:** Web Storage lets the browser store key/value data locally — larger and more private than cookies, and never sent to the server.

**Explanation:**
- Storage is per origin (domain + protocol); all pages from that origin share the same data; limit is at least 5 MB
- `window.localStorage` persists across sessions (survives tab/browser close); `window.sessionStorage` lasts only one tab session
- Core methods: `setItem(key, value)`, `getItem(key)`, and removing items; always check support with `typeof(Storage) !== "undefined"` first
- Values are stored as strings — convert with `Number()` when you need arithmetic (e.g. a click counter)

**Example:**
```html
<script>
if (typeof(Storage) !== "undefined") {
  localStorage.setItem("lastname", "Smith");
  document.getElementById("demo").innerHTML = localStorage.getItem("lastname");
} else {
  document.getElementById("demo").innerHTML = "Sorry, no Web storage support!";
}
</script>
```

Prefer localStorage for persistent preferences, sessionStorage for single-session state like wizard progress.

---

## 72. Web Workers API
**Definition:** A web worker is an external JavaScript file that runs on a background thread, so heavy work doesn't freeze the page.

**Explanation:**
- Create one with `new Worker("demo_workers.js")`; the worker sends data back via `postMessage()`, and the main thread receives it in `w.onmessage = function(event) { ... }` (data arrives in `event.data`)
- Check support first: `typeof(Worker) !== "undefined"`
- Terminate a worker with `w.terminate()` to free resources; set the variable to `undefined` afterward so a new one can be created
- Workers have no access to `window`, `document`, or the parent object — they cannot touch the DOM directly; all UI updates happen via messages to the main thread

**Example:**
```html
<script>
let w;
function startWorker() {
  if (typeof(Worker) !== "undefined") {
    if (typeof(w) == "undefined") { w = new Worker("demo_workers.js"); }
    w.onmessage = function(event) {
      document.getElementById("demo").innerHTML = event.data;
    };
  }
}
function stopWorker() { w.terminate(); w = undefined; }
</script>
```

Reserve workers for CPU-intensive tasks (parsing, calculations); trivial scripts don't need the overhead.

---

## 73. Server-Sent Events API
**Definition:** Server-Sent Events (SSE) let a web page receive automatic updates pushed from the server over a long-lived HTTP connection — no polling, no WebSocket.

**Explanation:**
- Create an `EventSource` pointed at a server URL that streams events: `var source = new EventSource("demo_sse.php")`
- Each update triggers `source.onmessage`; the payload arrives in `event.data` — append it to the page
- Other handlers: `onopen` (connection opened), `onerror` (connection problem)
- Server side: set the `Content-Type` header to `text/event-stream`, disable caching, and prefix every message line with `data: ` before flushing

**Example:**
```html
<script>
if (typeof(EventSource) !== "undefined") {
  var source = new EventSource("demo_sse.php");
  source.onmessage = function(event) {
    document.getElementById("demo").innerHTML += event.data + "<br>";
  };
} else {
  document.getElementById("demo").innerHTML =
    "Sorry, no support for server-sent events.";
}
</script>
```

Classic use cases: live feeds, stock tickers, sports scores, notification streams — one-directional server-to-client updates.

---

## 74. HTML Accessibility
**Definition:** HTML accessibility means marking up pages so that everyone — including screen-reader and keyboard-only users — can navigate them; semantic elements, meaningful headings, alt text, and clear language are the tools.

**Explanation:**
- Semantic HTML uses elements for their purpose: `<button>` (not `<div>`) for actions — screen readers announce it correctly, and it is focusable and keyboard-clickable by default; non-semantic: `<div>`, `<span>`; semantic: `<form>`, `<table>`, `<article>`
- Headings `<h1>`–`<h6>` define document structure for search engines, skimming users, and screen-reader navigation; use `<h1>` for the main heading and don't use headings just to make text big or bold
- The `alt` attribute describes an image for screen readers and shows when the image fails to load; it should describe the image's content
- Declare the page language with `<html lang="en">` to assist browsers and search engines
- Write clear language (short sentences, avoid abbreviations like Feb, avoid slang) and make link text describe the destination — "Read more about how to eat healthy", never bare "Click here"

**Example:**
```html
<img src="img_chania.jpg" alt="A narrow city street with flowers in Chania">
```

Accessibility is not an add-on — baking it in from the start benefits every user and is required for many compliance standards.

---

*Source topics: W3Schools HTML/CSS tutorials. Notes reworded; identifiers (tags, properties, values) kept exact.*
