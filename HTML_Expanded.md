1. `<a>` (Anchor):
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

2. `<abbr>` (Abbreviation):
   - Description: The `<abbr>` tag defines an abbreviation or an acronym, providing a tooltip with the full form when hovered over.
   - Attributes:
     - `title`: Specifies the full form of the abbreviation (e.g., `title="World Health Organization"`).
   - Use Cases: Displaying shortened forms of lengthy terms while providing a tooltip for clarification.
   - Example:
     ```html
     <abbr title="World Health Organization">WHO</abbr>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<abbr>`.)

3. `<address>` (Contact Information):
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

4. `<area>` (Image Map Region):
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

5. `<article>` (Article):
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

6. `<aside>` (Sidebar Content):
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

7. `<audio>` (Audio Player):
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

8. `<b>` (Bold Text):
   - Description: The `<b>` tag defines text as bold, providing emphasis without implying any extra importance.
   - Attributes: None
   - Use Cases: Highlighting keywords, terms, or phrases within a paragraph or heading.
   - Example:
     ```html
     <p>This is <b>bold</b> text.</p>
     ```
   - CSS Attributes and Effects:
     - `font-weight`: Sets the weight (boldness) of the text.

9. `<base>` (Document Base URL):
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

10. `<bdi>` (Bi-Directional Isolation):
    - Description: The `<bdi>` tag isolates a span of text that might be formatted in a different direction from the surrounding text.
    - Attributes: None
    - Use Cases: Displaying text that's formatted in a different direction (such as right-to-left) within a document that's predominantly left-to-right, ensuring correct rendering.
    - Example:
      ```html
      <p>Welcome to our website. Your username is: <bdi>مرحبا</bdi></p>
      ```
    - CSS Attributes and Effects: (No specific CSS attributes for `<bdi>`.)

11. `<bdo>` (Bi-Directional Override):
   - Description: The `<bdo>` tag overrides the default directionality of text, allowing you to specify whether the text should be displayed from left to right or right to left.
   - Attributes:
     - `dir`: Specifies the text directionality (e.g., `dir="rtl"` for right-to-left, `dir="ltr"` for left-to-right).
   - Use Cases: Forcing the directionality of text within a document.
   - Example:
     ```html
     <p><bdo dir="rtl">مرحبا</bdo> Hello</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<bdo>`.)

12. `<blockquote>` (Block Quotation):
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

13. `<body>` (Document Body):
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

14. `<br>` (Line Break):
   - Description: The `<br>` tag inserts a single line break within text content.
   - Attributes: None
   - Use Cases: Forcing a line break within a paragraph or line of text.
   - Example:
     ```html
     <p>This is<br>a line break.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<br>`.)

15. `<button>` (Button):
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

16. `<canvas>` (Drawing Area):
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

17. `<caption>` (Table Caption):
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

18. `<cite>` (Citation):
   - Description: The `<cite>` tag defines the title of a creative work, such as a book, movie, or song.
   - Attributes: None
   - Use Cases: Referencing the title of a work within text.
   - Example:
     ```html
     <p>The book <cite>The Great Gatsby</cite> was written by F. Scott Fitzgerald.</p>
     ```
   - CSS Attributes and Effects: (No specific CSS attributes for `<cite>`.)

19. `<code>` (Code):
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

20. `<col>` (Table Column):
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
