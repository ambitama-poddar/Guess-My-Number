# Guess-My-Number

## Summary
In this project, Guess My Number, I aimed to create an interactive game where the user tries to guess a secret number. I utilized DOM manipulation to select elements from the HTML document and update their content based on user input. Through the use of JavaScript, I dynamically modified the game's interface and provided feedback to the user.  

## Demo
To see a working demo of Guess My Number, you can visit https://ambitama01.github.io/Guess-My-Number/. The project features a retro design inspired by classic 80s games, making it even more fun to play!

The objective of Guess My Number is simple: we need to guess a secret number between 1 and 20. Enter your guess in the input field, click "Check," and you'll receive a message indicating if your guess is too low or too high. With each failed guess, your score decreases by one. When you guess the correct number, the screen turns green and you receive a "Correct number!" message. The highscore is also displayed, representing the best score achieved so far. If you want to play again, simply click the "Again!" button to reset the game, except for the highscore.

## Project Files
To access the project files, please visit the [GitHub repository](github-repository-link-goes-here). Inside the repository, you will find the following files:

- **Prettier configuration**: Contains the Prettier configuration used for code formatting, which should be used throughout all projects in this section.
- **Empty Script**: An empty JavaScript file where you will write the code for Guess My Number.
- **CSS Style**: The CSS file responsible for the styling of the project. You can explore it if you're interested.
- **HTML**: The HTML file that defines the structure of the project's interface. It's important to note that the class names used in this file will be used for element selection in JavaScript.

## DOM Manipulation
In Guess My Number, we will be utilizing DOM manipulation to interact with the HTML document displayed in the browser. DOM manipulation refers to the process of accessing and modifying elements on a webpage using JavaScript. By manipulating the DOM, we can dynamically update the content and appearance of the interface based on user input or other events.

## Selecting Elements
To select elements from the HTML document, we will use the `document.querySelector()` method in JavaScript. This method allows us to select elements based on CSS-like selectors. For example, to select an element with a specific class name, we use `document.querySelector('.classname')`, and to select an element by its ID, we use `document.querySelector('#id')`.

## Accessing Element Content
Once we have selected an element, we can access its content using the `textContent` property. For example, if we select an element with the class name "message" using `document.querySelector('.message')`, we can retrieve its text content by accessing `textContent` on the selected element.

