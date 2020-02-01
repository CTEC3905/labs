For all exercises, [**validate** your HTML](https://validator.w3.org/) and use **inspect** in the browser (Chrome!!) to check the **console messages**.

This week may be a challenge - use the **02 Lecture** slides for reference - if you complete everything today, well done!

If not, don't worry - use your **Self-directed Learning Time (SDL)** to work on your code before next week's lab. If you get stuck, **keep trying**! The simplest version of the solutions will be demonstrated next week.

---

## Exercise 1: getting familiar with HTML5 and CSS

1.  Create a basic HTML file `index.html`, a CSS file `styles.css` and a “js” folder containing a JavaScript file `scripts.js`
2.  Mark up a simple 5-item menu with “`a`” tag links (`<a href="#">link text</a>` tags) inside a `nav` tag. Keep it simple and don’t use any other tags to do this
3.  Style the menu to appear horizontally across the top of the page using **CSS flexbox** ([Flexbox cheat sheet](http://flexbox.malven.co/))
4.  create a `:hover` style for the menu items
5.  use a CSS `transition` to make the menu item background fade to another colour on hover (**clue:** the CSS `transition` rule goes on the “`a`” tag selector rule, **not** the `a:hover` selector rule)

---

1.  Add a `header` section above the `nav` tag, containing an `h1` tag with a few words
2.  Add a `main` tag below the `nav` tag, containing a paragraph “`p`” tag with the text "Click me to say hello"
3.  Adjust the `body` and `h1` margins so that `body`, `header`, `nav` and `main` have no gaps between them
4.  Use flexbox (cheat sheet below) to stack the “`a`” tags in the `nav` vertically, and set a width of `15%` to the nav tag and `85%` to the `main` tag
5.  Set left-right `padding` on the `main` tag, then use `float: left;` and `float: right;` on the `nav` and `main` with `box-sizing` to contain the `main` tag padding

---

## Exercise 2: simple JavaScript interaction

1.  Add an `id` attribute of `"hello"` to the “`p`” tag
2.  use `document.getElementById();` to set a JavaScript `const` property named `hello` to store a reference to the paragraph
3.  attach an `eventListener(){}` to the `hello` variable that listens for a `"click"` event and calls a named function `greeting`
4.  write a `greeting` function that sends a message to the console using `console.log();`
5.  add another line inside the `greeting` function that changes the text of the paragraph to a text string of your own

---

Nice work! You have now completed the **02 Lab learning outcomes**:

- Link a stylesheet to an HTML file
- Successfully add styles to change HTML elements
- Understand basic CSS syntax and flexbox
- Use different CSS selectors to target specific tags and states
- Create HTML semantic markup that can be re-arranged using CSS
- Handle a simple user interaction using a JavaScript event listener
- Understand how `getElementById and` and `eventListener` work together

These links will help you with the code:

- [Flexbox cheat sheet](http://flexbox.malven.co/)
- [Targeting HTML and changing CSS with JS](https://ctec3905.github.io/js-get-elements/): this example page ([source code on GitHub](https://github.com/CTEC3905/js-get-elements)) shows how to target various HTML elements and make changes to CSS via JavaScript. It uses `addEventListener()` and various types of `getElement(s)By` functions. It will help you understand **how to use JavaScript** to **interact with the DOM**.
