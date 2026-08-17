PHASE 19 — HTML + CSS INTEGRATION

223. "class" as a CSS Hook

Function: Gives CSS a reusable selector for styling multiple elements.
Logic: One class can be shared by many elements.
Example:

<p class="text">Hello</p>
<p class="text">World</p>

224. "id" as an Identifier

Function: Gives an element a unique identifier that CSS or JavaScript can target.
Logic: An "id" should normally be unique within the document.
Example:

<h1 id="main-title">Learning HTML</h1>

225. Inline Styles

Function: Applies CSS directly to an HTML element.
Example:

<p style="color: red;">Hello</p>

226. External Stylesheets

Function: Connects an HTML document to a separate CSS file.
Logic: Keeps structure and styling in separate files.
Example:

<link rel="stylesheet" href="style.css">

227. "<link rel="stylesheet">"

Function: Loads an external CSS stylesheet into the webpage.
Example:

<link rel="stylesheet" href="style.css">

228. HTML Structure for CSS

Function: Provides a structured HTML hierarchy that CSS can style.
Logic: Good HTML structure makes CSS easier to organize and maintain.
Example:

<section class="profile">
    <h2>Hsan</h2>
    <p>Content Creator</p>
</section>

229. Semantic Structure vs Styling

Function: Separates an element's meaning from its visual appearance.
Logic: HTML defines meaning; CSS defines presentation.
Example:

<button class="primary">Submit</button>

HTML: button/action
CSS: appearance