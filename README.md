# CS50 Project 0

## Web Programming with Python and JavaScript

This is a website about me, my interests and some stuff related to music and a rock band where I sing and play guitars.

It contains 4 html pages and 2 stylesheet files. It is possible to get from any page on this website to any other page by following hyperlinks in _Navbar_. Which I implemented using **Bootstrap**.

<img src="images/tree.png">

**style.css** uses:

1. At least 5 different css properties;
2. At least five different types of CSS selectors;
3. Includes one mobile-responsive @media query
4. Includes `:inside` selector to insert an image before an element
5. Multiple selectors: `element, element`
6. .Class and #id

**variables.scss**

- Contains two variables `$bgcolor` and `$color` to modify the footer included in all the `.html` pages of the site (SCSS variables)
- Contains a general pattern `%rodape` that inherits to the `.footer` class (SCSS Inheritance)
- `.footer` class has `span` that modifies the text in the footer contained in all span nested in `.footer` class (SCSS nesting)

**Navbar** 

- Every page has a `Navbar` with links to the other pages and changes the active item according to the current page.
- This is a Bootstrap `Navbar` with horizontal links, with reponsive behavior. Hidden when printing.

**index.html**

- Contains a banner type image. Each `.html` files contains a different one;
- Uses Bootstrap `.container` and `.navbar` classes;
- Uses two Bootstrap columns for layout purposes (Bootstrap's grid model) to display information. Both columns are mobile-responsive using `@media screen`. For screens bellow 600px each column width is set to 100% and for screens bellow 992px each columnd width is set to 50%;

**interests.html**

- Contains two unordered lists with links to sites related to the topic;
- Each links opens up on a new tab 
- Contains one image for each topic using `div` classes `col-4` and `col-8`

**records.html**

- Contains a table using Bootstrap's `table` `table-striped` and `thead-dark` according to the colors of the website;

**gear.html**

- Contains an unordered list with a custom `guitar-list` class;
- `guitar-list` class uses a guitar icon image before each item on the list


