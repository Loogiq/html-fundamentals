PHASE 20 — HTML + JAVASCRIPT INTEGRATION

230. "<script>"

Function: Embeds or loads JavaScript in an HTML document.
Example:

<script src="app.js"></script>

231. "defer"

Function: Delays script execution until the HTML document has been fully parsed.
Logic: The script downloads while HTML parsing continues, then runs after parsing.
Example:

<script src="app.js" defer></script>

232. "async"

Function: Loads and executes a script asynchronously while the HTML document is being parsed.
Logic: The script runs as soon as it finishes downloading, so execution order is not guaranteed.
Example:

<script src="analytics.js" async></script>

233. DOM as HTML Representation

Function: Represents the HTML document as a tree of objects that JavaScript can access and manipulate.
Logic: HTML creates the structure; the browser turns it into the DOM.
Example:

<h1 id="title">Hello</h1>

JavaScript can access it through the DOM.

234. "id" as JavaScript Selector

Function: Provides a unique identifier that JavaScript can use to find an element.
Example:

<button id="login">Login</button>

235. "class" as JavaScript Hook

Function: Provides a reusable identifier that JavaScript can use to find groups of elements.
Example:

<button class="delete">Delete</button>
<button class="delete">Delete</button>

236. "data-*" as Data Storage

Function: Stores custom data on an HTML element for JavaScript to access.
Example:

<button data-user-id="123">Profile</button>

237. HTML Events

Function: Provides interaction points that JavaScript can respond to.
Logic: HTML elements can trigger events such as clicks, input, and submission.
Example:

<button onclick="saveData()">Save</button>

238. Form Interaction

Function: Allows JavaScript to read, validate, and respond to user form input.
Example:

<form id="login-form">
    <input id="email" type="email">
    <button type="submit">Login</button>
</form>