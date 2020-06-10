# An introduction to HTML and CSS basics
## Sonu kumar

Before we get started on the basics of HTML and CSS, We need to understand the basics of the internet and how a website work.
We view any website with the help of the web browser, our browser understand only 3 language i.e HTML, CSS and Javascript. The entire working can be divided into client-server model.
Clients are basically our phones, laptop and web browser and server stores all the information of website , webpage and apps. When we type in a URL like say “www.google.com”, the browser is sending a request to the server in the which all the information about the website is stored. Whichever page that we request, the server reads it and sends the information about the web page back to the browser and that is how we view the website.
Web development has two parts: Frontend and Backend
Frontend is basically whatever we see on the website and interact with and it is built using 3 languages i.e
1.	**HTML**:- HTML stands for Hyper text markup language.It is a markup language and help us to markup things on the website like header, section, footer, button etc. Bascially it help us to define the structure of the web page.
2.	**CSS**:-CSS stands for Cascading Style Sheets. Css is used to design our website by adding visual elements like color, layouts, fonts etc.
3.	**Javascript**:-It is a programming language which helps to make our website interactive. It is used to interact with user action like slides, scroll etc
## Basics of HTML

HTML stand for hyper text markup language. It is not considered as a programming language. It help us to provide a structure to our webpage. It used to markup the different parts of the webpage with the help of the tags.
Elements, tags and attributes
**Elements:**- contains opening tags, content, closing tags; for example,  
`<h1>Hello World!</h1>`
 Here in the above example h1 is the element  
 
**Tags:**- Once we wrap the element name in between the less than and greater than, angle bracket then it becomes a tag. There are two types of tag container and non-container tag, one which has both opening and well as closing tag are known as container tag and the one which has only opening tags are known as non-container tag  

Example:- `<h1>heading</h1>`, `<br>`
Here h1 is container tag and br is non-container tag.
**Atrribute**:-It provide some extra information about the element, which actually doesn’t appear as content in a webpage.Atrributes are only used in the opening tags
Example:- `<img src=”” alt=””>`
Here src is attribute of img tag.
  ## Basics of CSS

CSS stands for Cascading styling sheets. Css is used to design    our website by adding visual elements like color, layouts, fonts etc. To style elements they are first targeted and then the required styles are applied with the help of selectors, properties and values in CSS.
**Selectors**:- CSS selectors are used to "find" (or select) the HTML elements you want to style.
Example:- `h1{
}`
   Here h1 is the selector  

**Properties & Values**:-  Property determines the style that needs to     be applied and value determines the behavior of the property. It can be any property & value of the element.
Example:-
`H1{
Color: red;
}`
Here color is the property and red is the value.
**There are 3 types of selector in css**

1. **Type Selector**:- Type selectors target an element with the element name or element type. Eg:- h1,p etc.
2. **Class selector**:- Class Selector allows us to target an element with the class attribute defines inside the tag. For example
`<h1 class=”heading”>….</h1>`
.heading{
}
Here heading is the class selector
3.	**Id selector**:- ID selectors are unique selectors that cannot be reused anywhere inside the code.
 For example,

   `<div id="container"></div>`
In
  #container {

    background-color: red;
  }
Here container is id selector

 ## Refrencing CSS
 
There are 3 ways to include CSS in our HTML file:
1.	Inline styling:- In inline styling, we write our style inside the tag only.
2.	Internal styling:-In internal styling, we write our style inside the style tag placed inside the head tag.
3.	External styling:- In external styling, a separate stylesheet is created to write the CSS and then connected to the HTML with the link tag. The external file is saved with .css extension. The most preferred style by the developer is the external styling because it help us to keep our CSS and HTML files different from each other and doesn’t mess up the code.


