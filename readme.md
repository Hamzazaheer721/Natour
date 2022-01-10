Sass CodePen Setup link is as follows :

1. https://codepen.io/hamzazaheer721/pen/jOGmXzE

=> This code will contain, implementation of functions, nesting, variables and extend.

2. https://codepen.io/hamzazaheer721/pen/QWqvzmW?editors=1100

=> This code has grid implementation with float layout

You can select the attributes with attribute selector in css

-> [class^="col-"] {} // All classes that start with col-

-> [class*="col-] {} // All classes that contain col-

-> [class$="col-"] {} // All classes that end with col-

//////////// NOTE //////////////

==> Perspective <==

1. Perspective is used to give some perspective to 3d Positioned Element.
2. It defines how far an element is from the user, so lower the value, the more intense the 3d effect would be.
3. When defining the perspective to an element, it is the child elements which gets the perspective view, not the element itself.

==> Backface-visibility <==

1. Backface of an element is mirror image of front-face being displayed
2. It is useful when element is rotated, it lets you decide if user should see the backface or not.

//////////// NOTE /////////////////

1. In BEM, we don't nest the element names, in following we will create new element while keeping the name of the block.
   -- card
   ---card**side
   ----card**side**picture (incorrect)
   ----card**picture (correct)

==> box-declaration-break <==

It decides how element fragments should be rendered when broken across different multiple lines, columns or pages.
-> box-declaration-break: clone
Each element is rendered independently, with specified border, padding and margin wrapping each fragment. border-radius, border-image, and box-shadow are applied to each fragment independently. background is also drawn independently to each fragment, which means that background-image with background-repeat: no-repeat may nevertheless repeat multiple times

==> background-blend-mode <==

Specifies the blending mode of each background layer (color / image)

////////////// NOTE /////////////

Sometimes, when the child div is put into parent, the border-radius of the parent is lost, because child overflows it

===> Quick FIX <===

give overflow:hidden to parent;

===> NOTE <====

Clip path in google chrome breaks the overflow property

//////// NOTE ///////////

==> shape-outside <==

shape outside property specifies the shape, which usually is non-rectangular, around which adjacent inline-content
should wrap.
By default, inline content wraps around the margin-box. Hence, shape-outside property allows customization to its
wrapping, making it possible to wrap it around complex objects rather than simple boxes.
Note: This is very demanding property, it requires the width, height and float as well.

==================== TIP ======================

Best way to move around an floated element is to manipulate it with transform.

=== Object-fit ===

- object-fit property specifies as how the <img /> or <video /> should be resized to fit its container.

=== Solid Linear Gradient ===

- We can use the linear-gradient to give clip-path like transparent effect
- We use it like following
  - background-image: linear-gradient(105deg, rgba(color1, .9) 0%, rgba(color1, .9) 50%, rgba(color2, .5) 50%)

=== placeholder-shown ===

- it Represents any input/textarea element that is currently displaying placeholder text.
