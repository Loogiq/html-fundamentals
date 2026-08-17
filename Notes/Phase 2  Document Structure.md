PHASE 2 — HTML DOCUMENT STRUCTURE

11. "<!DOCTYPE html>"

Function: Tells the browser that the document uses modern HTML.
Logic: It should be placed at the very beginning of an HTML document.
Example:

<!DOCTYPE html>

12. "<html>"

Function: The root element that contains the entire HTML document.
Logic: All other HTML elements are placed inside "<html>".
Example:

<html>
    ...
</html>

13. "<head>"

Function: Contains information and resources about the webpage that are not the main page content.
Example:

<head>
    <title>My Website</title>
</head>

14. "<body>"

Function: Contains the main content displayed on the webpage.
Example:

<body>
    <h1>Hello</h1>
    <p>Welcome to my website.</p>
</body>

15. "<title>"

Function: Defines the webpage title shown in the browser tab.
Example:

<title>My Website</title>

16. "<meta>"

Function: Provides metadata about the HTML document.
Example:

<meta charset="UTF-8">

17. "<link>"

Function: Connects the HTML document to an external resource.
Logic: It is commonly used to connect CSS files.
Example:

<link rel="stylesheet" href="style.css">

18. "<style>"

Function: Contains CSS rules directly inside the HTML document.
Example:

<style>
    p {
        color: red;
    }
</style>

19. "<script>"

Function: Embeds or loads JavaScript into the webpage.
Example:

<script src="app.js"></script>

20. HTML Document Hierarchy

Function: Defines the structural relationship between HTML elements.
Logic: The basic hierarchy is "html → head/body → content".
Example:

<!DOCTYPE html>
<html>
    <head>
        <title>My Website</title>
    </head>

    <body>
        <h1>Hello</h1>
        <p>Welcome.</p>
    </body>
</html>