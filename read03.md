## Javascript Templating

Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source.
### Mustacge
is a **logic-less** template syntax,It works by expanding tags in a template using values provided in a hash or object.
- **logic-less:**there is no if statements ,for loops,just **atags** are repalced with a value.
- it ia often considered the base for JS templating
---
(e.g (Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn)) 

---
- Mustache is NOT a templating engine. Mustache is a specification for a templating language.

## Fleexbox
A flex container expands items to fill available free space or shrinks them to prevent overflow.
- display:flex;
- flex-direction(row (default): left to right|row-reverse | column | column-reverse;)
- flexx-wrap:(nowrap | wrap | wrap-reverse;)
- flex-flow (Applies to: parent flex container element)(This is a shorthand for the flex-direction and flex-wrap properties)
- justify-content(flex-start | flex-end | center | space-between | space-around | space-evenly | start | end | left | right |safe | unsafe;)
- align-items(stretch | flex-start | flex-end | center | baseline | first baseline | last baseline | start | end | self-start | self-end |safe | unsafe;)
align-content(flex-start | flex-end | center | space-between | space-around | space-evenly | stretch | start | end | baseline | first baseline | last baseline |safe | unsafe;)
### Properties for the Children (flex items)
- order(intger)
- flex-grow(intger)
- flex-shrink(posetive intger)
- flex-basis
- flex