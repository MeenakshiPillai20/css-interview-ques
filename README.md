<h1>Interview Questions</h1>
<h3> 1. Difference between flex row and column? </h3>
<p> 
    Flex row and flex column  is a css property based on the concept of css flex box. They are both flex direction 
    property by which we can align the elements in main axis and cross axis. Flex row arrange the items horizontally 
    and flex column arrange the items vertically. The main axis and the cross axis also depend on flex row and 
    flex column. If we give flex direction as row then main axis will be horizontal and the cross axis will be 
    vertical and  if we give flex direction as column then the main axis would be vertical and the cross axis 
    would be horizontal. Flex direction property can be applied to the parent element and also to the children 
    element of the parent tag.
</p>
<h3> 2. Explain inline, internal and external stylesheet? </h3>
<p> 
    There are three different style we can apply to the HTML element they are inline, internal and external. 
    Inline style sheets are where we style the code in the element only using style attribute, we can give 
    the style attribute in the open tag. In internal CSS we use style tag to style the HTML elements of the 
    particular page only. Style tag is always present on head tag. In external CSS we import the link of 
    external CSS file into the HTML in the head tag and we can use that link to as many pages as we want we just 
    want to include that in the head section of each file. Most preference between these three files are inline 
    then internal then external.
</p>
<h3> 3. Justify-content allows you to do what? </h3>
<p> 
    Justify content is a sub property of Flex box module. This property defines how the browser distributes 
    space between and around content items along the main-axis of a flex container, and the inline axis of a 
    grid container. It is used in both flex box and grid in css. Properties of justify content are flex start, 
    flex end, center, space around, space between, space evenly, stretch, etc.
</p>
<h3> 4. Difference between absolute and relative positioning? </h3>
<p> 
    Relative position is used when we need to position the element relative to the normal position. We can 
    also use top, bottom, left, right properties for them that will cause the element away from the normal 
    position. An element with absolute positioning will move accordingly to its parent element. In the absence 
    of the parent element the html will be placed according to the body tag. If we want to position a child 
    element according to the parent element so we have to give position relative to the parent element and 
    position absolute to the child element.
</p>
<h3> 5. What is grid-template-columns used for? </h3>
<p> 
    The grid-template-columns property it is one of the property of grid which specifies the number (and the widths) 
    of columns in a grid layout. The values are a space separated list, where each value specifies the size of 
    the respective column. It is one of the property of grid. Basically by using grid column we can specify how 
    many columns we want in the grid container if we want three columns with same width you can use 
    grid-template-columns : auto auto auto; So the same width three columns would be generated. It specify the 
    size of the respective column. Number of columns can be determined by number of ways that can be pixel, 
    percentage or fraction.
</p>
<h3> 6. What is the z-index in CSS? </h3>
<p> 
    z-index is a CSS property used for positioning it basically defines the order of overlapping HTML elements. 
    Elements with a higher index will be placed on top of elements with a lower index. Z index only works on 
    positioned elements (position:absolute, position:relative, or position:fixed). Z index property determines 
    the stack level of an HTML element. Stack level is position at Z axis. z-index when is positive will show 
    on the top of the element and when negative it will go behind the element and when blur we can see both.
</p>
<h3> 7. What is the difference between padding and margin? </h3>
<p> 
    Padding and margin both are the properties of box model. These are the two properties of CSS which provides 
    space or gap inside or outside border. A margin is the space around an element’s border, while padding is 
    the space between an element’s border and the element’s content. The margin property controls the space 
    outside an element, and the padding property controls the space inside an element. Margin properties can be 
    negative if we want to overlap it and padding should always be positive.
</p>
<h3> 8. What is box sizing? </h3>
<p> 
    Box sizing is a property defines how the width and height get applied on the element. Box-sizing property 
    allows us to include the padding and border in an element's total width and height. By default, the width 
    and height of an element is calculated like this: width + padding + border = actual width of an element
    height + padding + border = actual height of an element. So we set box-sizing as border box so it doesn't 
    include padding and border in the actual width and height.
</p>
<h3> 9. What is animation delay? </h3>
<p> 
    Animation  delay is a sub property of css animation. It is defined that how long the animation should wait 
    by specifying the number of second and milliseconds before starting. The animation-delay CSS property specifies 
    the amount of time to wait from applying the animation to an element before beginning to perform the animation. 
    The animation can start later, immediately from its beginning, or immediately and partway through the animation.
</p>
<h3> 10. Which property you will use to merge cells vertically in grid? </h3>
<p> 
    To merge the cells vertically in a grid we use grid column property. grid-column-start and grid-column-end 
    both these property specifies a grid item's size and location in a grid layout vertically. Its shorthand 
    property is grid column, eg  ->   grid-column : 1/4;
</p>
<h3> 11. Which property you will use to merge cells horizontally in grid? </h3>
<p> 
    To merge the cells horizontally in a grid we use grid row property. grid-row-start and grid-row-end both 
    these property specifies a grid item's size and location in a grid layout horizontally. Its shorthand property 
    is grid row, eg  ->   grid-row : 1/4;
</p>
<h3> 12. Explain CSS box model? </h3>
<p> 
    Box model refers to how HTML elements are modeled in browser. It us mostly referred when we design some 
    page or layout. It basically allows us to add a border around elements, and to define space between elements.
    It is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, 
    and the actual content. <strong>Content -> </strong> The content of the box, where text and images appear. 
    <strong>Padding -> </strong> Clears an area around the content. The padding is transparent.<strong>
    Border -> </strong> A border that goes around the padding and content. <strong>Margin -> </strong> Clears an 
    area outside the border. The margin is transparent.    
</p>
<h3> 13. what is the difference between display none and visibility hidden? </h3>
<p> 
    Display none and visibility hidden both are used to hide the elements. The main difference is display 
    none doesn't take any space and is hidden but visibility hidden gets up its original space and is not 
    visible too.
</p>
