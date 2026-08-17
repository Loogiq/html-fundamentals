PHASE 17 — ACCESSIBILITY

205. HTML Accessibility

Function: Makes webpages usable by people with different abilities and assistive technologies.
Logic: Use meaningful HTML structure instead of relying only on visual appearance.
Example:

<button>Submit</button>

206. Semantic HTML for Accessibility

Function: Uses meaningful HTML elements so browsers and assistive technologies can understand the page structure.
Example:

<nav>
    <a href="/about">About</a>
</nav>

207. Accessible Headings

Function: Creates a clear content hierarchy for users and assistive technologies.
Logic: Use headings in a logical order based on content structure.
Example:

<h1>My Website</h1>
<h2>About Me</h2>
<h2>Projects</h2>

208. Accessible Links

Function: Makes link purposes clear to users.
Logic: Link text should describe where the link goes.
Example:

<a href="/courses">View HTML Courses</a>

209. Accessible Images

Function: Provides text alternatives for images.
Logic: Use meaningful "alt" text for informative images.
Example:

<img src="profile.jpg" alt="Hsan profile photo">

210. Accessible Forms

Function: Makes form controls understandable and usable.
Example:

<label for="email">Email</label>
<input id="email" type="email">

211. Labels & Form Controls

Function: Connects a label to its form control.
Logic: The label's "for" value should match the input's "id".
Example:

<label for="username">Username</label>
<input id="username" type="text">

212. Keyboard Accessibility

Function: Allows users to navigate and interact with content using a keyboard.
Logic: Prefer native interactive elements such as "<button>" and "<a>".
Example:

<button>Submit</button>

213. ARIA Basics

Function: Adds accessibility information when native HTML cannot fully describe an interface.
Example:

<button aria-label="Close">×</button>

214. Native HTML vs ARIA

Function: Helps choose between native HTML semantics and ARIA.
Logic: Prefer native HTML when it already provides the required behavior and meaning.
Example:

<button>Save</button>