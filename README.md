### Boxes css

1. Inline Boxes
    - that element occupies all the space

    - occupies only the space necessary for its content

    - causes no line-breaks after or before the element

    - Box model applies in a different way: heights and widths do not appy

    - Paddings and margins are applied only horizontally (left to right)

    - css display: inline (change block to inline)

2. Block level boxes
    - Elements are formatted visually as blocks

    - Elements occupy 100% of parent element's width no matter the content

    - Elements are stacked vertically by default, one after another

    - The box-model applies as showed earlier

    - default elements: body, main, header, footer, section, nac, aside, div, h1-h6, p, ul, ol, li, etc

    - css display:block (change inline to block)

3. Inline-block boxes
    - Looks like inline from the outside, behaves like block level on the inside

    - Occupies only content's space
    - Causes no line break
    - Box-model applies as showed
    - css display: inline-block

### Normal flow vs absolute positioning
Normal flow
- Default positioning
- Elements is in flow
- Elements are simply laid out according to their order in the html code
Default positioning
position: relative

Absolute Positioning
- Element is removed from normal flow: "out of flow"
- No impact on surrounding elements, might overlap them
- We use top, bottom, left, or right to offset the element from its relatively positioned container
position: absolute

### Layout 
Layout is 
1. Layout is the way text , images and other content is placed and arranged on a webpage
2. Layout gives the page a visual structure, into which we place our content
3. Build alayout: arranging page elements into a visual structure, instead of simply having them placed one after another(normal flow)

there are two types of layout

### page layout vs component layout
1. the 3 ways of building layouts with css
    - Float layouts
        - The old way ofo building layouts of al sizes, using the float css property, Still used, but gettubg iytdated fast
    - Flexbox
        - Modern way of laying out elements in a 1 dimensional row without using floats. perfect of component layouts
    - Css grid
        - For laying out element in a fully-fledged 2-dimensional grid. perfect for page layouts and complex components

Float
    - Elemennt is removed from the normal flow
    - Text and inline elements will wrap around the floated element
    - the container will not adjust its height to the element

Flex box
    - Flexbox is a set of related css properties for building 1-demensional layouts
    - The main idea behind flexbox is that empty space inside a container element cam be automatically divided by its child elements
    - Flexbox makes it easy to automatically align items to one another inside a parent container, both horizontally and vertically
    - Flexbox solves comon problems such as vertoca; centering and creating equal-height columns
    - Flexbox is perfect for replacing floats, allowing us to write fewer and cleaner HTML and CSS code
![1-demensional](1-demensional.png "Text to show on mouseover").
![Flexbox-terminology](Flexbox-terminolocy.png)
![Flexbox-cheatsheet](cheatsheet-flexbox.png)

### CSS GRID
- CSS Grid is a set of CSS properties for building 2-demensional layouts
- The main idea behind CSS Grib is that we divide a container element into rows and columns that can be filled with its child elements
- In two-demensional contexts, CSS Grod allows us to write less nested HTML and easier to read CSS
- CSS grid is not meant to replace flexbox! instead, they work perfectly together. Need a 1D layout? use flexbox, Need a 2d layout? Use css grid
![css-grid](css%20grid.png)
![css-grid-cheatsheet](cheatsheet-cssgrid.png)