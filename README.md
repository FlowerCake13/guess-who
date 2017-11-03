# guess-who

Can we guess who you are based on what your favorite things are? Let's try it!

## Objective
Use **JavaScript Event Listeners** to display your favorite items on click of a button.

## Prerequisites
To complete this project, students should have the following:
* Basic understanding of HTML structure and attributes.
* Basic understanding of CSS properties.
* Basic understanding of JavaScript and DOM.

## Your Challenge

### Part I
To complete Part I, fulfill the following requirements:
1. Set up your project file structure through the command line.
2. Create the following:
* HTML, CSS, JS file
3. Link all of your files correctly.

### Part II HTML
To complete Part II, fulfill the following requirements in HTML:

1. Create a div with a class of container.
2. Create 9 buttons. Each button should have an id of button1, button2, button3...etc. all the way until button9. Each button should have a different category for your favorite items. For example:

```HTML
<button id="button1">Favorite Movie</button>
<button id="button2">Favorite Book</button>
...etc.
```

Choose any 9 of the following:
* Favorite Movie
* Favorite Book
* Favorite Place to Travel to
* Favorite Flavor
* Favorite Character
* Favorite Author
* Favorite Song
* Favorite Restaurant
* Favorite Food
* Favorite Social Media Star
* Favorite Game
* Favorite TV Show
* Favorite Band
* Favorite Color
* Favorite Store
* Favorite Animal

If you have another category in mind, let one of the instructors know to check if that will be appropriate.

### Part III CSS
To complete Part III, fulfill the following requirements in CSS:

1. Target the class of container.
  * width: 80%;
  * height: 600px;
  * display: flex;
  * justify-content: space-around;
  * align-items: center;
  * flex-wrap: wrap;

2. Target the button element.
  * width: 200px;
  * height: 200px;
  * border-radius: 200px;
  * outline: none;
  * font-size: 20px;
  * background-color: Choose your favorite color!

### Part IV JS
To complete Part IV, fulfill the following requirements in JS:

1. Create variables to store all 9 of your buttons! *Hint: Use ```document.getElementById()!```.*
2. Add Event Listeners to every button that will listen for a click. When the button is clicked, change the innerHTML of that button to your favorite thing!

Example:
```JavaScript
button1.addEventListener('click', function() {
  //My button1's text initially had "Favorite Movie". So now, I will change the innerHTML of that button to my favorite movie!
  button1.innerHTML = "Happy Feet!"
})
```
### Stretch Goals
1. Make this page iconically yours! What makes you, Your? Add pictures, text, and other enhancements to personalize this page. 
