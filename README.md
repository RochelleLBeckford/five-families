# Practice: Creating a Webpage building upon HTML basics and understanding how to use CSS

## Understanding selectors and properties to bring styling with colors, fonts, sizing, layouts, and much more...

### Practce understanding CSS Five Font Families

-   [ ] Simple practice to gain a better understanding of the power of adding CSS Styling to a webpage and how it can make it uniquely beautiful
    -   [ ] CSS or Cascading Style Sheet, is a language that paints a website with colors, fonts, layouts, and animations.
    -   [ ] CSS is used to create stunning webpages.
    -   [ ] It can enhance the user experience, and can make a webpage unquie and stand out amongst the rest.
    -   [ ] It is absolutely beautiful to see a webpage come to life and become even more beautiful.

<hr>

-   [ ] Every rule begins with a selector then followed by curly brackets {}
    -   [ ] Inside the curly brackets, declarations are made of property:value pairs seperated by a colon.
    -   [ ] Each line will end with a semicolon ; .
    -   [ ] CSS files have as many rules as desired. Even most webpages commonly used could have several hundres of CSS rules for it.

<hr>

-   [ ] CSS Selectors are used to determine which CSS elements are styled
    -   [ ] The most common type of selectors is the following:
        -   [ ] Type Selectors:
            -   [ ] Selects all the matching elements on the webpage for styling
    -   [ ] HTML elements can be selected by their HTML attributes
        -   [ ] Selecing an element by "class" is done by using a period ".", and can be used to style multiple elements with a matching "class" attribute
        -   [ ] Selecting an element by "id" is done by using a hashtag "#", and is used to style a single element with a matching "id" attribute.
    -   [ ] Instead of selecting every element with a matching class only "div" elements that either have a class of "class-name" or an "id" of "id-name".
        -   [ ] This selection is known as "targeting"

<hr>

-   [ ] CSS Five Font Families:
    -   [ ] Fonts are the most heavily-used properties for styling.
    -   [ ] It can improve readability and further express a page's tone and feeling.
    -   [ ] The are five generic font families
        -   [ ] Serif
        -   [ ] Sans-serif
        -   [ ] Monospace
        -   [ ] Cursive
        -   [ ] Fantasy
    -   [ ] These fonts are considered "web-safe" because they are supported in most major web browsers.

    -   [ ] We use the font-family property to assign these families with CSS
        -   [ ] <img src="img/c-font-family-syntax.png" alt="Font-family Property Syntax" width="250">
        -   [ ] It is good practice to aa general font name after the desired font name so there is a fall back if the browser does not recognize the first font.

    -   [ ] The font-size family is another property used to style fonts.
    -   [ ] It sets how big or small the text a given element should be on the webpage.
    -   [ ] It can be done with absolute units (px, pt, etc..) or relative units (percentages, em, rem, etc..). It can be applied to any element that features text content:
        -   [ ] <img src="img/d-fontt-size-property.png" alt="Font-sizr Property Syntax" width="220">

    -   [ ] The font-weight property is used to style fonts by setting the default "thickness" of a given element's text.
        -   [ ] The property uses either keyword values (i.e. lighter and bolder) or numeric values (i.e. 100 and 800).
            -   [ ] Anything less the 400 will make the font thinner
            -   [ ] Anything from the 400 - 700 range would be normal for most fonts
            -   [ ] While anything above 700 usually makes the font bolder
        -   [ ] <img src="img/f-font-weight-property.png" alt="Font-weight Property Syntax" width="250">

<hr>

-   [ ] The &lt;header&gt; element:
    -   [ ] Is used for the beginning of the webpage
    -   [ ] Houses the title of the webpage along with Logos
    -   [ ] The &lt;img&gt; element:
        -   [ ] Is used for all the images on the webpage

-   [ ] The &lt;br&gt; element:
    -   [ ] Creates a new line in your code and forces whatever comes after to start on a new lin

-   [ ] The &lt;hr&gt; element:
    -   [ ] Adds a horizontal line or dividing line across the webpage
    -   [ ] Used to separate sections or different topics on a webpage

-   [ ] The &lt;main&gt; element:
    -   [ ] Is where the main information of the webpage will go
    -   [ ] The &lt;section&gt; element:
        -   [ ] This groups together pieces of similar information

-   [ ]  The &lt;footer&gt; element:
    -   [ ]  This element tends to finish off the webpage as it is located at the very bottom of the webpage and is the last set of items that will be seen
    -   [ ] For instance:
        -   [ ] A footnote on the webpage
        -   [ ] Links to different sections of the webpage
        -   [ ] A copyright symbol for copyright information
            -   [ ] & copy; -> is the symbol for copyright
        -   [ ] A link to external sources using the "href" attribute of the &lt;a&gt; element for the links in the list item to external sources
            -   [ ] &lt;a href="/privacy"&gt;Privacy&lt;/a&gt;
                -   [ ] Use the target attribute to open the link path in a new tab instead of the current page
                -   [ ] <a href="/privacy" target="_blank">Privacy</a>
                -   [ ] When the user clicks one of these external links, they would be redirected to a new page with the informat ion

<hr>

-   [ ] Encompass:
    -   [ ] HTML
    -   [ ] CSS
-   [ ] HTML:
    -   [ ] Will be the structure and skeleton of how the app will appear on the webpageWill be the structure and skeleton of how the app will appear on the webpage
-   [ ] CSS:
    -   [ ] Encompass the style of the app and give it some flair
