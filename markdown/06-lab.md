## Exercise 06-lab: 

### Introduction

We're covering two topics in the labs this week: **CSS grid** and handling **locaStorage** with JavaScript. However, this time most of the code is supplied and functions as it should, so you can just experiment with it, as explained below.

- Javascript: `console.log()` to check your code
- HTML: validate your code every few changes

---

### Task 1 - CSS grid layout

CSS Grid is complex and fairly new, but it provides the layout tools that front-end developers have wanted for some time.

You can reposition any element in the grid wherever you like, using a breakpoint.

1. Either clone or download the code from [GitHub 06-lab-cssgrid](https://GitHub.com/ctec3905/06-lab-cssgrid/) and run it in a browser. Change the window width to see the mobile and larger versions of the layout.
2. Add some text and image content inside the grid elements, and a 4-item menu in the `nav` tag, using flexbox (flexbox can be used to order elements *inside* a grid container) and resize the window in and out to test your new page.
3. Add another breakpoint above the 600px one, to rearrange the grid content areas for larger screen sizes. This doesn’t need to make design or logical sense - it’s just an experiment.
4. If you already started your site and have content, work out how you could arrange the main content areas using CSS grid.

You should have a responsive grid-based layout that works at mobile sizes, then at tablet, then at desktop widths (mobile styles plus two breakpoints).

---

### Task 2 - localStorage

Last week’s exercise demonstrated how to manipulate the Document Object Model (DOM) after receiving user input. This week, you will learn how to store and retrieve data to/from the browser’s local storage data store, so that is is retained between between browser sessions and can be used on multiple pages.

Think of it as an insecure but 'free' and server-less data store (Chrome has a 5MB limit, whereas cookies can store far less than even 1MB).

1. Either clone or download the code from [GitHub 06-lab-localStorage](https://github.com/CTEC3905/06-lab-localStorage/), load it in a browser and open Chrome’s console in the web inspector.
2. You’ll see three **data objects** of increasing complexity. These data objects were added to the browser’s `localStorage` when the page loaded (although they could have been taken from user input and then stored, we kept this code simple as possible). Examine this data to see its structure. This is the **same format** as many external JSON API data sources, which will be covered in a future lab.
3. Look through the code and read the comments so you can understand how data is added to localStorage, and how to extract part or all of it.
4. In the JavaScript file (work out which one from the HTML `script` tag!), change one of the values being added to localStorage and run the page again.
5. Add another item to one of the data objects (take care to omit the trailing comma on the final key-value pair or final object.
4. Style the appearance of the data using CSS - you could keep the existing list tag or use a table.

Your file should generate some different data, which is retrieved and displayed in your own way and, using your own CSS styles.

---

## 06 Lab learning outcomes:

- learn one method of laying out CSS grids
- understand the CSS grids can be changed with breakpoints
- use JavaScript to set and retrieve data from the browser
- understand why `JSON.stringify` and `JSON.parse` are required for writing and reading localStorage
- navigate around a JavaScript data object that uses JSON-like formatting
