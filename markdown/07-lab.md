## Exercise 07-lab: 

### Introduction

This week’s lab follows on from the lecture material covering external data APIs. The [example repository](https://github.com/CTEC3905/07-lab-json-ajax) shows how to pull data from Wikipedia and has 3 branches with additional API examples.

For a more general introduction to APIs try the Codecademy [mini course](https://www.codecademy.com/apis) on using APIs with JavaScript.

- Javascript: `console.log()` to check your code
- HTML: validate your code every few changes

---

### Task 1 - run the code and inspect it

The master branch shows how to use the public Wikipedia API.

Navigate to the folder where you store your CTEC3905 work, then `git clone https://github.com/CTEC3905/07-lab-json-ajax.git` and `cd 07-lab-json-ajax`.

Create a new repository on your own GitHub account and copy its remote URL (from the green "Clone or Download" button), then back in the command-line, change the remote to your new repo with `git remote set-url origin YOUR_NEW_REPO`, then check it with `git remote -v`.

You can then experiment with the code, make changes, and push your version to your own account.

### Task 2 - experiment with the code and look up API documentation

Play with the existing code and try to change some of the query parameters.

Explore the Wikipedia [API sandbox](https://en.wikipedia.org/wiki/Special:ApiSandbox#action=query&titles=Main%20Page&prop=revisions&rvprop=content&format=jsonfm).

Check the [help pages](https://en.wikipedia.org/w/api.php?action=help) for the Wikipedia API.

The master branch code runs without needing to change anything.

Read through the comments and try and understand what is happening.

Look at the gatherData function and try and follow how the list of responses is formatted.

Comment in the console.log statement on line 41. Then inspect the JavaScript console and look through the response object. Try and find the items that we display on the results page. You can also try and copy the url shown on line 37 into your browser. This will display the JSON data there. Run it through a [JSON beautifier](https://codebeautify.org/jsonviewer) to make it more readable.

---

### Task 3 - Look at the different branches

First close Atom, then commit any changes you've made! There's a problem with Atom running in CloudPlayer that prevents GIT from storing the changes properly.

First, see the list of available branches using:  
`git branch -a`. You’ll check one of these out in a moment.

Make sure you closed Atom, and added and committed any changes you’ve made to your master branch. Then change to one of the other branches using:  
`git checkout flickr`

Note how the files in your local repository have changed. Inspect the new code and run it in the browser. Read the readme file and follow the links to get a Flickr API key, etc.

When you are ready to check out another branch, add and commit all your changes, close Atom, and then "checkout" another branch.

---

## 07 Lab learning outcomes:

- successfully clone a repository and push it to a new repository of your own
- understand how to obtain external API data from differing APIs
- use JavaScript to parse and navigate through JSON data
- checkout GIT branches from a cloned repository
