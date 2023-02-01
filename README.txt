Layout Techniques
- Arrangement of the structure

1. CSS GRID CONCEPT / FLEXBOX
2. Traditional Layouting Structures : table

HTML
 - Access to css styling's via link
 - CSS GRID CONCEPT / FLEXBOX
 - Allow's us to make partions on the page : element  <div> : block level element
 - within the divs we can have content

HTML STYLES
 - Styling html docs using css.

 Rules (Ways to write css)
   1. Internal CSS : writing the styling rules inside the HTMl docs. : style html tag (internal)  <style> </style>
   2. Inline CSS : Inline , inside a HTML opening tag/element using a style attribute
   3. External CSS file : outside the HTML docs


   /*  The rule for external and internal css writing */
selector  {
    property: value,
    property: value
}

selector :    1. The name of the html element : p , button ,
              2. Use of the id attribute :
              3. Use of the class attribute : a class : a group of related things : groups HTML elements allowing them to access the
               same rules which were written once.




     Creating a LAYOUT TECHNIQUE.
     1. Traditional Way : Css properties and tables
     2. CSS GRID
     3. CSS FLEXBOX


CSS FLEXBOX :

// helps us to design flexible responsive layouts without having to use css properties like float and positioning

Tomorrow Sessions

Bootstrap GRID
: SYSTEM USED FOR CREATING LAYOUTS
: Responsive layout

Work / Use :
Series of tags when creating a bootstrap grid
1. A container
2. Rows
3. Columns

3 concepts will work together to create a layout and align the content

is fully built using the FLEXBOX tech.


Rules , around the usage.
To create a bootstrap grid :

1. Overall container : <div>  with a BS class of container or container-fluid
2. Ensure you have the meta viewport tag :     <meta name="viewport" content="width=device-width, initial-scale=1.0">
3. The first child element directly after a container , should be a div with a class a row
4. Inside rows the first child element is a div with a class col
Inside the class col that's where you place content.

Here : A viewport has 12 columns per row , and these columns are spannable
       The grid system ensures that the partions always add up to 12 ,


Responsive Classes

1. Bootstrap grid includes five tiers of predefined classes for building responsive layouts
2. The tier classes customize the columns to give a better/improved appearance to the partions
3. FIVE TIERS : col : extra small  : auto : default
                sm : small : max container width  :  <= 540px / 576px
                md : medium : max container width : <=720px / 768
                lg : large : max container width  : <=960px / 992
                xl : xtra large : max container width : <- 1140px / 1200

4. Gap between the colums in a row : 15px



































