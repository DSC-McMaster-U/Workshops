# Intro to Web Development
Welcome to our **Intro to Web Development Guide**. This workshop walks you through:
- The basics of web HTML/CSS/JavaScript
- How to create your personal website
- Hosting your website using GitHub pages

Find the workshop slides and recording here:
- Slides:
- Recording:

Find the code for this workshop under the **code** folder.

## HTML Basics
**What is HTML?**<br>
HTML stands for **Hyper Text Markup Language**. It is not a programming language. Instead HTML is the code that defines the structure of the webpage and its content. 
The basic building block of HTML is called an **element** (think of them as lego bricks). These elements labels the type of content we are displaying, eg. if the content is a paragraph, heading, link, image etc.                    

Let's look at what these elements look like.

### Anatomy of an HTML Element 

```html
                 Content
           --------------------
    <p>     My first paragraph.    </p>
   -----                          ------
Opening tag                     Closing Tag

--------------------------------------------
              Paragraph Element
```
- **Opening Tag** - Every element start with an `opening tag`, which contains the keyword (`p` is used for paragraph elements) enclosed in angled brackets `<>`. 
- **Content** - If the element has any content, it comes after the `opening tag` and this is what gets displayed on the webpage. 
- **Closing Tag** - To denote where the content finishes, we must end our element with the `closing tag` which follows the same syntax as the opening tag, except it contains a `/` *forward slash* before the element name.
- **Element** - Opening tag, content and the closing tag together make the element. 

Not all html elements follow this syntax exactly. Let's look at two different types of elements we can have.

#### Nested Elements
You can put elements inside other elements like so:  
```html
<p> I am a <strong> nested </strong> element. </p>
```
This is called **nesting**. Here out text would appear normally, with the word **nested** being bolded.

#### Empty Elements
Some elements are **empty** and don't have any content associated. These elements **do not** require a closing tag.
```html
<img src="cat.gif"> <!-- Displays an image -->
<br> <!-- Line Break -->
<hr> <!-- Horizontal Line -->
```
<sub>Note: `<!--  -->` defines a comment in HTML </sub>



### HTML Attributes


### Common HTML Tags

### HTML File structure

### Resources

## CSS Basics
What is CSS?
### CSS Box Model

### CSS Syntax

### Where to put CSS code?

### Simplifying CSS using frameworks

### Resources

## JavaScript Basics
What is JavaScript?\
Javascript is lightweight, cross platform language mainly known for its uses in web development. Its popularly used in frameworks for Web Development like Node.js.

An example of what Javascript is capable of doing is present below:\

```html
<script><!-- Script tag to embed Javascript into HTML -->
document.getElementById("demo").innerHTML = "Hello JavaScript!"; <!-- Use of DOM will be explained further below -->
</script>
```

### The Document Object Model (DOM)
What is Document Object Model (DOM)?\
Document object model is a model that JavaScript uses to organize different HTML tags in an HTML webpage as objects so they can be easy to work with.

The model can be seen in the picture below for further illustration:\
[<img src="https://www.w3schools.com/js/pic_htmltree.gif">](https://www.w3schools.com/js/js_htmldom.asp)

An explanation of the previous example is present here:
```html
<script>
document.getElementById("demo").innerHTML = "Hello JavaScript!"; <!-- Starts with the document object and follows the hierarchy to demo and changes what is inside of the tags(innerHTML) to "Hello JavaScript!" -->
</script>
```

### JS Examples
A few key examples for JavaScript use:

Functions:
```javascript
//Function declaration
function myFunction(a, b) {
  return a * b;
}

//Function call
a = myfunction(1,2);
```

Loops:
```javascript
var i;
var num;
//For Loop structure
for (i = 0; i < 3; i++) {
  num += i;
}

//While loop structure
while (i < 3) {
  num += i;
}
```

Objects:
```javascript
//Object declaration and assignment
var car = {type:"Fiat", model:"500", color:"white"};

//Accessing object data
var a = car.model;
```

[Useful Resource for more examples and further documentation](https://www.w3schools.com/js/default.asp)

## Creating a Personal Website

## Deploying it to GitHub
