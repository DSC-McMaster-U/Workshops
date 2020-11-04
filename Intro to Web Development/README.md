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
           |------------------|
                              
    <p>     My first paragraph.    </p>

  |-----|                         |-----|
Opening tag                     Closing Tag

|------------------------------------------|
              Paragraph Element
```
- **Opening Tag** - Every element start with an `opening tag`, which contains the keyword (`p` is used for paragraph elements) enclosed in angled brackets `<>`. 
- **Content** - If the element has any content, it comes after the `opening tag` and this is what gets displayed on the webpage. 
- **Closing Tag** - To denote where the content finishes, we must end our element with the `closing tag` which follows the same syntax as the opening tag, except it contains a `/` *forward slash* before the element name.
- **Element** - Opening tag, content and the closing tag together make the element. 

Not all html elements follow this syntax exactly. Let's look at two different types of elements we can have.

#### **Nested Elements**
You can put elements inside other elements like so:  
```html
<p> I am a <strong> nested </strong> element. </p>
```
This is called **nesting**. Here out text would appear normally, with the word **nested** being bolded.

#### **Empty Elements**
Some elements are **empty** and don't have any content associated. These elements **do not** require a closing tag.
```html
<img src="cat.gif"> <!-- Displays an image -->
<br> <!-- Line Break -->
<hr> <!-- Horizontal Line -->
```
<sub>Note: `<!--  -->` defines a comment in HTML </sub>


#### **HTML Attributes**
You might have noticed the image element above `<img src="cat.gif">` has the extra code `src="cat.fig"` along with the tag name `img`. The `src` keyboard here is an example of an HTML **attribute**. 

An HTML attribute provides additional info and may change the behaviour of the HTML element. The attribute should be placed in the opening tag and follow the syntax `name="value"`. 

Examples
```html
<!-- 'class' is a global attribute -->
<p class="notes">Elements can have attributes</p>

<!-- 'src' and 'alt' are img attributes -->
<img src="cat.gif" alt="Gif of a Cat">

<!-- 'href' is an anchor attribute -->
<a href="https://google.ca">Google</a>
```
<sub>**Global Attributes -** These are attributes that can be used with any HTML element.</sub>

- `class` - this attribute is mostly used for naming/grouping elements to apply styles (see [selective styling](#how-to-selectively-style-elements))
- `src` - Gives the image path (url)
- `alt` - The text to show when image can't be loaded onto the webpage
- `href` - The link that the anchor should navigate to (see [allowed values of href](#anchor-tag))




These are just some examples of attributes, there are a lot more specific to each HTML element but you rarely will use them. 
### Common HTML Tags

#### Anchor Tag

### HTML File structure

### Resources

## CSS Basics
What is CSSS?
### CSS Box Model

### CSS Syntax

#### How to selectively style elements?

### Where to put CSS code?

### Simplifying CSS using frameworks

### Resources

## JavaScript Basics
What is JavaScript?

### The Document Object Model (DOM)

### JS Examples

## Creating a Personal Website

## Deploying it to GitHub
