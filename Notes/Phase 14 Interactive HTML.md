PHASE 14 — INTERACTIVE HTML

177. "<details>"

Function: Creates a disclosure widget that the user can open and close.
Logic: Content inside "<details>" is hidden until the user expands it.
Example:

<details>
    <summary>What is HTML?</summary>
    <p>HTML structures web content.</p>
</details>

178. "<summary>"

Function: Defines the visible heading of a "<details>" element.
Example:

<details>
    <summary>Click to learn more</summary>
    <p>More information.</p>
</details>

179. "<dialog>"

Function: Represents a dialog box or modal window.
Example:

<dialog open>
    <p>Hello!</p>
</dialog>

180. "<search>"

Function: Defines a section containing search or filtering controls.
Example:

<search>
    <form>
        <input type="search">
        <button>Search</button>
    </form>
</search>

181. "<progress>"

Function: Displays the progress of a task.
Example:

<progress value="70" max="100"></progress>

182. "<meter>"

Function: Represents a measurement within a known range.
Logic: Use "<meter>" for a value; use "<progress>" for task completion.
Example:

<meter min="0" max="100" value="80">80%</meter>

183. Interactive HTML Concepts

Function: Uses built-in HTML elements to create interactive behavior without requiring JavaScript for basic interactions.
Example:

<details>
    <summary>Show answer</summary>
    <p>HTML provides structure and semantics.</p>
</details>