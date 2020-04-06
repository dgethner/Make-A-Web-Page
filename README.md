# Make-A-Web-Page

## Requirements

In order to demonstrate your new skills, your project needs to meet some specific requirements. We've provided a detailed checklist below.

If you feel confident and want a shorter description of the requirements, you can also check out the project rubric, which is exactly what your reviewer will be looking at when they grade your project.

Before submitting your project, check to make sure your project meets each of these requirements:

### 1. Your submission has an HTML file and a CSS file

For this project, you'll need to have at least two files:

* An HTML file. This contains the HTML code that gives the structure and content of your page.
* A CSS file. This contains the CSS code that styles your page.


### 2. All of your styling is done using a separate (linked) CSS file

Remember that you can do CSS styling in two ways:

* You can put the CSS code inside your HTML file, using the ```<style>``` tag or the ```style``` attribute. For this project, do not do it this way.
* You can put all of your CSS code in a separate file (usually this file is simply named style.css). This makes it a lot easier to edit and maintain your styles, and this is what we want you to demonstrate for this project.

Remember, you’ll need to link your HTML file to your CSS file using the ```<link>``` element (if you downloaded the starter files, your HTML code will already have the ```<link>``` element in it).

### 3. You've checked your code to make sure it has valid syntax
We want you to demonstrate that you know how to identify and fix syntax errors. One of the quickest ways to check your code for syntax errors is to run it through an automated validation check.

Before submitting your project, go to these validators and check your HTML and CSS files for validation errors:

* [HTML Validator](https://validator.w3.org/)
* [CSS Validator](https://jigsaw.w3.org/css-validator/)

If you get validation errors, don’t panic! Read the errors and try to figure out what they mean and how to fix them. It’s often helpful to copy and paste the error messages into Google.

### 4. Your page demonstrates how to use HTML to structure text
HTML gives structure to your page. You can make your page about anything you like, but we want you to demonstrate that you know how to structure your content. The first part of that is to make sure you have at least three sections of structured text.

Each section should have:

* A title that is formatted with a heading element (```<h1>```, ```<h2>```, etc.)
* At least one paragraph of text, enclosed within a paragraph element (```<p>```)

Notice how this page (that you're reading now) has structured text like this—it has a series of sections, each one of which has a title and some paragraphs.

### 5. Your page demonstrates how to use container elements
When you have structured text, like a title followed by a paragraph, you can think of those parts as conceptually related. That is, the title and the paragraph are probably about the same concept. And you might also have an image that shows a picture of something related to that concept.

For example, if you look at the first item on this list (1. Your submission has an HTML file and a CSS file), you can see that it has a title, paragraphs, and image, that are all related to the same concept.

When you have structure like this in your page, it's a good idea to put each set of conceptually related elements inside of a container element, like a ```<div>```. That way, you can apply a style to the ```<div>``` (like centering the content on the page), and it will affect all of the related elements inside.

So for this project, we want you to demonstrate how to wrap up conceptually related elements inside a ```<div>```, and then apply a style to that ```<div>``` using a CSS class.

To be specific:

* Your HTML file needs to contain at least 3 ```<div>``` container elements.
* Each ```<div>``` element should contain multiple conceptually related pieces of content (like a title, paragraph, and image that are all about the same thing).
* Each ```<div>``` element should have a class applied to it.

### 6. Your page demonstrates how to use CSS selectors
In order to apply a style to anything in your HTML file, you'll need to use CSS selectors in your CSS file. For this project, your CSS file needs to have at least three selectors.

Here’s a reminder of what a CSS selector looks like:

```p { }```

This selector will apply styles to all of the ```<p>``` elements in your HTML file.

### 7. Your page demonstrates use of the ```class``` attribute and class selectors
If you want to apply a style to all of a particular kind of elements on your page, you can use an element selector, like the one we just showed above (which applies a style to all ```<p>``` elements).

But if you only want to apply a style to certain elements (such as making only some of your ```<p>``` elements a particular color), then you can use a class selector. Remember, that looks something like this:

```.myclassname {}```

Where ```myclassname``` can be anything you like (though try to choose a name that describes what the class is for).

To get the styling to be applied to an element, you would then use the ```class``` attribute on that element. For example:

```<div class = "myclassname">```

And now this particular ```<div>``` element will be styled using whatever rules you put in the myclassname class selector.

One of the most powerful things about using class selectors, is that you can create a single class selector and then apply it to multiple elements. For example, you could style multiple ```<div>``` elements using the same ```myclassname``` class that we created above.

To show that you know how to do these things, make sure that:

* At least one of the selectors in your CSS file is a class selector.
* Multiple HTML elements are styled using the same class selector.



### 8. Your page demonstrates the use of images
Make sure that:

* Your page uses the ```<img>``` tag to display at least one image.
* The ```<img>``` element includes alternative text (using the ```alt``` attribute) that describes the image.

Remember that you can either link to an image that's on your computer, or you can link to an online image (using that image's URL). If you're linking to an image on your own computer, you'll need to make sure that the image gets included with your submission (otherwise, we won't see it when we review your project!).

### 9. Your page demonstrates the use of hyperlinks
Make sure that your page uses the ```<a>``` element to provide at least one hyperlink to another page.

### 10. Your page gives credit
If any content (such as text or images) is not completely original, it's important to make sure that your page gives credit to the author.

For example, you may wish to include a poem or piece of artwork that was created by someone else; if you do, make sure to state who the original author is (or if the author is unknown, state where the work was taken from). If the work is taken from another website, provide a hyperlink to that website.

Please note that your code itself (that is, your HTML and CSS) must be completely original.


### Credit for this project's instructions  
*Goes to [Udacity](https://www.udacity.com/) in their Intro to Programming Nanodegree track*
