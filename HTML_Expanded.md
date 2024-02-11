## 1. `<a>` (Anchor):
   - Description: The `<a>` tag defines a hyperlink, which is used to link one webpage to another or link to specific parts within the same webpage.
   - Attributes:
     - `href`: Specifies the URL of the linked page or the location within the same page (e.g., `href="https://example.com"`).
     - `target`: Specifies where to open the linked document (e.g., `_blank`, `_self`, `_parent`, `_top`).
     - `title`: Provides additional information about the linked document (e.g., `title="Visit Example"`).
   - Use Cases: Creating navigation menus, linking to external or internal pages, creating buttons or images with clickable behavior.
   - Example:
     ```html
     <a href="https://example.com" target="_blank" title="Visit Example">Visit Example</a>
     ```
   - CSS Attributes and Effects:
     - `color`: Changes the color of the link text.
     - `text-decoration`: Specifies the decoration added to the link text (e.g., `underline`, `none`).
     - `font-weight`: Sets the weight (boldness) of the link text.

## 2. `<abbr>` (Abbreviation):
   - Description: The `<abbr>` tag defines an abbreviation or an acronym, providing a tooltip with the full form when hovered over.
   - Attributes:
     - `title`: Specifies the full form of the abbreviation (e.g., `title="World Health Organization"`).
   - Use Cases: Displaying shortened forms of lengthy terms while providing a tooltip for clarification.
   - Example:
     ```html
     <abbr title="World Health Organization">WHO</abbr>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<abbr>`.)

## 3. `<address>` (Contact Information):
   - Description: The `<address>` tag defines contact information for the author or owner of a document.
   - Attributes: None
   - Use Cases: Displaying contact information like postal address, email, or phone number.
   - Example:
     ```html
     <address>
       John Doe<br>
       123 Main Street<br>
       Anytown, USA<br>
       Email: <a href="mailto:john@example.com">john@example.com</a>
     </address>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<address>`.)

## 4. `<area>` (Image Map Region):
   - Description: The `<area>` tag defines a clickable area within an image map, usually used alongside `<map>` to define clickable regions on an image.
   - Attributes:
     - `alt`: Specifies an alternative text for the area (similar to the `alt` attribute in `<img>` tags).
     - `coords`: Specifies the coordinates of the clickable area.
     - `href`: Specifies the URL of the linked document or the location within the same page.
     - `shape`: Specifies the shape of the clickable area (e.g., `rect`, `circle`, `poly`).
     - `target`: Specifies where to open the linked document.
   - Use Cases: Creating clickable regions on an image to navigate to different pages or sections within a webpage.
   - Example:
     ```html
     <img src="planets.jpg" alt="Planets" usemap="#planetmap">
     <map name="planetmap">
       <area shape="rect" coords="0,0,82,126" href="sun.html" alt="Sun">
       <area shape="circle" coords="90,58,3" href="mercury.html" alt="Mercury">
       <area shape="circle" coords="124,58,8" href="venus.html" alt="Venus">
     </map>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<area>`.)

## 5. `<article>` (Article):
   - Description: The `<article>` tag defines an independent piece of content that can stand alone and be reused in different contexts.
   - Attributes: None
   - Use Cases: Grouping together content such as blog posts, news articles, forum posts, etc.
   - Example:
     ```html
     <article>
       <h2>Article Title</h2>
       <p>Article content goes here...</p>
     </article>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<article>`.)

## 6. `<aside>` (Sidebar Content):
   - Description: The `<aside>` tag defines content that is tangentially related to the main content, often presented as a sidebar.
   - Attributes: None
   - Use Cases: Displaying related content, advertisements, or supplementary information alongside the main content.
   - Example:
     ```html
     <aside>
       <h3>Related Links</h3>
       <ul>
         <li><a href="#">Link 1</a></li>
         <li><a href="#">Link 2</a></li>
       </ul>
     </aside>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<aside>`.)

## 7. `<audio>` (Audio Player):
   - Description: The `<audio>` tag embeds audio content in a webpage, allowing users to play audio files directly within the browser.
   - Attributes:
     - `autoplay`: Specifies that the audio will start playing automatically when loaded.
     - `controls`: Specifies that audio controls (play, pause, volume, etc.) should be displayed.
     - `loop`: Specifies that the audio should start over again when finished.
     - `muted`: Specifies that the audio should be muted by default.
     - `preload`: Specifies how the audio should be loaded when the page loads.
     - `src`: Specifies the URL of the audio file.
   - Use Cases: Embedding background music, podcast episodes, or sound effects on a webpage.
   - Example:
     ```html
     <audio controls>
       <source src="audio.mp3" type="audio/mpeg">
       Your browser does not support the audio element.
     </audio>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<audio>`.)

## 8. `<b>` (Bold Text):
   - Description: The `<b>` tag defines text as bold, providing emphasis without implying any extra importance.
   - Attributes: None
   - Use Cases: Highlighting keywords, terms, or phrases within a paragraph or heading.
   - Example:
     ```html
     <p>This is <b>bold</b> text.</p>
     ```
   - CSS Attributes and Effects:
     - `font-weight`: Sets the weight (boldness) of the text.

## 9. `<base>` (Document Base URL):
   - Description: The `<base>` tag specifies the base URL and target for all relative URLs in a document.
   - Attributes:
     - `href`: Specifies the base URL (e.g., `href="https://example.com"`).
     - `target`: Specifies the default target for all hyperlinks and forms in the document.
   - Use Cases: Setting a common base URL for all relative links and forms within a document.
   - Example:
     ```html
     <base href="https://example.com/"

 target="_blank">
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<base>`.)

## 10. `<bdi>` (Bi-Directional Isolation):
    - Description: The `<bdi>` tag isolates a span of text that might be formatted in a different direction from the surrounding text.
    - Attributes: None
    - Use Cases: Displaying text that's formatted in a different direction (such as right-to-left) within a document that's predominantly left-to-right, ensuring correct rendering.
    - Example:
      ```html
      <p>Welcome to our website. Your username is: <bdi>مرحبا</bdi></p>
      ```
    - CSS Attributes and Effects: (No specific CSS attributes for `<bdi>`.)

## 11. `<bdo>` (Bi-Directional Override):
   - Description: The `<bdo>` tag overrides the default directionality of text, allowing you to specify whether the text should be displayed from left to right or right to left.
   - Attributes:
     - `dir`: Specifies the text directionality (e.g., `dir="rtl"` for right-to-left, `dir="ltr"` for left-to-right).
   - Use Cases: Forcing the directionality of text within a document.
   - Example:
     ```html
     <p><bdo dir="rtl">مرحبا</bdo> Hello</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<bdo>`.)

## 12. `<blockquote>` (Block Quotation):
   - Description: The `<blockquote>` tag defines a block of quoted text, typically indented and styled differently from the surrounding text.
   - Attributes:
     - `cite`: Specifies the source of the quoted text.
   - Use Cases: Quoting longer passages from external sources.
   - Example:
     ```html
     <blockquote cite="https://example.com/quote">
       This is a blockquote.
     </blockquote>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<blockquote>`.)

## 13. `<body>` (Document Body):
   - Description: The `<body>` tag defines the main content of an HTML document, including text, images, links, etc.
   - Attributes: None
   - Use Cases: Enclosing all visible content within an HTML document.
   - Example:
     ```html
     <body>
       <h1>Hello, world!</h1>
       <p>This is the main content of the document.</p>
     </body>
     ```
   - CSS Attributes and Effects: 
     - `background-color`: Sets the background color of the document.
     - `color`: Sets the text color within the document.
     - `font-family`: Sets the font family for text within the document.
     - `line-height`: Sets the line height for text within the document.
     - `margin`: Sets the margins around the document content.
     - `padding`: Sets the padding around the document content.

## 14. `<br>` (Line Break):
   - Description: The `<br>` tag inserts a single line break within text content.
   - Attributes: None
   - Use Cases: Forcing a line break within a paragraph or line of text.
   - Example:
     ```html
     <p>This is<br>a line break.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<br>`.)

## 15. `<button>` (Button):
   - Description: The `<button>` tag defines a clickable button, which can be used to trigger actions or submit forms.
   - Attributes:
     - `autofocus`: Specifies that the button should automatically receive focus when the page loads.
     - `disabled`: Specifies that the button is disabled.
     - `form`: Specifies the form the button belongs to.
     - `name`: Specifies the name of the button.
     - `type`: Specifies the type of button (e.g., `submit`, `reset`, `button`).
     - `value`: Specifies the value of the button (used with form submission).
   - Use Cases: Creating interactive buttons for form submission or other actions.
   - Example:
     ```html
     <button type="button">Click me</button>
     ```
   - CSS Attributes and Effects:
     - `background-color`: Sets the background color of the button.
     - `color`: Sets the text color of the button.
     - `padding`: Sets the padding around the button text.
     - `border`: Sets the border around the button.
     - `cursor`: Sets the cursor style when hovering over the button.

## 16. `<canvas>` (Drawing Area):
   - Description: The `<canvas>` tag provides a drawing surface for graphics and animations using JavaScript.
   - Attributes:
     - `height`: Specifies the height of the canvas.
     - `width`: Specifies the width of the canvas.
   - Use Cases: Drawing charts, diagrams, animations, or interactive graphics.
   - Example:
     ```html
     <canvas id="myCanvas" width="200" height="100"></canvas>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<canvas>`.)

## 17. `<caption>` (Table Caption):
   - Description: The `<caption>` tag defines a caption for a `<table>` element, providing a title or description for the table.
   - Attributes: None
   - Use Cases: Providing context or summary information for a table.
   - Example:
     ```html
     <table>
       <caption>Monthly Sales Report</caption>
       <tr>
         <th>Month</th>
         <th>Sales</th>
       </tr>
       <tr>
         <td>January</td>
         <td>$1000</td>
       </tr>
     </table>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<caption>`.)

## 18. `<cite>` (Citation):
   - Description: The `<cite>` tag defines the title of a creative work, such as a book, movie, or song.
   - Attributes: None
   - Use Cases: Referencing the title of a work within text.
   - Example:
     ```html
     <p>The book <cite>The Great Gatsby</cite> was written by F. Scott Fitzgerald.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<cite>`.)

## 19. `<code>` (Code):
   - Description: The `<code>` tag defines a piece of computer code, typically displayed in a monospaced font.
   - Attributes: None
   - Use Cases: Displaying code snippets within text or documentation.
   - Example:
     ```html
     <p>This is an example of <code>inline code</code>.</p>
     ```
   - CSS Attributes and Effects:
     - `font-family`: Sets the font family for code text.
     - `background-color`: Sets the background color behind code text.

## 20. `<col>` (Table Column):
   - Description: The `<col>` tag defines properties for a column within a `<table>` element.
   - Attributes:
     - `span`: Specifies the number of columns the `<col>` element should span.
   - Use Cases: Defining column properties such as width or alignment for table columns.
   - Example:
     ```html
     <table>
       <colgroup>
         <col style="background-color:lightblue">
         <col span="2" style="background-color:lightgreen">
       </colgroup>
       <tr>
         <td>Column 1</td>
         <td>Column 2</td>
         <td>Column 3</td>
       </tr>
     </table>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<col>`.)

## 21. `<colgroup>` (Table Column Group):
   - Description: The `<colgroup>` tag groups together a set of `<col>` elements to apply properties to multiple columns in a table simultaneously.
   - Attributes: None
   - Use Cases: Defining common properties for multiple table columns.
   - Example:
     ```html
     <table>
       <colgroup>
         <col style="background-color: lightblue">
         <col style="background-color: lightgreen">
       </colgroup>
       <tr>
         <td>Column 1</td>
         <td>Column 2</td>
       </tr>
     </table>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<colgroup>`.)

## 22. `<data>` (Data Value):
   - Description: The `<data>` tag provides a machine-readable value within a document, often used for numerical or quantitative data.
   - Attributes:
     - `value`: Specifies the value of the data.
   - Use Cases: Marking up numerical data for machine processing or styling.
   - Example:
     ```html
     <p>The population of <data value="328200000">the United States</data> is approximately 328,200,000.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<data>`.)

## 23. `<datalist>` (Pre-defined Options for Input):
   - Description: The `<datalist>` tag provides a list of predefined options for an `<input>` element, allowing users to select from a list while still permitting freeform input.
   - Attributes: None
   - Use Cases: Providing autocomplete suggestions or pre-defined options for user input fields.
   - Example:
     ```html
     <label for="browser">Choose a browser:</label>
     <input list="browsers" id="browser" name="browser">
     <datalist id="browsers">
       <option value="Chrome">
       <option value="Firefox">
       <option value="Safari">
       <option value="Edge">
       <option value="Opera">
     </datalist>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<datalist>`.)

## 24. `<dd>` (Description List Definition):
   - Description: The `<dd>` tag defines the description of a term in a description list (`<dl>`).
   - Attributes: None
   - Use Cases: Displaying the definition or description of a term within a definition list.
   - Example:
     ```html
     <dl>
       <dt>HTML</dt>
       <dd>HyperText Markup Language</dd>
       <dt>CSS</dt>
       <dd>Cascading Style Sheets</dd>
     </dl>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<dd>`.)

## 25. `<del>` (Deleted Text):
   - Description: The `<del>` tag defines text that has been deleted or removed from a document.
   - Attributes:
     - `cite`: Specifies the URL of the document that explains the reason for the deletion.
     - `datetime`: Specifies the date and time when the deletion occurred.
   - Use Cases: Indicating removed or deleted content, often used in conjunction with `<ins>` to show modifications.
   - Example:
     ```html
     <p>This text is <del>no longer relevant</del> <ins>now important</ins>.</p>
     ```
   - CSS Attributes and Effects:
     - `text-decoration`: Sets the decoration for deleted text (e.g., `line-through`).

## 26. `<details>` (Disclosure Widget):
   - Description: The `<details>` tag creates a disclosure widget that can be toggled open or closed to reveal additional content.
   - Attributes: None
   - Use Cases: Creating collapsible sections of content, such as FAQs or content sections with optional details.
   - Example:
     ```html
     <details>
       <summary>Click to reveal more</summary>
       <p>Additional content goes here...</p>
     </details>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<details>`.)

## 27. `<dfn>` (Definition Term):
   - Description: The `<dfn>` tag defines a term that is being defined within a document, typically used in glossaries or dictionaries.
   - Attributes: None
   - Use Cases: Marking up terms that are being defined within a document.
   - Example:
     ```html
     <p>The <dfn>Internet</dfn> is a global network of interconnected computers.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<dfn>`.)

## 28. `<dialog>` (Dialog Box):
   - Description: The `<dialog>` tag defines a dialog box or modal window within a document, typically used for interactions that require user attention or input.
   - Attributes:
     - `open`: Specifies that the dialog box should be open by default.
   - Use Cases: Creating modal dialogs for user interactions, such as confirmations or form submissions.
   - Example:
     ```html
     <dialog open>
       <p>This is a dialog box.</p>
       <button>Close</button>
     </dialog>
     ```
   - CSS Attributes

 and Effects: (No specific CSS attributes for `<dialog>`.)

## 29. `<div>` (Division):
   - Description: The `<div>` tag defines a generic container or division within a document, often used for grouping and styling purposes.
   - Attributes: None
   - Use Cases: Grouping together content for styling or layout purposes, creating sections or containers within a webpage.
   - Example:
     ```html
     <div>
       <h1>Section Heading</h1>
       <p>This is some content within a division.</p>
     </div>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<div>`.)

## 30. `<dl>` (Description List):
   - Description: The `<dl>` tag defines a description list, which consists of terms (`<dt>`) and their associated descriptions (`<dd>`).
   - Attributes: None
   - Use Cases: Creating glossaries, dictionaries, or other lists where terms are defined with associated descriptions.
   - Example:
     ```html
     <dl>
       <dt>HTML</dt>
       <dd>HyperText Markup Language</dd>
       <dt>CSS</dt>
       <dd>Cascading Style Sheets</dd>
     </dl>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<dl>`.)

## 31. `<dt>` (Description List Term):
   - Description: The `<dt>` tag defines a term or name in a description list (`<dl>`).
   - Attributes: None
   - Use Cases: Marking up terms or names in a definition list.
   - Example:
     ```html
     <dl>
       <dt>HTML</dt>
       <dd>HyperText Markup Language</dd>
       <dt>CSS</dt>
       <dd>Cascading Style Sheets</dd>
     </dl>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<dt>`.)

## 32. `<em>` (Emphasis):
   - Description: The `<em>` tag defines text that should be emphasized, typically rendered in italics by default.
   - Attributes: None
   - Use Cases: Emphasizing text within a sentence or paragraph to convey stress or importance.
   - Example:
     ```html
     <p>This is <em>important</em> information.</p>
     ```
   - CSS Attributes and Effects:
     - `font-style`: Sets the style of the emphasized text (e.g., `italic`).

## 33. `<embed>` (Embedded Content):
   - Description: The `<embed>` tag embeds external content such as multimedia (e.g., audio, video, or interactive content) directly into an HTML document.
   - Attributes:
     - `src`: Specifies the URL of the embedded content.
     - `type`: Specifies the MIME type of the embedded content.
   - Use Cases: Embedding multimedia content like videos or interactive applications.
   - Example:
     ```html
     <embed src="video.mp4" type="video/mp4">
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<embed>`.)

## 34. `<fieldset>` (Field Set):
   - Description: The `<fieldset>` tag groups related form elements together and creates a visual container for them, often with a border and optional legend.
   - Attributes: None
   - Use Cases: Grouping form controls together for better organization and styling.
   - Example:
     ```html
     <fieldset>
       <legend>Personal Information</legend>
       <label for="name">Name:</label>
       <input type="text" id="name" name="name"><br>
       <label for="email">Email:</label>
       <input type="email" id="email" name="email">
     </fieldset>
     ```
   - CSS Attributes and Effects:
     - `border`: Sets the border around the fieldset.
     - `padding`: Sets the padding inside the fieldset.

## 35. `<figcaption>` (Figure Caption):
   - Description: The `<figcaption>` tag defines a caption or title for a `<figure>` element, providing a description or context for the content within the figure.
   - Attributes: None
   - Use Cases: Providing captions or descriptions for images, illustrations, diagrams, etc.
   - Example:
     ```html
     <figure>
       <img src="example.jpg" alt="Example">
       <figcaption>This is an example image.</figcaption>
     </figure>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<figcaption>`.)

## 36. `<figure>` (Figure):
   - Description: The `<figure>` tag encapsulates self-contained content like images, illustrations, diagrams, or code snippets, along with an optional `<figcaption>`.
   - Attributes: None
   - Use Cases: Wrapping images or illustrations with related captions or descriptions.
   - Example:
     ```html
     <figure>
       <img src="example.jpg" alt="Example">
       <figcaption>This is an example image.</figcaption>
     </figure>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<figure>`.)

## 37. `<footer>` (Footer):
   - Description: The `<footer>` tag defines the footer section of a document or a section within a document, typically containing metadata, copyright information, or navigation links.
   - Attributes: None
   - Use Cases: Adding footer content to the bottom of a webpage or a specific section within a webpage.
   - Example:
     ```html
     <footer>
       <p>&copy; 2024 Example Company</p>
     </footer>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<footer>`.)

## 38. `<form>` (Form):
   - Description: The `<form>` tag creates an interactive form for collecting user input, which can be submitted to a server for processing.
   - Attributes:
     - `action`: Specifies the URL where the form data should be submitted.
     - `method`: Specifies the HTTP method to be used when submitting the form (e.g., `GET`, `POST`).
   - Use Cases: Creating various types of input forms for user interaction and data submission.
   - Example:
     ```html
     <form action="/submit-form" method="post">
       <label for="username">Username:</label>
       <input type="text" id="username" name="username">
       <button type="submit">Submit</button>
     </form>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<form>`.)

## 39. `<h1>` to `<h6>` (Headings):
   - Description: The `<h1>` to `<h6>` tags define headings of different levels, where `<h1>` is the highest and `<h6>` is the lowest level heading.
   - Attributes: None
   - Use Cases: Structuring the content hierarchy and providing semantic meaning to different sections of a webpage.
   - Example:
     ```html
     <h1>Main

 Heading</h1>
     <h2>Subheading</h2>
     <h3>Sub-subheading</h3>
     ```
   - CSS Attributes and Effects:
     - `font-size`: Sets the size of the heading text.
     - `font-weight`: Sets the weight (boldness) of the heading text.
     - `margin`: Sets the margins around the heading text.

## 40.  `<head>` (Document Head):
   - Description: The `<head>` tag contains metadata and links to external resources that are essential for the document, such as `<title>`, `<meta>`, `<link>`, and `<script>` tags.
   - Attributes: None
   - Use Cases: Specifying metadata, linking to external resources, and providing instructions for the browser.
   - Example:
     ```html
     <head>
       <title>Document Title</title>
       <meta charset="UTF-8">
       <link rel="stylesheet" href="styles.css">
       <script src="script.js" defer></script>
     </head>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<head>`.)

## 41. `<header>` (Header):
   - Description: The `<header>` tag defines the header section of a document or a section within a document, typically containing introductory content, logos, navigation menus, etc.
   - Attributes: None
   - Use Cases: Adding header content to the top of a webpage or a specific section within a webpage.
   - Example:
     ```html
     <header>
       <h1>Website Title</h1>
       <nav>
         <ul>
           <li><a href="#home">Home</a></li>
           <li><a href="#about">About</a></li>
           <li><a href="#contact">Contact</a></li>
         </ul>
       </nav>
     </header>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<header>`.)

## 42. `<hr>` (Horizontal Rule):
   - Description: The `<hr>` tag inserts a thematic break or horizontal line within a document, typically used to separate content sections.
   - Attributes: None
   - Use Cases: Creating visual divisions or separators between content sections.
   - Example:
     ```html
     <p>This is the first paragraph.</p>
     <hr>
     <p>This is the second paragraph.</p>
     ```
   - CSS Attributes and Effects:
     - `border`: Sets the style, color, and width of the horizontal rule.

## 43. `<html>` (HTML Document):
   - Description: The `<html>` tag defines the root element of an HTML document, encapsulating all other elements within the document.
   - Attributes: None
   - Use Cases: Wrapping all content within an HTML document.
   - Example:
     ```html
     <!DOCTYPE html>
     <html lang="en">
       <head>
         <meta charset="UTF-8">
         <title>Document Title</title>
       </head>
       <body>
         <p>This is the content of the document.</p>
       </body>
     </html>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<html>`.)

## 44. `<i>` (Italic Text):
   - Description: The `<i>` tag defines text that is set in italic style, typically used for stylistic differentiation rather than semantic emphasis.
   - Attributes: None
   - Use Cases: Styling text in an italic font style.
   - Example:
     ```html
     <p>This is <i>italic</i> text.</p>
     ```
   - CSS Attributes and Effects:
     - `font-style`: Sets the style of the italic text.

## 45. `<iframe>` (Inline Frame):
   - Description: The `<iframe>` tag embeds another HTML document within the current document, creating a nested browsing context.
   - Attributes:
     - `src`: Specifies the URL of the document to embed.
     - `width`: Specifies the width of the iframe.
     - `height`: Specifies the height of the iframe.
   - Use Cases: Embedding external content such as maps, videos, or web applications within a webpage.
   - Example:
     ```html
     <iframe src="https://www.example.com" width="600" height="400"></iframe>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<iframe>`.)

## 46. `<img>` (Image):
   - Description: The `<img>` tag embeds an image within a document, displaying a graphical representation.
   - Attributes:
     - `src`: Specifies the URL of the image.
     - `alt`: Specifies alternative text for the image.
     - `width`: Specifies the width of the image.
     - `height`: Specifies the height of the image.
   - Use Cases: Displaying images within a webpage.
   - Example:
     ```html
     <img src="image.jpg" alt="Image Description" width="200" height="150">
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<img>`.)

## 47. `<input>` (Input Control):
   - Description: The `<input>` tag creates an interactive control element, such as a text field, checkbox, radio button, or button.
   - Attributes:
     - `type`: Specifies the type of input control (e.g., `text`, `checkbox`, `radio`, `submit`).
     - `name`: Specifies the name of the input control.
     - `value`: Specifies the initial value of the input control.
   - Use Cases: Creating various types of input controls for collecting user input in forms.
   - Example:
     ```html
     <input type="text" name="username" placeholder="Enter your username">
     <input type="checkbox" name="subscribe" value="yes"> Subscribe
     ```
   - CSS Attributes and Effects: (Styling input controls can vary widely and depend on the specific type of control.)

## 48. `<ins>` (Inserted Text):
   - Description: The `<ins>` tag defines text that has been inserted into a document, typically rendered with an underline by default.
   - Attributes:
     - `cite`: Specifies the URL of the document that explains the reason for the insertion.
     - `datetime`: Specifies the date and time when the insertion occurred.
   - Use Cases: Indicating newly added or inserted content, often used in conjunction with `<del>` to show modifications.
   - Example:
     ```html
     <p>This text is <del>no longer relevant</del> <ins>now important</ins>.</p>
     ```
   - CSS Attributes and Effects:
     - `text-decoration`: Sets the decoration for inserted text (e.g., `underline`).

## 49. `<kbd>` (Keyboard Input):
   - Description: The `<kbd>` tag defines text that represents user input from the keyboard, typically rendered in a monospaced font.
   - Attributes: None
   - Use Cases: Indicating keyboard input or key combinations within text.
   - Example:
     ```html
     <p>To save a file, press <kbd>Ctrl</kbd> + <kbd>S</kbd>.</p>
     ```
   - CSS Attributes and Effects:
     - `font-family`: Sets the font family for keyboard input text.

## 50. `<label>` (Form Label):
   - Description: The `<label>` tag defines a label for an `<input>` element, providing a description or title for the input control.
   - Attributes:
     - `for`: Specifies which input element the label is associated with (via the input's `id` attribute).
   - Use Cases: Associating labels with form controls for better accessibility and usability.
   - Example:
     ```html
     <label for="username">Username:</label>
     <input type="text" id="username" name="username">
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<label>`.)
