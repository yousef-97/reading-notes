# Intro & CH1 & CH8 & CH17 & CH18
## intro
**First its not hard to learn HTML(hyper text markup language) and CSS**
### How people access the wep
you should know these 4 things:
- web Browser like: (chrome,firefox) to access the website
- webservers :the webhost
- devices
- Screen readers: are programs that read out the contents of a computer screen to a user
  They are commonly used by people with visual impairments
 
### CH1 structure
 html containe from elements and each element has an attrebute often elements have opening and closing tags (e.g):   
 \<p class='hi'\> this is paragraph \</p\> which ***\<p\>*** is the **element** and ***class*** the **attribute name & hi is the att value**.
 - \<p\> :opreing tag 
 - \</p\> :closing tag
  #### main html elements
    - \<html\>\</html\> to indicates that anything between is HTML code
    - \<head\>\</head\> this contains information about the page and evry thing inside it not visble to site visitor
    - \<body\>\</body\> Everything inside this element is shown inside the main browser window
    - \<title\>\</title\> its shown in the top of the browser above where you usually type in the URL of the page you want to visit

### CH8: Extra Markup
 - \<!DOCTYPE html\> :declaration to tell a browser the page is using HTML5 version
 - \<!-\- -\-\> :for comments
 - ID attribute :uniquely identify that element from other elements on the page (used to edit the site using css and js)
 - Class attribute : identify several elements as being different from the other elements on the page (you can use more than one class for the same element)
 - block elements : after closing tag ther is an new line (e.g h1-h6,ul)
 - inline elements: ther is no new line after closing tag (e.g b,i)
 - div element:used for grouping the elements in block
 - spam element :used for grouping the elements in inline
 - iframe : little window that has been cut into your page and in that window you can see another page
 - meta : element lives inside the \<head\> element and contains information about that web page.

### CH17: HTML5 Layout
  helpful elemens alternatives to the <div> element like:
  - header & footer: The main header or footer that appears at the top or bottom of every page on the site.
  - nav :used to contain the major navigational blocks on the site
  - article :acts as a container for any section of a page that could stand alone and potentially be syndicated.
  - aside :two cases
    1. if its inside article it should contain information that is related to the article 
    2. but is aside out of articleit acts as a container for content that is related to the entire page
  - section : groups related content together and each section have its own heading
  - hgroup : heading group used to group together a set of one or more h1 through h6 elements so that they are 
    treated as one single heading
  
 ### CH18: Process & Design

**things you should know it befor starting build a wep page:**

1. **Who is the Site For?** the Interests ,people jobs and there ages not yhe same so you should know the answer of this qustion
1. **Why people visit your Website?** your wep site shoud be influenced by the goals of your users.
1. **What information your visitors need?** you know your wep site well but other people will not so you need to work out what          information they need in order to achieve their goals quickly and effectively
1. **Site maps** : organize organize the information into sections or pages.
1. **wireframes**: simple sketch of the key information that needs to go on each page of a site It shows the hierarchy of the information and how much space it might require.<br />  
# JS the ABC of programming
A. What is a script and how do I create one?
B. How do computers fit in with the world around them?
C. How do I write a script for a web page?

### What is a script and how do I create one?
**script** : is a series of instructions that a computer can follow to achieve a goal.
**writing script** : aim to your goal the put tasks to reach your goal.
you should devide a your goal to steps (e.g):
  - define the goal
  - design the script
  - code each steps  <br />
### How do computers fit in with the world around them?
  **Objects**
    each object can have its own:
    - Properties
    - Events
    - Methods

### How do I write a script for a web page?
 - keep javascript code in seprated file also css code 
- script element in html used to tell the browser to     load jacascript file    
