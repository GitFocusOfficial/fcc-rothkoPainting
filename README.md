# Learn the CSS Box Model by Building a Rothko Painting

Every HTML element is its own box – with its own spacing and a border. This is called the Box Model.

In this course, you'll use CSS and the Box Model to create your own Rothko-style rectangular art pieces.

## Step 1

By now, you should be familiar with the basic elements an HTML page should have.

Set up your code with a DOCTYPE declaration, an html element with the language set to English, a head element, and a body element.

**Step 2**

Within the head element, add a meta tag which sets the charset to UTF-8, and a title element with the value Rothko Painting.

Within the body element, add an img element with a src of https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-1.png.

**Step 3**

In the CSS box model, every HTML element is treated as a box with four areas.

Imagine you receive a box from your favorite online retailer -- the content is the item in the box, or in our case, a header, paragraph, or image element.

Change the src attribute in the <img> from https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-1.png to https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-2.png.

**Step 4**

The content is surrounded by a space called padding, similar to how bubble wrap separates an item from the box around it.

Think of the border like the cardboard box your item was shipped in.

Change the src attribute to https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-3.png

**Step 5**

Margin is the area outside of the box, and can be used to control the space between other boxes or elements.

Here the bottom element has a larger top margin, pushing it further down the page.

Now that you understand the CSS box model, let's get started on the Rothko painting.

Remove the <img> element.

**Step 6**

Add a div element in the body.

Set the class attribute equal to canvas.

This will act as the canvas for your painting.

**Step 7**

Before you can start styling the div you added, you need to link your CSS to your HTML.

Add a link element to link your styles.css file. Set the href to styles.css, and remember to set the rel attribute to stylesheet.

**Step 8**

Time for CSS.

Even though your <div> has no text, it's still treated as a box with content. Write a CSS rule that uses the .canvas class selector and set its width to 500 pixels. Here's a CSS rule that sets the width of the class card to 300 pixels:

Example Code

```card
.card {
  width: 300px;
}
```

**Step 9**

Add the height property with the value 600px to your .canvas rule.

**Step 10**

Change the background-color of the canvas to #4d0f00.

**Step 11**

Every painting needs a frame.

Wrap the .canvas element in another div. Give that div the frame class.

**Step 12**

Write a new rule using the .frame class selector.

Use the border shorthand declaration to give the .frame element a solid, black border with a width of 50px.

**Step 13**

The frame is much too wide.

In .frame, set its width to 500 pixels.

**Step 14**

Use padding to adjust the spacing within an element.

In .frame, use the padding shorthand property to increase the space between the .frame and .canvas elements by 50px. The shorthand will increase space in the top, bottom, left, and right of the element's border and canvas within.

**Step 15**

Use margins to adjust the spacing outside of an element.

Using the margin property, give the .frame element vertical margin of 20px, and horizontal margin of auto. This will move the frame down 20 pixels and horizontally center it on the page.

**Step 16**

Add a new div element inside of your .canvas element.

Give the new div the class attribute with a value of one. This will be your first rectangle.

**Step 17**

Write a new rule that targets .one and set its width to 425 pixels.

**Step 18**

Now set the height for .one to 150 pixels.

**Step 19**

Set the background-color of .one to #efb762.

**Step 20**

Use margins to position the .one element on the canvas.

Add the shorthand margin property with a vertical margin of 20px and a horizontal margin of auto.