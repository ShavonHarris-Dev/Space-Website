// HTML tells the browser what the content we are writing actualli isFinite. This is a header or a paragraph. A link, etc

// Tags
// {/* <cover> opening tag

// </cover> closing tag */}
// This whole thing is an element 


// A book

// {/* <page>
//     <heading>
//     <subheadings>
        
//     </subheadings>
//     </heading>
// </page> */}


//headings denote hierarchy and page structure
// six levels of headings
// <h1></h1> to <h6></h6>
//paragraphs are your regular text <p></p>


// {/* <stron> The text inside is of strong impoertance</stron> */}
// {/* <em>Short for emphasis and it has stress emphasis. It makes texts italic</em> */}
// these are inline elements as opposed to paragraphs etc which are block 

// file nameing
// should be decriptive
// no spaces, use underscores, or hyphens
// use lowercase

// the main folder is called our root folder
// The homepage must be index.html
// indexedDB.html must be in the root folder not a subfolder

// images should be places in a sub folder for better organization

HTML Lists
Regular Bullet Points/ Navigation/ etc
numbered <ol> or  Bullet Points<ul>
inside you can use <li>
These by default are indented


Images require the src attribute 
<img src (url inside of quotes)>

Images are not valid without an alt attribute which is used to describe the image. Should describe the intent of the cat. Short but descriptive.

Alt Text
<img src= "cute-cate.jpg" alt=" a very cute cat">

If it id a decorative image or logo it doesnt need the alt text but still the alt attribute.
<img src= "logo.jpg" alt="">

<link href></link> links things together
<a> points at another place to take you there
<rel> is the relationship so
<link href ="css/style.css" rel="stylesheet">

cmd / is a helpful shortcut for comments
<!--  -->

the body selector will change mostly everything on the page since most of your html is within the body on the dom. However if you dd a rule with perhaps a selector like h1 it will overwrite the body selector

Tags so far
h1 - h6
p
strong and em
a 
ul, ol, and li
img 
header
main
section
footer
nav
div(generic)
apan


HTML Tags	HTML Elements	HTML Attributes

HTML tags are used to hold the HTML element.	HTML element holds the content.	HTML attributes are used to describe the characteristic of an HTML element in detail.


HTML tag starts with < and ends with >	Whatever written within a HTML tag are HTML elements.	HTML attributes are found only in the starting tag.
HTML tags are almost like keywords where every single tag has unique meaning.	HTML elements specifies the general content.	HTML attributes specify various additional properties to the existing HTML element.


The box model
Most elements are block level elements by default
- they have a width of 100% of their parent
they have a height of 0
the height grows to match the content 
they stay stack one on top of each other
-try to avoid setting a height


Margin and padding 
-Margins are used to control the position of an elemenet relative to those around it.

margin-left
margin-right
margin-top
margin-bottom

Margin shorthand

margin: 10px 20px 30px 40px
top, right, bottom, left
clockwise!!!!!

instead of    margin: 10px 10px 10px 10px
you can write margin: 10px 
this means all sides

margin: 10px 20px 10px 20px 
can be written as 
10px 20px
top and bottom left and right

margin: 25px 10px 15px 10px
25px 10px 15px
top left and right bottom
500px and 100px
top and bottom left and right


Padding is used to control the positioning INSIDE our element. 

Margin adds empty space to the outside and padding adds empty space to the inside

borders
main {
    border: solid yellow 20px;
}

you can do border-left
border-right
border-top
border-bottom
border-right

You can also overwrite code 

border: 10px solid red;

border-bottom: red
or 
border-left-style: dashed;