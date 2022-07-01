## Chap 7 Qs
1. If you're using an input element in a form, what attribute controls the behavior of that input?
  <method> controls whether the values will be stored in a database.

2. What element is used to create a dropdown list?
  <select>

3. If you're using an input element to send form data to a server, what should the type attribute be set to?
  It depends on what type of form control you want to create!
4. What element is used to group similar form items together?
  <fieldset>

## Chaps 13 and 15 Qs
1. Describe the differences between border, margin, and padding.
  __Border__ refers to the outside edge of a box. Every box has a border, even if it's invisible or 0px wide.
  __Margin__ is the area outside the edge of a box's border.
  __Padding__ is the area between a margin and the box's contents.
2. For a CSS rule padding: 1px 2px 5px 10px, what sides of the content box does each pixel value correspond to?
   1- top, 2- right, 5- bottom, 10- left
3. Describe the difference between block-level and inline elements.
    _Block-level_ elements start on a new line and act as the main building blocks of the page's layout. _In-line elements_ flow between the surrounding text without affecting the overall layout.
4. What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?
  Fixed positioning positions an element in relation to the browser window, so the element doesn't move when a user scrolls. It's important to use z-indices when there are relative, fixed, or absolutely-positioned elements so that you can control what happens when they overlap. Elements with higher z-index will appear "in front" of elements with lower z-index.
5. What is the difference between a fixed and liquid layout?
  In a fixed layout, the width of the page contents stays the same regardless of whether the browser window is resized. A liquid layout allows the elements to spread and contract as the browser window size is changed. 
