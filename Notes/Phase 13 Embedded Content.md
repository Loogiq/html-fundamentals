PHASE 13 — EMBEDDED CONTENT

171. "<iframe>"

Function: Embeds another webpage or external document inside the current webpage.
Example:

<iframe src="https://example.com"></iframe>

172. "<embed>"

Function: Embeds external content into the webpage.
Example:

<embed src="document.pdf" type="application/pdf">

173. "<object>"

Function: Embeds an external resource and provides a container for fallback content.
Example:

<object data="document.pdf" type="application/pdf">
    PDF not supported.
</object>

174. "<canvas>"

Function: Provides a drawing area that JavaScript can use to render graphics.
Logic: HTML provides the canvas; JavaScript usually draws on it.
Example:

<canvas id="myCanvas"></canvas>

175. "<svg>"

Function: Defines scalable vector graphics directly in HTML.
Example:

<svg width="100" height="100">
    <circle cx="50" cy="50" r="40"></circle>
</svg>

176. External Resources

Function: Connects or embeds resources that exist outside the current HTML document.
Logic: HTML can reference external files or content through elements such as "<iframe>", "<img>", "<video>", and "<link>".
Example:

<img src="photo.jpg" alt="Photo">
<link rel="stylesheet" href="style.css">