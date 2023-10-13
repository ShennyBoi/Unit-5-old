# Unit5

<h1>SEAN UNIT 5 PROJECT</h1>

<h2>attributes</h2>

Images by <a href="https://www.freepik.com/free-vector/realistic-polygonal-background_13223084.htm#query=geometric%20background&position=3&from_view=keyword&track=ais">Freepik</a>

<h2>Notes for Sean:</h2>

<h3>General Notes</h3>

- "< link >" tag is for importing css style file
- anything in a php tag gets run on page load, even in an "onclick()"

<h3>Page Loading error:</h3>

- unclosed PHP tag
- page not created
- / wrong path

<h3>CSS files system:</h3>

- all.css is for all php files
- each specifically named css file is for specific php files

<h3>File path referencing:</h3>

- ./ = current
- ../ = parent
- ../../ = grand?parent

<h2>Shortcuts:</h2>

- <h3>VSCode</h3>

  - CTRL + H -- Find and replace
    - then ALT + L -- F&R In selection
  - CTRL + SHIFT + H -- find & replace in whole project
  - F2 -- Rename File
  - CTRL + SHIFT + ' -- New Terminal

- <h3>Chrome</h3>
  - F12 -- Developer view

<h2>CSS:</h2>

<h3>Justify Content</h3>

Justify-content determines how remaining space in the container will be<br>
distributed around the flex elements if there is any remaining space in<br>
the container main axis.

- <h4>Positional alignment:</h4>

  - justify-content: center -- Pack items around the center
  - justify-content: start -- Pack items from the start
  - justify-content: end -- Pack items from the end

  - justify-content: flex-start -- Pack flex items from the start
  - justify-content: flex-end -- Pack flex items from the end
  - justify-content: left -- Pack items from the left
  - justify-content: right -- Pack items from the right

- <h4>Baseline alignment</h4>

  - justify-content does not take baseline values

- <h4>Normal alignment</h4>

  - justify-content: normal

- <h4>Distributed alignment</h4>

  - justify-content: space-between -- Distribute items evenly.<br>
    The first item is flush with the start, the last is flush with the end
  - justify-content: space-around -- Distribute items evenly.<br>
    Items have a half-size spaceon either end
  - justify-content: space-evenly -- Distribute items evenly.<br>
    Items have equal space around them
  - justify-content: stretch -- Distribute items evenly.<br>
    Stretch 'auto'-sized items to fit the container

- <h4>Overflow alignment</h4>

  - justify-content: safe center;
  - justify-content: unsafe center;

- <h4>Global values</h4>

  - justify-content: inherit;
  - justify-content: initial;
  - justify-content: unset;

<h3>Display</h3>

display: < tag >;

- inline -- Displays an element as an inline element (like < span >). Any height and width properties will have no effect;
- block -- Displays an element as a block element (like < p >). It starts on a new line and takes up the whole width;
- contents -- Makes the container disappear making the child elements children of the element the next level up in the DOM;
- flex -- Displays an element as a block-level flex container;
- grid -- Displays an element as a block-level grid container;
- inline-block -- Displays an element as an inline-level block container;
- inline-flex -- Displays an element as an inline-level flex container;
- inline-grid -- Displays an element as an inline-level grid container;
- inline-table -- The element is displayed as an inline-level table;
- list-item -- Let the element behave like a < li > element;
- run-in -- Displays an element as either block or inline depending on context
- table -- Let the element behave like a < table > element;
- table-caption -- Let the element behave like a < caption > element;
- table-column-group -- Let the element behave like a < colgroup > element;
- table-header-group -- Let the element behave like a < thead > element;
- table-footer-group -- Let the element behave like a < tfoot > element;
- table-row-group -- Let the element behave like a < tbody > element;
- table-cell -- Let the element behave like a < td > element;
- table-column -- Let the element behave like a < col > element;
- table-row -- Let the element behave like a < tr > element;
- none -- The element is completely removed;
- initial -- Sets this property to its default value;
- inherit -- Inherits this property from its parent element;
