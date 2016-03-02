# Kicking Sass: How to Write CSS in a PostCSS World

For years, front-end developers have turned to preprocessors like Sass and CoffeeScript to fill in the gaps in native CSS and JavaScript. Although these tools have transformed and enhanced the way we write code, they've also forced us to work in nonstandard syntaxes, bouncing from one compiler to the next as we try to find the perfect build process. But what if there's a better way? Learn how postprocessors and transpilers can revolutionize your code and workflow. If the idea of writing proposed CSS4 and ES7 code today without compromising browser support sounds crazy, you're in for a surprise.

## Understanding the Git branches
Throughout the course of the workshop, we'll take a project built with Sass and jQuery and rebuild it using PostCSS, System.js and JSPM. The workshop will be broken up into several different stages, each of which corresponds with a Git branch:

* **step-one:** Start with this branch. CSS is written in Sass, and JavaScript uses jQuery with no script loader or ES6.
* **[step-two](https://github.com/degdigital/kickingsass):** Sass removed, and PostCSS added.
* **step-three:** jQuery removed, and System.js added.
* **step-four:** Final branch. JSPM added and configured to work with System.js.

If at any time you lose your place, just check out the corresponding branch to catch back up with the completed code.

## Software Requirements
* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en/)
* A text editor
* A terminal
* Admin rights to your computer