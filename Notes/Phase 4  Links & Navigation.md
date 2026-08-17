PHASE 4 — LINKS & NAVIGATION

51. "<a>"

Function: Creates a hyperlink to another page, resource, or location.
Logic: The "href" attribute defines where the link goes.
Example:

<a href="https://example.com">Visit Example</a>

52. "href"

Function: Specifies the destination of a link or external resource.
Example:

<a href="about.html">About</a>

53. Absolute URL

Function: Specifies a complete URL including the protocol and domain.
Example:

<a href="https://example.com/about.html">About</a>

54. Relative URL

Function: Specifies a resource location relative to the current page.
Example:

<a href="about.html">About</a>

55. Internal Page Link

Function: Links to another page within the same website.
Example:

<a href="/about.html">About</a>

56. Fragment Identifier

Function: Links directly to a specific element on the same page.
Logic: The "href" uses "#" followed by an element's "id".
Example:

<a href="#contact">Contact</a>

<section id="contact">
    <h2>Contact</h2>
</section>

57. "target"

Function: Specifies where a linked document should open.
Example:

<a href="https://example.com" target="_blank">Open</a>

58. "rel"

Function: Defines the relationship between the current page and the linked resource.
Example:

<a href="https://example.com" rel="noopener">Visit</a>

59. Download Link

Function: Tells the browser to download a linked resource instead of navigating to it.
Example:

<a href="file.pdf" download>Download PDF</a>

60. Email & Telephone Links

Function: Creates links that open an email client or phone application.
Example:

<a href="mailto:hello@example.com">Email</a>
<a href="tel:+123456789">Call</a>

61. "<nav>"

Function: Defines a section containing navigation links.
Logic: Use it for major navigation areas of a website.
Example:

<nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/contact">Contact</a>
</nav>