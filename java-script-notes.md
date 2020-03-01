# Javascript Pgs, 43-69 

<p> Html – content layer.  This is there the content of the page lives.  The html gives the page structure and adds semantics.

CSS – The CSS enhances the HTML page with rules that state how the HTML content is presented (background, borders, box dimensions, colors, fonts, etc.).

JS files – This is where we can change how the page behaves, adding interactivity.  Aim to keep as much of the Javascript as possible in separate files.

Each layer builds on the previous one – progressive enhancement. </p> 

<p> A Javascript file is just a text file, but it has a ,js file extension.  Example:  add-content.js
The HTML script> element is used to load the Javascript into the page.  It has an attribute called src, whose value is the path to the script you created.  Usually added just before the closing body tag. 
		
CSS line in head: <link rel=”stylesheet” href=”css/c01.css” />

<p>
Document.write	Example: document.write(‘Good afternoon!’);
Calling a method of an object.

 <li> The document object represents the entire web page.
 <li>The write () method of the document object allows new content to be written into the page where the script element sits.  
 <li> Whenever a method requires some info to work, the data is given inside the (parenthesis)
 <li>	. (period) member operator
 <li>	Each piece of info is called a parameter of the of the method. </li>
</p>

<p> Javascript runs where it is found in the HTML.  When the browser comes across a script element, it stops to load the script to see if it needs to do anything.  Note the script element can be moved below the first paragraph, and this affects where the new greeting is written on the page.  This has implications for where script elements should be placed and can affect the loading of pages.

A script is a series of instructions that a computer can follow one-by-one.  Each individual instruction or step is known as a statement.  Statement should end with a semicolon.  JS is case sensitive.  

Statements are instructions and each one starts on a new line, a semicolon tells JS when the step is over.  Statements can be organized into code blocks = statements surrounded by curly {} brackets (not followed by a ;). </p> 

<p>Comments: // This is my comment in my code to explain something.
Mult-line comments: /*     */

Declare the variable.
	var quantity; 
var – keyword; quanitity – name	camelCase for more than one work
					kebob name_name

Once you have created a variable, you can tell it what info you would like it to store.  You assign a value to the variable.

Quantity = 3;

You can now use the variable by name.  = is an assignment operator.  Until you have assigned a value to a variable, the value is undefined.
Boolean – true false, on off, etc.  Used when code can take more than one path.</p>

* Rules for Naming Variables:
1.  The name must begin with a letter, $ or an underscore_, NOT a number.
1.  The name can contain numbers, $ or an _, not a dash or period.
1.  Cannot use keywords or reserved words.
1.  Case sensitive.
1.  Use a name that describes the kind of info that the variable stores.
1.  Use camelCase or kebob_kebob
