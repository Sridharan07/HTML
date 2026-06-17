# HTML Practice Project

## Build a Personal Recipe & Travel Site

Work through the tasks in order in a single file called `index.html`.

Each task gives you:
- A definition of the HTML concept
- A task to complete
- The expected output

**Important:** Write the code yourself. No solutions are provided.

**Tutorial Reference:** https://www.youtube.com/watch?v=3jkub2c0kLA

---

# Setup Tasks

## Task 1 — Document Skeleton

### Definition
The skeleton is the required wrapper of every HTML page:
- `<!DOCTYPE html>` declares HTML5
- `<html>` holds the entire page
- `<head>` contains page information
- `<body>` contains visible content

### Task
Create a valid HTML5 document.

Inside `<head>`, add a `<title>`:

`My Recipe & Travel Journal`

### Expected Output
The page appears blank, but the browser tab displays:

**My Recipe & Travel Journal**

---

## Task 2 — Comments

### Definition
Comments are written between:

```html
<!-- Comment -->
```

Browsers ignore comments.

### Task
Add:
- One comment at the top of the body
- Three additional comments for sections such as:
  - Navigation
  - Recipes
  - Footer

### Expected Output
Comments are visible only in the source code.

---

## Task 3 — Not Case Sensitive

### Definition
HTML tags are not case-sensitive.

```html
<h2>
<H2>
```

Both work the same way.

### Task
Create:
- One heading using `<h2>`
- One heading using `<H2>`

Add a comment explaining that both render identically.

### Expected Output
Both headings appear exactly the same.

---

# Text Tasks

## Task 4 — Heading Tags (h1–h6)

### Definition
Heading tags define titles and section headings.

- `<h1>` = largest
- `<h6>` = smallest

### Task

Create:

| Tag | Content |
|------|----------|
| h1 | My Recipe & Travel Journal |
| h2 | Featured Recipe |
| h3 | Ingredients |
| h4 | Preparation Notes |
| h5 | Chef's Tip |
| h6 | Last Updated 2026 |

### Expected Output
Six headings displayed from largest to smallest.

---

## Task 5 — Paragraph Tag

### Definition
The `<p>` tag contains regular text.

### Task
Write a short introduction describing your recipe and travel website.

### Expected Output
A paragraph appears with spacing above and below.

---

## Task 6 — Pre Tag

### Definition
The `<pre>` tag preserves:
- Spaces
- Tabs
- Line breaks

### Task

Display:

```text
Prep   15 min
Cook   30 min
Total  45 min
```

### Expected Output
Text appears aligned exactly as typed.

---

## Task 7 — Bold / Strong

### Definition

- `<b>` makes text bold.
- `<strong>` makes text bold and important.

### Task
Write a sentence containing:
- One `<b>` word
- One `<strong>` word

### Expected Output
Two bold words appear.

---

## Task 8 — i and em

### Definition

- `<i>` = italic text
- `<em>` = emphasized text

### Task
Create a sentence containing:
- One italic word
- One emphasized word

### Expected Output
Both words appear italicized.

---

## Task 9 — Small Tag

### Definition
`<small>` displays smaller text.

### Task
Add a disclaimer.

Example:

```text
Prices may vary by region.
```

### Expected Output
Smaller text appears.

---

## Task 10 — Mark Tag

### Definition
`<mark>` highlights text.

### Task
Highlight an important cooking instruction.

Example:

```text
preheat the oven
```

### Expected Output
Highlighted text appears with a yellow background.

---

## Task 11 — Del and Ins

### Definition

- `<del>` = deleted text
- `<ins>` = inserted text

### Task
Show an old and new recipe price.

### Expected Output
Old price = strikethrough

New price = underlined

---

## Task 12 — Sub and Sup

### Definition

- `<sub>` = subscript
- `<sup>` = superscript

### Task
Create:
- Water formula (H₂O)
- Area measurement (cm²)

### Expected Output
Subscript and superscript appear correctly.

---

## Task 13 — Q Tag

### Definition
`<q>` creates inline quotations.

### Task
Add a short quote.

### Expected Output
Browser automatically adds quotation marks.

---

## Task 14 — Abbr Tag

### Definition
`<abbr>` defines abbreviations.

### Task

Example:

```html
<abbr title="United Kingdom">UK</abbr>
```

### Expected Output
Hovering shows the full meaning.

---

# Link & Image Tasks

## Task 15 — Anchor Tag

### Definition
The `<a>` tag creates links.

### Task
Create:

```text
Search for more recipes
```

Link it to an external website.

### Expected Output
Clickable link.

---

## Task 16 — Absolute URL vs Relative URL

### Definition

Absolute URL:

```text
https://example.com
```

Relative URL:

```text
recipes.html
```

### Task
Create:
- One absolute link
- One relative link

### Expected Output
Both links appear clickable.

---

## Task 17 — Target Attribute

### Definition

```html
target="_blank"
```

Opens a link in a new tab.

### Task
Create a link using `_blank`.

### Expected Output
Link opens in a new tab.

---

## Task 18 — Mailto

### Definition

```html
mailto:
```

Opens the user's email application.

### Task
Create:

```text
Email me your recipe ideas
```

### Expected Output
Email application opens.

---

## Task 19 — Image Tag

### Definition

```html
<img src="" alt="">
```

Displays an image.

### Task
Add:
- Image source
- Descriptive alt text
- Width around 300px

### Expected Output
Image appears.

---

## Task 20 — Image as a Link

### Definition
Place an image inside an anchor tag.

### Task
Make an image clickable.

### Expected Output
Clicking the image opens a website.

---

## Task 21 — Favicon

### Definition

```html
<link rel="icon">
```

Adds a browser tab icon.

### Task
Add a favicon.

### Expected Output
Icon appears beside the page title.

---

# Structure Tasks

## Task 22 — br and hr

### Definition

- `<br>` = line break
- `<hr>` = horizontal divider

### Task
Create:
- Two-line address using `<br>`
- Section divider using `<hr>`

### Expected Output
Address breaks into two lines and divider appears.

---

## Task 23 — Empty Tags

### Definition
Empty tags have no closing tag.

### Task
Add a comment listing:

```text
<br>
<hr>
<img>
<link>
<input>
```

### Expected Output
Visible only in source code.

---

## Task 24 — Div and Span

### Definition

- `<div>` = block container
- `<span>` = inline container

### Task
- Wrap a section in a div
- Color one word using span

### Expected Output
One word appears in a different color.

---

## Task 25 — Class and ID

### Definition

- `id` = unique
- `class` = reusable

### Task
- One div with an ID
- Two paragraphs sharing a class

### Expected Output
No visual change yet.

---

# Styling Tasks

## Task 26 — Inline Style Attribute

### Definition

```html
style=""
```

Applies CSS directly to an element.

### Task
Make a paragraph:
- Blue
- Larger font size

### Expected Output
Styled paragraph appears.

---

## Task 27 — Single and Double Quotes

### Definition
Use single quotes inside double-quoted attributes.

### Task

Example:

```html
style="font-family:'Times New Roman';"
```

### Expected Output
Font renders correctly.

---

# List Tasks

## Task 28 — Lists in HTML

### Definition

### Unordered List

```html
<ul>
```

### Ordered List

```html
<ol>
```

### Description List

```html
<dl>
```

### Task

Create:

1. Shopping list
2. Numbered cooking steps
3. Description list of cooking terms

**Bonus:** Nest a `<ul>` inside an `<ol>` item.

### Expected Output
All three list types appear.

---

# Table Tasks

## Task 29 — Table in HTML

### Definition

- `<table>`
- `<tr>`
- `<th>`
- `<td>`

### Task
Create a meal plan table:

Columns:
- Day
- Breakfast
- Dinner

Rows:
- Monday
- Tuesday

### Expected Output
Bordered table appears.

---

## Task 30 — Colspan

### Definition

```html
colspan=""
```

Spans multiple columns.

### Task
Create a title row:

```text
My Meal Plan
```

Spanning all columns.

### Expected Output
One wide header cell appears.

---

## Task 31 — Rowspan

### Definition

```html
rowspan=""
```

Spans multiple rows.

### Task
Create a "Weekday" cell spanning Monday and Tuesday.

### Expected Output
One tall cell covers two rows.

---

## Task 32 — Table Styles

### Definition
Style tables using:

```css
border-collapse
padding
background-color
```

### Task
Style the meal plan table.

### Expected Output
Cleaner table with colored header.

---

# Embedding Tasks

## Task 33 — Iframe Tag

### Definition

```html
<iframe>
```

Embeds another webpage.

### Task
Embed the tutorial video.

### Expected Output
Video plays inside your page.

---

# Form Tasks

## Task 34 — Forms in HTML

### Definition

Use:
- form
- label
- input
- textarea
- radio buttons
- checkbox
- select
- button

### Task

Create a "Submit Your Recipe" form containing:

- Name
- Email
- Recipe description
- Difficulty (Easy/Medium/Hard)
- Subscribe checkbox
- Category dropdown
- Submit button

### Expected Output
Fully functional form UI.

---

## Task 35 — Fieldset and Legend

### Definition

- `<fieldset>`
- `<legend>`

### Task
Wrap form controls in:

```text
Recipe Submission
```

### Expected Output
Bordered group with caption.

---

# Finishing

## Task 36 — Conclusion Section

### Definition

- `<section>`
- `<footer>`

### Task
Create:
- H2 heading
- Thank-you paragraph
- Horizontal rule
- Copyright footer

### Expected Output
Clean ending section at bottom of page.

---

# Completion Checklist

- [ ] Document skeleton + title
- [ ] Comments
- [ ] Case sensitivity note
- [ ] All 6 headings
- [ ] Paragraph
- [ ] pre tag
- [ ] b / strong
- [ ] i / em
- [ ] small
- [ ] mark
- [ ] del / ins
- [ ] sub / sup
- [ ] q
- [ ] abbr
- [ ] a tag
- [ ] absolute vs relative URL
- [ ] target attribute
- [ ] mailto
- [ ] img tag
- [ ] image as link
- [ ] favicon
- [ ] br / hr
- [ ] empty tags note
- [ ] div / span
- [ ] class / id
- [ ] inline style
- [ ] single & double quotes
- [ ] ul / ol / dl
- [ ] table
- [ ] colspan
- [ ] rowspan
- [ ] table styles
- [ ] iframe
- [ ] form
- [ ] fieldset / legend
- [ ] conclusion / footer

---

## Practice Tip

Build the project once by following the tasks.

Then create a new blank `index.html` file and rebuild everything from memory.

That second pass is where the real learning happens.