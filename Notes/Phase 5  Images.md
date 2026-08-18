PHASE 5 — IMAGES

62. "<img>"

Function: Embeds an image into the webpage.
Example:

<img src="photo.jpg" alt="My photo">

63. "src"

Function: Specifies the source or location of an image or other embedded resource.
Example:

<img src="photo.jpg" alt="My photo">

64. "alt"

Function: Provides alternative text that describes an image.
Logic: Helps users when the image cannot be seen and supports accessibility.
Example:

<img src="cat.jpg" alt="A black cat">

65. Image Dimensions

Function: Specifies the width and height of an image.
Example:

<img src="photo.jpg" alt="My photo" width="500" height="300">

66. "<figure>"

Function: Groups self-contained content such as an image, illustration, or diagram.
Example:

<figure>
    <img src="photo.jpg" alt="Mountain">
</figure>

67. "<figcaption>"

Function: Provides a caption for a "<figure>".
Example:

<figure>
    <img src="photo.jpg" alt="Mountain">
    <figcaption>Mountain landscape</figcaption>
</figure>

68. Responsive Images

Function: Allows the browser to choose an appropriate image for different screen sizes or resolutions.
Logic: Use responsive image techniques to optimize performance and display quality.
Example:

<img
    src="small.jpg"
    srcset="small.jpg 480w, large.jpg 1200w"
    alt="Mountain"
>

69. "<picture>"

Function: Provides multiple image sources for different conditions.
Example:

<picture>
    <source media="(min-width: 800px)" srcset="large.jpg">
    <img src="small.jpg" alt="Mountain">
</picture>

70. "<source>"

Function: Specifies an alternative media or image source.
Example:

<picture>
    <source srcset="large.webp" type="image/webp">
    <img src="photo.jpg" alt="Photo">
</picture>

71. Image Accessibility

Function: Makes images understandable and usable for people using assistive technologies.
Logic: Use meaningful "alt" text for informative images and appropriate empty "alt=""" for decorative images.
Example:

<img src="logo.png" alt="HSAN">I

