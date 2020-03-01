# Introducing CSS Chp. 10

<p>What CSS does – allows you to create rules that specify how the content of an element should appear.  Allows you to create rues that control the way each individual box (and content of that box) is presented.  The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.</p>

- Block level elements – look like they start on a new line
- Inline elements flow within the text and do not start a new line.

<p> A CSS rule contains two parts: a selector and a declaration
	P {
		font-family: Arial ; } = all elements shown should be in Arial typeface

The same rule can apply to more than one element if you separate the element names wth commas.

H1, h2, h3 {
	Font-family: Arial;
	Color: yellow; }
Property		Value</p>

# Introducing CSS

- External link. <link href=”css/styles.css” type-=text/css”
			Rel=stylesheet” />

<p>Internal CSS. <style type=”text/css”>. Usually sits around the head element.
	Body {
		Font-family: arial ;
		Background-color: rgb }
	H1 {
		Color: rbg (255.255.255); }
		</style></p>

- A site with more than one page should use an external style sheet.

- CSS Rules Cascade – Last rule, specificity, Important!
