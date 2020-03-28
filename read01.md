# Responsive Web Design
Responsive web design is the practice of building a website suitable to work on every device and every screen size, no matter how large or small, mobile or desktop.
## Responsive Overview
### Responsive vs. Adaptive vs. Mobile
-  **Responsive:** generally means to react quickly and positively to any change.(continually and fluidly change based on different factors)
-  **adaptive:** means to be easily modified for a new purpose or situation.(built to a group of preset factors)</br>  
***thecombination of the tow is ideal,providing the perfect formula for functional websites***</br>  
- **Mobile:** you should build a separate website commonly on a new domain solely for mobile users.</br>**Responsive web design is broken down into three main components: flexible layouts, media queries, and flexible media**
### 1- Flexible Layouts:  </br>
The formula for relative width of the target element (target ÷ context = result)</br>

- Flexible Grid:
we can take all of the fixed units of length and turn them into relative units(using **em** and **%** for sizes and dimentions).
### 2- Media Queries:
Media queries provide the ability to specify different styles for individual browser and device circumstances.
- Initializing Media Queries:
  - by linking to a separate style sheet from within the HTML document.
  -  using the @media rule inside of an existing style sheet.
- Logical Operators in Media Queries:
  - and ( allows an extra condition to be added)
  - not (negates the query, specifying any query but the one identified.)
  - only( hiding the styles from devices or browsers that don’t support media queries.)
- Height & Width Media Features:
(e.g :@media all and (min-width: 320px) and (max-width: 780px) {...})
- Orientation Media Feature:
(e.g :@media all and (orientation: landscape) {...})
- Aspect Ratio Media Features:(width/height)
(e.g:@media all and (min-device-aspect-ratio: 16/9) {...})
- Resolution Media Feature(pixel density)
(e.g @media print and (min-resolution: 300dpi) {...})
### Viewport:( viewport meta tag in HTML)
some of 
- Height & Width 
- Scale
- Resolution
you can combining viewport value using comma(,).

