front-end-formations
====================

Code School - Learn the latest versions of HTML &amp; CSS. Take a look at new HTML5 tags, form elements, attributes, input types, border-radius, box-shadow, gradients, and more.

### LEVEL 1 - Overview & Updates
Get an overview of HTML5 and CSS3, and learn which HTML elements have been updated in HTML5. 

#### THE NEW DOCTYPE
In HTML4 we have 3 different types of Doctypes, that simple putting are only copy and pasted from one project to the other. They are:

1. Strict: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">`
2. Transitional: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">`
3. Frameset: `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">`

Now in the HTML5, we only need a simple one: `<!DOCTYPE html>`

##### Challenge
Start out by writing the new HTML5 doctype into the index.html inside level_1/1


#### THE META DECLARATION
The meta declaration is another updated tag, in the HTML4 it has two attribute uncessary in the HTML5 and looked like: `<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">`. 

Now in the HTML5, a new attribute was added, and the meta for encode definition looks like: `<meta charset="UTF-8">`

##### Challenge
Write the new HTML5 `meta` declaration for specifying the character encoding of our document. It should use `UTF-8` as the encoding. Use the level_1/2/index.html

#### THE SCRIPT TAG
The script tag used normally for javascript inclusion, was updated. In the HTML4 we specify the `type` attribute as `text/javascript` like `<script type="text/javascript" src="script.js"></script>`. 

Now in the HTML5 they changed browsers so they can infer javascript as type, so the new script tag for HTML5 is: `<script src="file.js"></script>`.

##### Challenge
Assuming that we have the HTML inside level_1/3/index.html script tag in HTML4, remove the portion we do not need in HTML5.

#### THE LINK TAG

As the script tag in HTML4 we've been using the type attribute to specify the `text/css`, as in: `<link rel="stylesheet" type="text/css" href="style.css">`.

Now in the HTML5 specification the type attribute could be infered, so we finish with something like: `<link rel="stylesheet" href="style.css">`.

##### Challenge
Use the link tag to to include the external stylesheet, style.css, and only use the attributes necessary for the HTML5 version.

#### ALTERNATE VOICE OR MOOD
Some elements changed its semantic in the new HTML5. In HTML4, the `i` was a font style element that represents italic font. 

Now in the HTML5 the `i` tag represents text in an “alternate voice” or “mood”.

Some example uses for the `i` tag:
* Taxonomic designation;
* Technical term;
* Idiomatic phrase from another language Transliteration;
* A thought;
* Ship name in Western texts;

Usage example:
```html
    <p><i>I hope this fail</i>, he thought.</p>
```

##### Challenge 
Using the new semantics of HTML elements, mark up the text, “This is the finest piece of art I have ever seen” in the level_1/5/index.html to be represented in an “alternate voice” or “mood”.

#### STYLISTICALLY OFFSET
The `b` tag was also changed semantically. In old days it was only a font style element, but now it should be used to represent a stylistically offset.

Some example uses for the `b` tag:
* Key words in a document abstract;
* Product names in a review;
* Actionable words in interactive text-driven software; 
* Article lead;

Usage example:
```html
    <p><b class="lead">The event takes place this upcoming Saturday, and over 3,000 people have already registered.</b> In the first day of...</p>
```

##### Challenge
Using the new semantics of HTML elements, make the first paragraph an article lead, which needs to be “stylistically offset” from the following paragraphs. level_1/6/index.html

### LEVEL 2 - HTML5 Elements
Learn all of the new HTML5 elements, including the section, article, header, footer, and time elements, and also several others that will help make your markup more semantic.

### LEVEL 3 - HTML5 Forms
Learn all of the new HTML5 form input types, elements, and attributes.

### LEVEL 4 - CSS3 Styles
Learn modern CSS styling techniques, including border radius, box shadow, text shadow, box sizing, multiple backgrounds, and gradients.

### LEVEL 5 - Fonts & Interactions
Learn how to use web fonts with @font-face, create smooth transitions and manipulated elements in CSS with the transition and transform properties, and write CSS according to the principles of progressive enhancement.