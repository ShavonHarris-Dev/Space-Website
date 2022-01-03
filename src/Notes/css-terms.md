// css is all about property: value pairs

// properties are what we want to change like color and size

//value is what we want to change that property to. 21px. red.

// there must always be a colon and semi-colon. font-size: 21px;


//The style attribute is an inline method. Not secure.
//<h1 style = "font-size: 70px; color:red;">Linking between pages</h1>

// font-size
//Cover
// background-color
// text-align

//coloras can be set with keywords, hex codes, rgb, and hsl values. You should use hexadecimal values. You can google search color picker 

//<h2 style = "text-align: right"></h2>


Internal CSS
we can use a stylesheet
makes chages global
in the head
<style>
    CSS goes here
    </style>

    we style with Selectors
    like body!
    
    body{
        color: #323232
    }
    color is property
    #323232 is the value
    The property:value together is called a declaration

    from the selector to the closing curly brace is called a RULE

    external CSS
    To change all the pages at the same time 
    One stylesheet controlling all of our oages at one time

    element selectors like a, h2, body, p

    the class selectors .
    classes are a type of attribute we can add to an html element
    
    < p class="intro>...</p>
    
    .intro {

        font-size: 18px;
    }

The ID selectors
Ids are a type of attribute we can add to an HTML elememt

<p id="intro">...</p>

#intro{
    font-size: 18px;
}


Id vs class

Id is an individual
A class is a group

You can only have an id once on a page
a class can be used as many times as you'd like
an ID will overwrite a class

Don't use ID's as much. Stick with classes as much as possible when it comes to styling. 

if you want a space use a hyphen 
class = a-box

auto keyword on the left and the right will center text in the middle of the page 
margin-left: auto
margin-right: auto

this is to center an element like the main section
You need to have a width set
shorthand is 
margin: 0 auto;
This will not work on the top and bottom to center vertically

Fix the margin problem

body{
    margin:0;
}