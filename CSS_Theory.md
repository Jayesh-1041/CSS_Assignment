# Assignment CSS 

### **Q-1.**   What are the benefits of using CSS ?

**ANS :-** 
        2.Faster Loading Times.
        3.Responsive Design.
        4.Ease of Maintenance.
        5.Print-Friendly Pages.
        6.Easy Formatting Changes.

### **Q-2.**     What are the disadvantages of CSS?

**ANS :-**
        1.Cross-Browser Issues.
        2.Security Issues.
        3.Extra Work for Developers.
        4.Confusion due to many CSS levels.

### **Q-3.**     What is the difference between CSS2 and CSS3?

**ANS :-**
        CSS2 introduced a new box model which included padding, borders, and margins. CSS3 introduced the flexible box layout module, which allows for more flexible layouts.

### **Q-4.**     Name a few CSS style components.

**ANS :-** "At its most basic level, CSS consists of two components"
        1.Properties: These are human-readable identifiers that indicate which stylistic features you want to modify. For example: font-size , width , background-color.
        2.Values: Each property is assigned a value. This value indicates how to style the property.

### **Q-5.**     What do you understand by CSS opacity?

**ANS :-** The opacity property sets the opacity level for an  element. The opacity-level describes the transparency-level, where 1 is not transparent at all, 0.5 is 50% see-through, and 0 is completely transparent.
Example: 
div.first {
        opacity : 1;
}

div.second {
        opacity : 0.5;
}

div.third {
        opacity : 0;
}

### **Q-6.**     How can the background color of an element be changed?

**ANS :-** We can set background color by selecting the element by its class name of id name and then apply the background-color property on it to set background color.
Syntax :- background-color : color_name;
body {
        background-color : red;
}

### **Q-7.**     How can image repetition of the backup be controlled?

**ANS :-** The background-repeat property in CSS is used to repeat the background image both horizontally and vertically. It also decides whether the background image will be repeated or not.
Syntax :- background-repeat : repeat;
body {
        background-image: url("image link");
        background-repeat: repeat;
        background-repeat: repeat-x;
        background-repeat: repeat-y;
        background-repeat: no-repeat;
        background-repeat: initial;
}

### **Q-8.**     What is the use of the background-position property?

**ANS :-** The background-position property sets the starting position of a background image. By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.
body {
        background-image: url("image link");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
}

### **Q-9.**     Which property controls the image scroll in the background?

**ANS :-** We can specify a different value of the background-attachment property for each background image, separated by commas. The default value of image scrolling is scroll. Attribute Values: scroll, It prevents the element from scrolling with the contents, but scroll with page.
Example:-
.class {
        background-image: url(image link);
        background-position: center;
        background-repeat: no-repeat;
        background-attachment: scroll;
}

### **Q-10.**    Why should background and color be used as separate properties?

**ANS :-** The background property is a complex property in CSS, and if it is combined with color, the complexity will further increase. Color is an inherited property while the background.

### **Q-11.**    How to center block elements using CSS1?

**ANS :-** Block elements can be aligned by setting the left and right margins to "align" with the "margin":auto; and "text-align:center; property we can align the block elements into the center.block-level element occupies the entire spsce of its parent element.
body {
        text-align:center;
}

### **Q-12.**    How to maintain the CSS specifications?

**ANS :-** The CSS specifications are maintaind by the World Wide Web Consortoum (WWWC). Even though every browser supports CSS, there are many inconsistencies in the supported specification version.

``<!DOCTYPE html>``
``<html>``
``<head>``
``<style>``
``p {color: red;} ``
``</style>``
``</head>``
``<body>``

``<p>Assignment CSS</p>``

``</body>``
``</html>``

Ans :- Assignment CSS

### **Q-13.**   What are the ways to integrate CSS as a web page?

**ANS :-**      CSS may be added to HTML in three different ways.
 =>To style a single HTML element on the page, use Inline CSS in a style attribute. 
=>By adding CSS to the head section of our HTML document, we can embed an internal stylesheet.
=>We can also connect to an external stylesheet that separetes our CSS from our HTML.

### **Q-14.**   What is embedded style sheets?

**ANS :-**      An embedded style sheet in CSS allows you to define styles for an entire HTML document in one place. It’s a way to encapsulate your styling rules within the document itself.
Example:-
``<!DOCTYPE html> ``
``<html> ``
``<head> ``
    ``<title>Embedded</title> ``
      
    <!-- Embedded stylesheet -->
    <style> 
        h2 { 
            font-size: 1.5rem; 
            color: #2f8d46; 
            text-align: center; 
        } 
  
        p { 
            font-variant: italic; 
        } 
    </style> 
``</head> ``
``<body> ``
    ``<h2>Assignment</h2> ``
    ``<p>CSS</p> ``
``</body>`` 
``</html>`` 

### **Q-15.**   What are the external style sheets?

**ANS :-**      An external style sheet is a seperate CSS file that can be accessed by creating a link within the head section of the webpage. Multiple webpages can use the same link to access the stylesheet. The link to an external style sheet is placed within the head section of the page.

### **Q-16.**   What are the advantages and disadvantages of using external style sheets? 

**ANS :-**      Some of its primary advantages are increased website speed, time efficiency, flexibility, consistency, etc....
disadvantages are limited security, cross-browser issues, extera work for developers, etc....

### **Q-17**    What is the meaning of the CSS?

**ANS :-**      => CSS stands for Cascading Style Sheets.
=> CSS describes how HTML elements are to be displayed on screen, paper, or in other media
=> CSS saves a lot of work. It can control the layout of multiple web pages all at once
=> External stylesheets are stored in CSS files.


### **Q-18 :-** What are the media types allowed by CSS?

**ANS :-**    CSS media types allow you to tailor your stylesheets based on the characteristics of the device or medium that displays your web content.
=> all: Used for all types of devices.
=> print: Intended for paged material and documents viewed in print preview mode.
=> screen: Used for computer screens, tablets, smartphones, and other similar devices.
=> max-hight, min-hight, max-width, min-width, width

Example:-

@media screen and (min-width: 480px) {
  body {
    background-color: lightgreen;
  }
}

### **Q-19.**   What is the rule set?

**ANS :-**      A CSS rule set contains one or more selectors and one or more declaration.
The selector(s), which in this example is h1, points to an HTML element. The declaration(s), which in this example are color: blue and text-align: center style the element with a property and value.