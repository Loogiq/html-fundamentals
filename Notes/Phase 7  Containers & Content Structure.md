PHASE 7 — CONTAINERS & CONTENT STRUCTURE

80. "<div>"

Function: Creates a generic block-level container for grouping content.
Logic: Use it when no semantic HTML element fits the purpose.
Example:

<div>
    <h2>Profile</h2>
    <p>About me.</p>
</div>

81. "<span>"

Function: Creates a generic inline container for small pieces of content.
Logic: Use it when you need to group or style part of a line of content.
Example:

<p>Hello <span>Hsan</span></p>

82. Block-Level vs Inline Content

Function: Describes how elements participate in the document flow.
Logic: Block content normally starts on a new line; inline content stays within the current line.
Example:

<div>Block</div>
<span>Inline</span>

83. "<main>"

Function: Defines the main content of the webpage.
Logic: A page should normally have one main content area.
Example:

<main>
    <h1>Learning HTML</h1>
</main>

84. "<header>"

Function: Defines introductory content for a page or section.
Example:

<header>
    <h1>My Website</h1>
</header>

85. "<footer>"

Function: Defines footer content for a page or section.
Example:

<footer>
    <p>Copyright 2026</p>
</footer>

86. "<section>"

Function: Defines a thematic section of related content.
Logic: A section usually has its own heading.
Example:

<section>
    <h2>About Me</h2>
    <p>I am learning HTML.</p>
</section>

87. "<article>"

Function: Defines self-contained content that can stand independently.
Example:

<article>
    <h2>Learning HTML</h2>
    <p>HTML structures web content.</p>
</article>

88. "<aside>"

Function: Defines content related to the main content but separate from it.
Example:

<aside>
    <h2>Related Articles</h2>
</aside>

89. "<nav>"

Function: Defines a section containing major navigation links.
Example:

<nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
</nav>

90. Semantic HTML

Function: Uses elements that clearly describe the meaning and purpose of content.
Logic: Choose an element based on what the content means, not how it looks.
Example:

<article>
    <h2>HTML Basics</h2>
    <p>Learn the fundamentals of HTML.</p>
</article>

91. Semantic vs Non-Semantic Elements

Function: Distinguishes meaningful elements from generic containers.
Logic: Semantic elements describe purpose; non-semantic elements mainly group content.
Example:

<article>Semantic</article>
<div>Non-semantic</div>

92. Content Hierarchy

Function: Organizes content into a clear structural hierarchy.
Logic: Use headings and semantic elements to show relationships between content.
Example:

<main>
    <h1>My Website</h1>

    <section>
        <h2>About Me</h2>
        <p>My introduction.</p>
    </section>
</main>