Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Part 1 Modifications
=================

- I added a header tag to wrap around the name of each of the books which I then styled in the CSS file. I styled the headers to be 4em in font-size.
- I changed the font from Times New Roman to Georgia
- Wrapped the eBook licensing in a div, gave it class name license, centered the text, and made it bold
- For 1.html and 2.html, I wrapped all the preliminary information about each book in a div tag with the class name "intro-text" which I then centered and made bold using css.
- Set the background color to #fafafa
- I changed all the paths to the required images for all of the html files since I am using an images folder inside the ./gutenberg
- Changed the link tag to style the css from an external stylesheet. Instead of href="coverpage", the href is now "stylesheet"
- For 1.html and 2.html, I wrapped the contents section inside a div tag with the class named "contents" which I then centered. I did the same for the illustrations section for both html files and gave the div the class name "illustrations"

Part 1 CSS Sources
=================
