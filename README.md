# one-day-one-code
This is the documentation repository for the One Day One Code journey, which tracks the progressive implementation and enhancement of coding skills through Code of The Day.

## Day Code Projects
1. ***Documentations Repository***
   one-day-one-code: [github.com/rizsvn/one-day-one-code](https://github.com/rizsvn/one-day-one-code)
2. ***Day Code Results***
   | Day Code | Result |
   | - | - |
   | all day | [rizsvn.github.io/one-day-one-code/](https://rizsvn.github.io/one-day-one-code/) |
   | 2025-01-01_03 | [rizsvn.github.io/one-day-one-code/2025-01-01_03/](https://rizsvn.github.io/one-day-one-code/2025-01-01_03/) |
   | 2025-01-04_31 | Scheduled publication |
   | 2025-02-01_28 | Awaiting publication |
   | 2025-03-01_31 | Under development |

## Code of The Day
### 2025-01-04
**CSS Initialization**
- `<link rel="stylesheet" type="text/css" href="styles/style.css">`
  Links external CSS file "style.css" for page styling.
- 1. `<link rel="preconnect" href="https://fonts.googleapis.com">`
     Establishes early connection to Google Fonts server for faster font loading.
  2. `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`
     Preconnects to Google Fonts static content server, enabling cross-origin requests.
  3. `<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">`
     Imports Montserrat font family from Google Fonts with specified weights and styles.
- `*, *::before, *::after { box-sizing: border-box; }`
  Sets all elements to use border-box model, including pseudo-elements, for consistent sizing.
- `body { ... }`
  Applies base styles to the body element.
  1. `font-family: 'Monserrat', sans-serif; `
     Sets the default font to Montserrat, with sans-serif fallback.
  2. `margin: 0;` `padding: 0;`
     Resets default margin and padding for consistent layout.
  3. `background-color: #0D1117;`
     Sets the background color to a dark shade.
  4. `color: #F0F6FC;`
     Sets the default text color to a light shade.
  5. `display: flex;` `flex-direction: column;`
     Uses flexbox to arrange body content in a column.

> "Kickstart your Code of The Day with One Day One Code to progressively implement and enhance your coding skills." - Rizsan Zainal M

*#onedayonecode* *#codeoftheday*

## Day Code Logs
### 2025-01-03
**HTML Navigation on Header**
- `<header class="nav-container">`
  Defines the header section with a navigation container class.
- `<div class="nav-logo">`
  Defines the div section with a navigation logo container class.
- `<h1>One Day One Code</h1>`
  The main heading, displaying the site's title prominently.
- `<nav class="nav-menu">`
  A navigation menu container, used for grouping navigation links.
- `<ul>`
  An unordered list, the common structure for navigation menus.
- `<li>`
  A list item, representing a single navigation link.
- `<a href="#">`
  An anchor tag, creating a clickable link, with "#" as a placeholder URL.

### 2025-01-02
**HTML Metadata**
- `<meta charset="utf-8">`
  Character Encoding Declaration: Specifies UTF-8 character encoding, ensuring proper display of various characters.
- `<meta name="description" content="Code of The Day - 2025-01-02 | One Day One Code">`
  Page Description Metadata: Provides a brief description of the page content, used by search engines for snippets.
- `<meta name="keywords" content="code of the day, one day one code">`
  Keyword Metadata: Lists keywords related to the page content, aiding in search engine indexing.
- `<meta name="author" content="Rizsan Zainal M">`
  Author Metadata: Identifies the author of the page, useful for documentation and attribution.
- `<meta name="viewport" content="width=device-width, initial-scale=1">`
  Viewport Configuration: Sets the viewport for responsive design, ensuring proper rendering on various devices.

### 2025-01-01
**HTML First**
- `<!DOCTYPE html>`
  Document type declaration, essential for browser rendering.
- `<html>`
  Root element, encloses all other elements.
- `<head>`
  Contains document metadata, not displayed on the page.
- `<title>`
  Defines the page title, shown in the browser title or tab.
- `<body>`
  Main content container, visible page elements inside here.
- `<h1>`
  Primary heading, shows the main title of the page.
- `<p>`
  Paragraph element, used for standard text content.

---

© 2025 Rizsan Zainal M
