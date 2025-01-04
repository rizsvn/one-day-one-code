# one-day-one-code
This is the documentation repository for the One Day One Code journey, which tracks the progressive implementation and enhancement of coding skills through Code of The Day.

## Day Code Projects
1. ***Documentations Repository***
   one-day-one-code: [github.com/rizsvn/one-day-one-code](https://github.com/rizsvn/one-day-one-code)
2. ***Day Code Results***
   | Day Code | Result |
   | - | - |
   | all day | [rizsvn.github.io/one-day-one-code/](https://rizsvn.github.io/one-day-one-code/) |
   | 2025-01-01_05 | [rizsvn.github.io/one-day-one-code/2025-01-01_05/](https://rizsvn.github.io/one-day-one-code/2025-01-01_05/) |
   | 2025-01-05_31 | Scheduled publication |
   | 2025-02-01_28 | Awaiting publication |
   | 2025-03-01_31 | Under development |

## Code of The Day
### 2025-01-05
**CSS Navigation styling**
- `.nav-container {
  background-image: linear-gradient(to bottom, #010409ff, #010409bf, #01040980, #01040900);
  position: sticky;
  top: 0;
  z-index: 9;
  height: 50px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 100%;
  padding-block: 1rem;
  margin-inline: auto;
}`
  1. Applies a vertical gradient background for a visual effect.
  2. Sets position: sticky to keep the navbar at the top during scrolling.
  3. Uses a high z-index to ensure the navbar stays above other content.
  4. Defines a fixed height of 50px and uses flexbox for horizontal layout.
  5. Vertically centers items and evenly distributes them.
  6. Sets a 100% width and block padding of 1rem for internal spacing.
  7. Sets margin inline auto to center the element.
- `.nav-container a {
  line-height: 1rem;
  text-decoration: none;
  color: #c0c8ce;
  font-weight: lighter;
  transition: color 0.3s;
}`
  1. Sets line-height for vertical text control.
  2. Removes text decoration and sets text color.
  3. Uses font-weight: lighter for a thinner text appearance.
  4. Adds color transition for a smooth hover effect.
- `.nav-logo {
  height: 32px;
}
.nav-logo .logo-nav {
  margin: 0;
  height: 100%;
  width: auto;
  object-fit: contain;
  font-size: 1em;
  font-weight: normal;
  color: #F0F6FC;
  line-height: 32px;
}`
  1. Sets the logo container height to 32px.
  2. Removes logo margin, adjusts height to 100%, and width to auto.
  3. Uses object-fit: contain to ensure the logo is always visible.
  4. Sets logo font size and font weight.
  5. Sets logo color and line-height to match the container height.
- `.nav-menu ul {
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 2rem;
}
.nav-menu li {
  list-style-type: none;
}`
  1. Removes default padding on the ul list.
  2. Uses flexbox for horizontal layout of menu items.
  3. Sets spacing between menu items using gap.
  4. Removes list styles from li items.
- `.nav-container li a:hover {
  color: #F0F6FC;
  font-weight: normal;
  transition: color 0.3s ease-in-out;
}
.nav-container li a.active {
  color: #F0F6FC;
  font-weight: normal;
  transition: color 0.3s ease-in-out;
}
.nav-container li a.active::after {
  content: "";
  display: block;
  width: 1em;
  height: 0.1em;
  background-color: #F0F6FC;
  margin: 0 auto;
}`
  1. Changes color and font weight on hover or active states for visual indication.
  2. Adds color transition for smooth hover and active effects.
  3. Adds a short underline to the active link using the ::after pseudo-element.
  4. Sets the width, height, color, and margin of the underline.
  5. Uses display: block to allow dimension adjustments.

***Extra:***
- Added and edited some code on previous html:
  1. `<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">`
  2. `<h1>One Day One Code</h1>`
     to `<a href="#"><h1 class="logo-nav">one-day-one-code/</h1></a>`
- Edited some styles on previous css:
  1. `font-family: 'Monserrat', sans-serif;`
     to `font-family: "DM Mono", monospace;`
  2. `color: #F0F6FC;`
     to `color: #9198A1;`

> "Kickstart your Code of The Day with One Day One Code to progressively implement and enhance your coding skills." - Rizsan Zainal M

*#onedayonecode* *#codeoftheday*

## Day Code Logs
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
