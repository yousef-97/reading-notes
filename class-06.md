# JS Object Literals; The DOM
## OBJECT

**Creating Objects**:
its the same of any any type of data but the method and the properties should be inside curly braces.
**accessing an object**:
to access to the properties and method you will use the dot(.)

## THE DOM
DOM:document object modle<br />
### the dom tree:
- the document node
- element node
- attribute node
- text node
### caching DOM queries
methods that find elements in DOM tree
(e.g) var item = getElementById('id name')
here you storing the location of the node'<br />

### accessing elements:
first i notesed that finding the quickest way to access an element within your bage will make the bage seem faster.
- getElement ById('id)
- querySelector('cssselector) first element
- getElementsByTagName('tagName)
- querySelectorAll(cssSelector) alist of al matches
<document.getElementById('id') .... the dot is member operator.>
### white space nodes:
if you want to use the properteis like firstChild &lastChild you should use it and be sure there is no white spaces between tag elements.<br />
**when you create an element you have to remember that some of text node will move to the new element**.
#### accsessing and changing the text node:
nadeVlue prorperty used for return the text in the textnode and you can use it to update the content.
#### accessing & update text with text content(&innertext):
textContent(proprety):to update all text inside the node what ever if there is an another element node textContent will change all the text .  <br />
**innerText(pro)**: the sane but its not recomanded for resones:
- not standard
- it will not show the content that has been hidde
### adding or remaoing HTML content:
- innerHTML:(pro)have some security resks


