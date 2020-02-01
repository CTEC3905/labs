## Exercise 1: introduction to using the browser

1. Open the Chrome Browser (**NOT** Internet Explorer!)
2. Open this website to analyse: [developer.github.com](https://developer.github.com/)
3. Use “View Page Source” and also “Inspect” (tutor to guide)
4. Note the difference between how the source code appears (tutor to demonstrate)
5. Make some notes about how you think the site works technically (tutor to give examples)

---

## Exercise 2: introduction to workflow

1. Create a folder for this exercise in a place of your choice, making sure you can locate it again
2. Open the empty folder in a programmer's text editor - if Atom isn't installed, go to [software.dmu.ac.uk](http://software.dmu.ac.uk/) and select it for download, using the arrow on the right, then double-click to load it
3. Make a simple “index.html” page using your current knowledge (you can look things up if you've never done this before or use this [empty HTML page example](https://www.w3schools.com/html/html5_intro.asp))
4. Add some visible content e.g. inside an opening and closing HTML level 1 heading tag (`<h1>`)
5. Load the page in the Chrome browser

---

1. Add some content to the page and **reload it in the browser** each time you make a change (Windows/Mac: ctrl-R/cmd-R)
2. Check your code in the [HTML validator](https://validator.w3.org/) and correct any errors (repeat by validating each time you add more code)
3. Create a “styles.css” file inside a “css” folder and link it in your HTML file by adding this line in the HTML `head` section: `<link rel="stylesheet" href="css/styles.css">`. Note how the URL in the `href` attribute opens the “css” folder before requesting the file!
4. Add the following line to your “styles.css” file: `body { background: #f99; }` and reload the HTML page
5. Try some more styles in your “styles.css” file, reloading the page each time

---

1. Create a “scripts.js” file inside a “js” folder and link to it in your HTML file just before the closing `</body>` tag like this: `<script src="js/scripts.js"></script>`
2. Add the following to your “scripts.js” file: `alert("Hello!");` and reload the page in the browser
3. If the above works, change it to: `console.log("Hello!");`
4. Reload the page, open the Inspector and check the browser console panel (it should say “Hello!”)
5. Close down the browser, text editor and the folder containing your code
6. Find the folder again open it in the text editor Atom, and also open the HTML page in the browser

---

You have now completed the basic workflow for writing and running your code in a web browser.

NOTE: if you've finished, please set up a GitHub account if you don't have one. **Don't** connect to the GitHub Classroom yet.

You should also **revisit the lecture slides** and try the CSS styling.
