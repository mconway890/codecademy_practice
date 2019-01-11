# THE BOX MODEL
Review

In this lesson, we covered the four properties of the box model: height and width, padding, borders, and margins. Understanding the box model is an important step towards learning more advanced HTML and CSS topics.

1. The box model comprises a set of properties used to create space around and between HTML elements.
2. The height and width of a content area can be set in pixels or percentage.
3. Borders surround the content area and padding of an element. The color, style, and thickness of a border can be set with CSS properties.
4. Padding is the space between the content area and the border. It can be set in pixels or percent.
5. Margin is the amount of spacing outside of an element's border.
6. Horizontal margins add, so the total space between the borders of adjacent elements is equal to the sum of the right margin of one element and the left margin of the adjacent element.
7. Vertical margins collapse, so the space between vertically adjacent elements is equal to the larger margin.
8. margin: 0 auto horizontally centers an element inside of its parent content area, if it has a width.
9. The overflow property can be set to display, hide, or scroll, and dictates how HTML will render content that overflows its parent's content area.
10. The visibility property can hide or show elements.

# CHANGING THE BOX MODEL
Review: Changing the Box Model

In this lesson, you learned about an important limitation of the default box model: box dimensions are affected by border thickness and padding.

1. In the default box model, box dimensions are affected by border thickness and padding.
2. The box-sizing property controls the box model used by the browser.
3. The default value of the box-sizing property is content-box.
4. The value for the new box model is border-box.
5. The border-box model is not affected by border thickness or padding.

# DISPLAY AND POSITIONING
Review: Layout

In this lesson, you learned how to control the positioning of elements on a web page.

1. The position property allows you to specify the position of an element in three different ways.
2. When set to relative, an element's position is relative to its default position on the page.
3. When set to absolute, an element's position is relative to its closest positioned parent element. It can be pinned to any part of the web page, but the element will still move with the rest of the document when the page is scrolled.
4. When set to fixed, an element's position can be pinned to any part of the web page. The element will remain in view no matter what.
5. The z-index of an element specifies how far back or how far forward an element appears on the page when it overlaps other elements.
6. The display property allows you control how an element flows vertically and horizontally a document.
7. inline elements take up as little space as possible, and they cannot have manually-adjusted width or height.
8. block elements take up the width of their container and can have manually-adjusted heights.
9. inline-block elements can have set width and height, but they can also appear next to each other and do not take up their entire container width.
10. The float property can move elements as far left or as far right as possible on a web page.
11. You can clear an element's left or right side (or both) using the clear property.

When combined with an understanding of the box model, positioning can create visually appealing web pages. 
