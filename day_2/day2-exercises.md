## Chap 3-4 Questions:
1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
 An _ordered_ list is presented as numeric steps (e.g., 1., 2., etc.). An _unordered_ list is presented
 with bullet points and can be used when it doesn't matter what order the points appear in. A definition list, usually used for terms and their definitions, includes elements that contain the term to be defined and the definition.
2. What is the basic structure of an element used to link to another website?
 An absolute link includes <a> and an attribute called href, which specifies the page being linked to. E.g., <a href="http://www.cat-bounce.com">Cat Bounce</a>
3. What attribute should you include in a link to open a new tab when the link is clicked?
 target="_blank"
4. How do you link to a specific part of the same page?
 The id attribute must be used for the element to be linked to. It looks like this: <a> href="#topofpage">Top of page</a>

## Chap 10-12 Questions:
1. What is the purpose of CSS?
  CSS allows the developer to set rules stating how elements look. It forms a sort of invisible box around each HTML element, and the rule applies to the boxes (and their contents).
2. What does CSS stand for? What does cascading mean in this case?
  CSS (Cascading Style Sheets) is called "cascading" because the rules sort of cascade down to subsequent elements (depending on order and specificity of CSS rules).
3. What is the basic structure of a CSS rule?
  A CSS rule is comprised of a selector and a declaration. For example, in:
  ``` p {
    font-family: Arial;
    color: yellow;}
    ```
  the `p` is the selector (selecting all <p> elements), and everything in the {} is the declaration, indicating the font of the text in the <p> element will be yellow and Arial.

4. How do you link a CSS stylesheet to your HTML document?
  CSS can be internal (meaning there's a <style> element that contains the CSS rules which sits inside the <head> element in the HTML document), but usually isn't. Usually, there is an external CSS stylesheet and a <link> element in the HTML document that tells the browser where to find the stylesheet. Here's an example of what it might look like:
  ``` <link href="CSS/Styles.css" type = "text/CSS" rel="stylesheet"/>
  ```

5. When is it useful to use external stylesheets as opposed to using internal CSS?
  It's recommended to use external CSS when the webpage has more than 1 page.

6. Describe what a color hex code is.
  Hex codes are codes that represent binary code values for various colors.

7. What are the three parts of an HSL color property?
  Hue, saturation, and lightness.

8. In the world of typeface, what are the three main categories of fonts?
  serif, sans serif, and monospace

9. What are the differences between them?
  _Serif_ fonts have sort of decorative details at the ends of each letter. _Sans Serif_ fonts literally mean "without serif", so they do not have the decorative details. In monospace fonts, each letter is exactly the same width.
10. When specifying font-size, what are the main three units used?
  Pixels (px), ems, and % (which indicates the percentage of the default font size, usually 16).
