# Intro to CSS

## Exercise 1
* Download and save the webpage [*tbl.html*](./tbl.html) (or use your own copy).  
* In a text editor create a new file, paste in the following
```css
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color:#646464;
    color: #0295F3;
    line-height: 2.0;
}
```
* Save the file as *style.css* in the same directory as your copy of *tbl.html*.
* Return to your copy of *tbl.html*, add the following link element in the head the document
```html
<link href="style.css" rel="stylesheet" type="text/css">
```
* Save the HTML page and view it in a browser.
* The page should be 'styled'
* Add some additional CSS rules in *style.css* and experiment with different CSS properties. 
* Make sure you add separate CSS rules each of the tags used in the page i.e. headings, paragraphs, lists etc.
* The number of CSS properties can be overwhelming for beginnners. To start with just try to make yourself familiar with:
    * **Text-related properties** : alignment, changing fonts, line height, letter spacing etc.
    * **Basic box properties** : border, outline, padding and margin
    * **Setting the color of elements** using color names, hexadecimal values, and RGB values.
    * See https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS for more info on CSS.
        * Text related properties - https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals.
        * The box model - https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model.  

## Exercise 2
Playing around with different properties is usually fairly easy. The challenge in CSS comes when you need to work out which CSS properties are needed to implement a specific design. Have a look at the following image. How can you make your copy of *tbl.html* look like this image. To help, the fonts used are Garamond and Arial, and the colours are #f5f5f5, #434343, #d6d5d5 and #45b2f5.

![tbl](tbl.png "The tbl.html page styled")

## Exercise 3
This exercise is all about using selectors.
* Download [*population.html*](./population.html).
* This is a simple HTML page
* Create an external CSS file for this document and check this works i.e. add a simple rule for changing the background-color of the page.
* Now try the following:
    * Write a CSS rule that will set the font family of all the *li* elements to be Arial.
    * Write a CSS rule that will place a border around the *div* with the id attribute of *other_countries*.
    * Write a CSS rule that will colour all the *li* elements of the class *europe* red.
    * Write a CSS rule that will colour the background of all the *li* elements that are in an ordered list (*ol*) blue
    * Write a CSS rule that will colour the Word *seychelles* green

**Don’t make any changes to the HTML! Use CSS selectors to select specific parts of the document.**

## Exercise 4
This exercise is about using multiple classes, a common technique in web design.
* Download [*multiple-classes.html*](./multiple-classes.html) and [*multiple-classes.css*](./multiple-classes.css).
* Open the HTML page in a browser. Simply using the existing classes in the CSS file try the following:
    * Make the entire contents of the page Arial
    * Give the *h1* element a solid border
    * Put some space between the *h1* element and it's border
    * Make the entire list have a background-color of red and a solid rounded border
    * Put some space between the list elements
    * Put some space around the last paragraph

**Don’t make any changes to the CSS! Use the class attribute to apply the existing CSS rules to the HTML elements.**
